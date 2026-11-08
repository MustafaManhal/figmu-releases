# Figmu releases

Desktop installers for Figmu and the signed manifests the app uses for automatic updates.
This repository holds no source code.

- Download: https://mustafamanhal.github.io/figmu-releases/ or the latest release on this page.
- Update manifests: `stable/<platform>/latest.json` and `beta/<platform>/latest.json`, signed with Ed25519.
  The app checks the signature, size and SHA-512 before it installs anything.
