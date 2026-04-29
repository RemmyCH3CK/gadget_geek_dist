# gadget_geek_dist

Public distribution artifacts for [GadgetGeek](https://github.com/RemmyCH3CK/gadget_geek) — a personal macOS productivity menu-bar app.

This repo holds:
- `appcast.xml` — Sparkle 2 update feed, served via GitHub Pages at <https://remmych3ck.github.io/gadget_geek_dist/appcast.xml>
- DMG releases under [Releases](https://github.com/RemmyCH3CK/gadget_geek_dist/releases)

DMGs are EdDSA-signed by the maintainer's local Sparkle key; the matching public key is embedded in the GadgetGeek app bundle as `SUPublicEDKey`. Sparkle refuses any update with a missing or non-matching signature.

The source repo lives separately and is private.
