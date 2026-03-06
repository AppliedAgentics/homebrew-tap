# AppliedAgentics Homebrew Tap

Homebrew tap for AppliedAgentics desktop applications.

## Install Agent Flows Bridge

```bash
brew tap AppliedAgentics/tap
brew install --cask agent-flows-bridge
```

Use the install command only for the first install on a machine.

## Upgrade

```bash
brew update
brew upgrade --cask agent-flows-bridge
```

Use the upgrade command whenever `agent-flows-bridge` is already installed and you want the newest published release.

## Verify Installed Version

```bash
brew info --cask agent-flows-bridge
defaults read "/Applications/Agent Flows Bridge.app/Contents/Info" CFBundleShortVersionString
```

## Uninstall

```bash
brew uninstall --cask agent-flows-bridge
brew untap AppliedAgentics/tap
```
