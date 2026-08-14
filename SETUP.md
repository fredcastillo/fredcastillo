# Setup Guide — Fred Castillo GitHub Profile

This repository is designed to become the GitHub profile repository for:

`github.com/fredcastillo`

## 1. Create the special profile repository

Create a public repository named exactly:

`fredcastillo`

GitHub recognizes a repository with the same name as the username as a profile repository.

## 2. Upload these files

Copy the complete contents of this ZIP into the root of the new repository.

Recommended structure:

```text
fredcastillo/
├── README.md
├── assets/
│   ├── banner.gif
│   ├── terminal.gif
│   ├── security-lifecycle.gif
│   ├── technical-stack.svg
│   ├── operator-telemetry.svg
│   ├── contribution-stream.svg
│   └── logo.svg
└── scripts/
    └── generate_assets.py
```

## 3. Keep the profile visuals local

The technical stack, security focus map and contribution stream are self-contained SVG files in `assets/`.

They do not require a personal access token, a GitHub Actions workflow, an `output` branch or an external statistics service. Keep the filenames unchanged and test the README after replacing any asset.

## 4. Pin the strongest repositories

Recommended pinned repositories:

1. `windows-server-2025-security-lab`
2. `cybersecurity-labs`
3. `Digispark-HID-Attack-Defense-PoC`
4. `networking-labs`

Use the remaining pin slots only for projects that add a different signal such as cloud, automation, SIEM or Active Directory security.

## 5. Profile bio suggestion

Use a short GitHub bio. Example:

`Cybersecurity Student | ISC2 CC | Networking & Infrastructure | Windows/Linux | Security Engineering → Offensive Security`

Do not turn the short bio into a certification list.

## 6. Before publishing

Verify:
- certification names;
- repository URLs;
- LinkedIn URL;
- YouTube URL;
- English level;
- any technologies that may still be learning-only.

## Notes

The profile intentionally separates demonstrated work from areas of future growth so the page remains technically credible.
