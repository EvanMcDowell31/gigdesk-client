# gigdesk-client

This repository publishes one file, [client.json](client.json): the OAuth
Client ID Metadata Document that identifies gigdesk, a self-hosted app, to
Upwork's sign-in server. GitHub Pages serves it at

    https://evanmcdowell31.github.io/gigdesk-client/client.json

and that address is gigdesk's client ID. The file holds no secrets. Its
redirect addresses are on 127.0.0.1 and localhost, so the browser hands each
sign-in back to gigdesk on the same computer.

Format: [OAuth Client ID Metadata Document](https://datatracker.ietf.org/doc/html/draft-ietf-oauth-client-id-metadata-document-00).
