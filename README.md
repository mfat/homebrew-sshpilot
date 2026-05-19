# homebrew-sshpilot

Homebrew tap for [SSH Pilot](https://github.com/mfat/sshpilot) — a GTK4 / libadwaita SSH connection manager and terminal. (

## Install

```
brew tap mfat/sshpilot
brew install sshpilot
```
## Run

On macOS, you can run SSH Pilot by typing these commands depending on your architecture:

For Apple Silicon:

```
/opt/homebrew/bin/sshpilot
```

For Intel macs:

```
/usr/local/bin/sshpilot
```

On Linux:
```
sshpilot
```

Works on macOS Homebrew and Linuxbrew. The formula is build-from-source; first install pulls the GTK4 stack (gtk4, libadwaita, vte3, gtksourceview5, py3cairo, pygobject3, sshpass, etc.) and a Python virtualenv carrying paramiko / cryptography / keyring / psutil.

## Requirements
[Homebrew](https://brew.sh/)

SSH Pilot is a GUI application. After install, launch from a terminal inside an active desktop session:

- **macOS** — works out of the box with the native GTK4 backend (no XQuartz needed).
- **Linux (Linuxbrew)** — needs a host display server (Wayland or X11) and a dbus session.

## License

The formula in this tap inherits SSH Pilot's license: [GPL-3.0-only](https://github.com/mfat/sshpilot/blob/main/LICENSE).
