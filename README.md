# Mogents AI

Native macOS chat workspace for persistent tmux agents, with an integrated local host helper.

## Install

Requires macOS 14(Sonoma) or later. The app includes Apple Silicon and Intel code.

```sh
brew install --cask xiaolai/tap/mogents-ai
```

Open **mogents-ai**, then choose **Use This Mac** to enable authenticated access to this computer’s tmux sessions. The cask installs tmux and exposes the bundled helper as the `mogents-ai` command.

Use **Quit mogents-ai…** in the tray menu and confirm before upgrading or uninstalling. Command-Q is consumed. Confirmed tray Quit stops the verified local helper; tmux sessions and remote helpers remain independent.

[Download the latest release](https://github.com/xiaolai/mogents-ai/releases/latest). macOS app downloads are Developer ID signed, notarized and stapled. The standalone host and helper archives are optional alternatives to the combined client.

This repository distributes release artifacts. Release notes describe changes, build provenance, checksums and the scope of platform validation. This is development software.
