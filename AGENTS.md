# Public artifact repository

- Read `README.md` and use the `ws-artifact` skill.
- This repository and its full git history are public. Publish only material
  explicitly safe for the public web. Never include secrets, private source
  material, personal data, or internal URLs.
- Put each self-contained HTML artifact in a new, unique
  `artifacts/YYYY-MM-DD-short-title-unique-id/index.html` directory.
- Add a relative link to the gallery in root `index.html`. Keep existing links
  and artifacts intact. Do not overwrite an existing artifact unless asked.
- Validate interactions with Playwright at desktop and phone widths, and check
  console errors before publishing.
- A request to publish an artifact authorizes committing and pushing those
  artifact and gallery changes to `main`. Never force-push or bypass hooks.
- Wait for the Pages deployment for your exact commit and verify the exact live
  URL before including it as published in the reply.
