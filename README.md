# MISO Mac Guard Updates

Public distribution repository reserved for credential-free, signed MISO Mac Guard update artifacts.

## Current status

Automatic updates are under development. No update binaries or production update feed have been published here yet. Creating this repository does not enable automatic updates in existing installations.

## Publication policy

- Only credential-free update archives, integrity metadata, signatures, and public release notes belong here.
- Internal installers, deployment profiles, tokens, Slack credentials, device data, and application source code must not be uploaded.
- Reading or forking this public repository does not grant write or release permissions.
- The product updater must verify an embedded trust key and signed release identity before accepting an artifact. A download URL or checksum from the same repository is not sufficient authentication.
- Each published version must use a new release identity. Existing artifacts must not be silently replaced.

Do not install unverified artifacts from pull requests, forks, comments, or third-party links.
