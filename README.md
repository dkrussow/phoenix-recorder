# Phoenix Recorder

A one-page voice recorder for Phoenix Photo. It opens from the **Record a story** button next to a photo, shows that photo while you talk, and sends the recording back to the archive.

It only talks to a Phoenix Photo web app address (`script.google.com/macros/s/…/exec`) given in the link, and only with a one-time code from that archive. Nothing is stored on this site.

## Website (`home/`)

The Phoenix Photo marketing site lives in `home/`: the home page, a privacy page (`home/privacy/`) and terms (`home/terms/`). It links to the install guide at `install/`.

- The feedback buttons read their address from `FEEDBACK_URL` near the bottom of `home/index.html`. It points to the Google feedback form.
- When the custom domain is ready, update the `og:url` and `og:image` addresses at the top of `home/index.html`.
