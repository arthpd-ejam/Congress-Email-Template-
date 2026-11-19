# Congress Email Template

Static web app: pick your municipality, see your district representative, edit a template, and send it via a mailto link.

## Data
`data/reps.csv` — all 254 district representatives of the 20th Congress (as of Nov 2026), with contact fields and sources where available.

- `email`, `alt_email`, and `email_source` contain public email addresses and their sources. Empty email = not found yet.
- `phone` and `phone_source` contain publicly listed office phone numbers and their sources. Notes flag switchboards or dated information that should be rechecked.
- `facebook_url`, `messenger_url`, `instagram_url`, `x_url`, and `tiktok_url` are official public contact links when verified. Empty fields mean no contact link has been verified, not necessarily that the representative has no account. `social_source` records where the links were verified.
- Rows marked "verify" use a non-official (Gmail/Yahoo) email address.

### Email sources
- LEDAC members page and provincial/city government websites (link per row in `email_source`).
- 19th Congress House members directory (2022 compilation). Used only where the same person was re-elected in 2025. Two obvious typos were corrected (noted per row).
