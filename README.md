# VPN Auto Reconnect

macOS menu bar app that automatically reconnects your VPNs when your Mac wakes up from sleep.

- Reconnects the VPNs you select after every wake, one after the other, with retries
- Works with the VPNs configured in System Settings: IKEv2, L2TP/IPSec, Cisco IPSec
- Menu bar icon shows the state at a glance: a shield with a lock (all selected VPNs connected), an exclamation mark (some disconnected) or a cross (all disconnected)
- Optional continuous monitoring: reconnects a VPN that drops while the Mac is awake
- Connect all / disconnect all from the menu
- Launch at login
- No Dock icon, nothing to configure besides ticking your VPNs

The interface is in French.

## Install

With [Homebrew](https://brew.sh):

```sh
brew tap cbrassel/tap
brew trust cbrassel/tap   # Homebrew 7 and later
brew install --cask vpnautoreconnect
```

Or download the latest `VPNAutoReconnect-x.y.zip` from [Releases](../../releases), unzip it and move **VPNAutoReconnect** into **Applications**.

The app is signed with a Developer ID and notarized by Apple.

## Requirements

- macOS 14 or later
- At least one VPN configured in **System Settings › VPN**

## Feedback

Please open an [issue](../../issues).
