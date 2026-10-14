# DATUM updates

Public update feed for DATUM apps. Installed copies read this repository to find new versions.

- `latest.json` and `files/` — the current DATUM (Studio & Project) update.
- `project/latest.json` and `project/files/` — the current standalone DATUM Project update.

Each `latest.json` gives the version, size, SHA-256 and signature of its update file.

Every update is signed with Sam Francis's private key and checked by the app before it is used. Files here cannot change an installed app unless the signature and checksum match. The private key is never kept in this repository.
