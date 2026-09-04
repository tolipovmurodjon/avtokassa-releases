# AVTO Kassa - releases

Installer downloads and the update manifest for AVTO Kassa, an offline cashier and
receipt printer for an auto-service workshop.

**There is no source code in this repository.** It exists so a shop's till can download
an update without needing a token - a token shipped inside the .exe would be a token
handed to anyone who opens the file.

- `latest.json` - the manifest the app polls: version, download URL, SHA-256.
- Releases - the `AvtoKassaSetup.exe` for each version.

Both are published automatically by CI when a tag is pushed to the source repository.
