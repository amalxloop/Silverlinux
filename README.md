# SilverLinux OS

```
▄█████ ▄▄ ▄▄   ▄▄ ▄▄ ▄▄▄▄▄ ▄▄▄▄  ██     ▄▄ ▄▄  ▄▄ ▄▄ ▄▄ ▄▄ ▄▄ 
▀▀▀▄▄▄ ██ ██   ██▄██ ██▄▄  ██▄█▄ ██     ██ ███▄██ ██ ██ ▀█▄█▀ 
█████▀ ██ ██▄▄▄ ▀█▀  ██▄▄▄ ██ ██ ██████ ██ ██ ▀██ ▀███▀ ██ ██ 
```

A security-focused Linux distribution based on Debian Bookworm with KDE Plasma desktop and 350+ pre-installed security tools.

## Features

- **Security Tools**: Pre-installed with 350+ security tools including:
  - Network scanning (nmap, netcat, socat)
  - Wireless auditing (aircrack-ng, reaver, bully, hashcat)
  - Forensics (binwalk, foremost, volatility3, radare2, ghidra)
  - Password cracking (hashcat, john)
  - Web testing (nikto, dirb, gobuster, wfuzz, sqlmap)
  - Exploitation (Metasploit, searchsploit)
  - Privacy (tor, macchanger, cryptsetup)

- **Desktop Environment**: KDE Plasma
- **Base**: Debian Bookworm
- **Live ISO**: Bootable with persistence support

## Installation

### Quick Install on Existing Debian/Parrot

```bash
curl -fsSL https://raw.githubusercontent.com/amalxloop/silverlinux/main/install-silverlinux.sh | sudo bash
```

### Build ISO from Scratch

```bash
# Install dependencies
sudo apt-get update
sudo apt-get install -y live-build debootstrap squashfs-tools xorriso grub-efi-amd64

# Build
cd silverlinux-debian
sudo ./build-complete.sh
```

## Usage

- Run `neowofetch` to see system info
- Run `hollywood` for terminal hacker aesthetics

## System Requirements

- 4GB+ RAM recommended
- 25GB+ free disk space for ISO build
- 64-bit processor

## Default Credentials

- **User**: silver
- **Password**: silver

## License

MIT License

## Author

SilverLinux Team