# DeepVibe Homebrew tap

Homebrew formulae for [DeepVibe](https://github.com/deepvibe-eu/DeepVibe), the
(unofficial) DeepSeek coding partner IDE.

## Install

```sh
brew tap deepvibe-eu/tap
# newer Homebrew requires trusting third-party taps before loading a formula:
brew trust --formula deepvibe-eu/tap/deepvibe
brew install deepvibe
```

One formula serves both platforms from the GitHub releases:

- **macOS** — arm64 `.zip` (Apple Silicon). Apple Silicon only for now.
- **Linux** — x86_64 AppImage.

> The macOS build is currently unsigned/unnotarized, so Gatekeeper will
> quarantine it. Right-click → **Open** once, or sign/notarize the release.

## Other install methods

- AppImage / `.deb` / `.pkg.tar.zst` / `.tar.gz`: see the
  [releases](https://github.com/deepvibe-eu/DeepVibe/releases).
- AUR (`deepvibe-bin`): pending — AUR registration is currently closed.
- Snap (`deepvibe`, classic): pending Canonical review.
