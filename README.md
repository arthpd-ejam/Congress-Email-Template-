# Congress Email Template

Static web app: pick your municipality, see your district representative, edit a template, and send it via a mailto link.

## Data
`data/reps.csv` — all 254 district representatives of the 20th Congress (as of Nov 2026), with a public email and its source where one was found. Empty email = not found yet.

### Email sources
- LEDAC members page and provincial/city government websites (link per row in `email_source`).
- 19th Congress House members directory (2022 compilation). Used only where the same person was re-elected in 2025. Two obvious typos were corrected (noted per row).
- Rows marked "verify" use a non-official (Gmail/Yahoo) address.
