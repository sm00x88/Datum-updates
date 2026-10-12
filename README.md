# DATUM updates

Public update feed for DATUM apps. Installed copies read this repository to find new versions.

- `project/latest.json` — the current DATUM Project update (version, size, SHA-256, signature).
- `project/files/` — the signed update files.

Every update is signed with Sam Francis's private key and checked by the app before it is used. Files here cannot change an installed app unless the signature and checksum match. The private key is never kept in this repository.
