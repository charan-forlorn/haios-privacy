# HAIOS Privacy & Project Website

Public website for the HAIOS Dropbox Connector privacy notice.

- Website: https://charan-forlorn.github.io/haios-privacy/
- Privacy Policy: https://charan-forlorn.github.io/haios-privacy/privacy-policy.html
- Source is intentionally limited to public-facing project description and privacy notice. No HAIOS application source, credentials, access tokens, or account data are stored here.

## Published scope

The notice describes the current HAIOS Dropbox Connector R1 implementation:
- Dropbox OAuth scope: `account_info.read` only.
- Fixed API calls: `users/get_current_account` and `users/get_space_usage`.
- Local Windows/Python command-line execution.
- No file or folder content access and no Dropbox write operations.
- No connector-managed persistent token store or cloud database.
- Operator-controlled local stdout retention is distinguished from connector-managed persistence.

The policy must be updated before any material expansion in scopes, endpoints, processing, storage, sharing, or deployment model.

## Hosting

This site is published using GitHub Pages from the `main` branch, root directory.
