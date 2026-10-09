# cimd-demo

OAuth Client ID Metadata Documents (CIMD) for a demo of Okta for AI Agents.

Each file under `.well-known/cimd/` is an agent's client metadata document: its
`client_id` is the file's own URL, and it lists the agent's redirect URIs and
**public** signing keys. No secrets live here.

See the [IETF draft](https://datatracker.ietf.org/doc/draft-ietf-oauth-client-id-metadata-document/).
