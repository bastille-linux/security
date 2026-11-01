# bastille-security

C security subsystems for Bastille OS.

| Tool | Purpose |
|---|---|
| `bastille-duress/` | PAM duress module — fake PIN (decoy session) + real PIN (key destruction) |
| `bastille-keyguard/` | LUKS RAM-half key guard + BFU eviction |
| `bastille-usb/` | USB inspector daemon + PIN gate dialog |
| `bastille-firmware/` | ME neutralisation + firmware audit |
| `bastille-persist/` | Encrypted persistence setup |
| `bastille-profile/` | Encrypted profile manager |
| `bastille-vision/` | Focus-loss screen lock daemon |
| `gpggrid/` | Keyboard-logger-defeating GPG passphrase entry |
| `bastille-dsm-config/` | setuid DSM configuration helper |

These tools are compiled into the ISO during the live-build chroot phase.
See `bastille-linux/bastille` for the full build system.
