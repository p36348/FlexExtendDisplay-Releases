# Flex Extend Display releases

This repository hosts public macOS release artifacts and the Sparkle appcast
for Flex Extend Display. The application source code is maintained separately
in a private repository.

## Public endpoints

- Appcast: <https://p36348.github.io/FlexExtendDisplay-Releases/appcast.xml>
- Downloads: <https://github.com/p36348/FlexExtendDisplay-Releases/releases>

`appcast.xml` is generated and signed with Sparkle's `generate_appcast` tool.
Do not edit it manually. Sparkle private keys and Apple signing credentials
must never be committed here.

## GitHub Pages

Configure **Settings → Pages → Deploy from a branch**, select `main` and `/`
so the appcast URL above is publicly available over HTTPS.
