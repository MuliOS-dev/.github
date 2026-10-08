# MuliOS

[![UPDATE](https://img.shields.io/badge/UPDATE-50C878?style=flat\&logo=github\&logoColor=white)](https://github.com/MuliOS-dev/update)
[![Arch Linux](https://img.shields.io/badge/Arch%20Linux-Builds-1793D1?style=flat\&logo=archlinux\&logoColor=white)](https://github.com/MuliOS-dev/MuliOS-Arch)
[![Ubuntu](https://img.shields.io/badge/Ubuntu%20Builds-E95420?style=flat\&logo=ubuntu\&logoColor=white)](https://github.com/MuliOS-dev/MuliOS-Ubuntu)
[![GitHub Organization](https://img.shields.io/badge/GitHub-MuliOS-181717?style=flat\&logo=github\&logoColor=white)](https://github.com/MuliOS-dev)
[![Support](https://img.shields.io/badge/Support-5865F2?style=flat\&logo=discord\&logoColor=white)](https://discord.gg/3FzUdGbWMf)

### A Linux distribution built around choice, performance, and personalization.

MuliOS is an independent Linux distribution project focused on creating an operating system that adapts to how you use your computer.

MuliOS is built around a simple idea:

> **People change, your OS too.**

---

## What is MuliOS?

MuliOS is designed around **choice, performance, customization, simplicity, and modularity**.

The system provides different profiles that can adapt system configuration, packages, tools, and performance settings to different workloads.

### Profiles

* **Game Focused** — Gaming-focused software and optimizations
* **Code** — Development tools and programming environments
* **AI** — Tools for AI and machine-learning workloads
* **Study** — Tools for studying and everyday school work
* **Privacy** — Privacy-focused configuration
* **Casual** — A balanced everyday setup
* **More** — Additional profiles and configurations as the project evolves

Profiles are designed to remain broad and practical rather than creating a separate operating system for every use case.

---

## Projects

The MuliOS organization contains the components that make up the project.

| Project              | Description                                   |
| -------------------- | --------------------------------------------- |
| **MuliOS-Arch**      | Arch Linux-based MuliOS distribution          |
| **MuliOS-Ubuntu**    | Ubuntu-based MuliOS project                   |
| **MuliOS Installer** | Graphical installer and system setup          |
| **MuliOS Profiles**  | Profile-specific configurations and packages  |
| **MuliOS Tools**     | Utilities used throughout MuliOS              |
| **MUpdate**          | MuliOS system update and synchronization tool |
| **Documentation**    | Documentation and technical information       |

---

## Architecture

MuliOS is designed to keep the operating system modular and configurable.

```text
                         MuliOS
                           |
              +------------+------------+
              |                         |
        System Components          User Environment
              |                         |
       +------+------+------+      +----+----+
       |      |      |      |      |         |
    Kernel Packages Config Tools Profiles    UI
                                    |
              +---------------------+---------------------+
              |          |          |          |          |
           Gaming      Code        AI       Study      Privacy
                                                   |
                                                 Casual
```

The goal is to keep components independent wherever possible, making MuliOS easier to maintain, modify, and expand.

---

## Technology

The current MuliOS ecosystem uses open-source technologies including:

* Linux
* Arch Linux
* Python
* PySide6
* systemd
* Bash
* Git
* GitHub
* Archiso
* KDE Plasma
* PipeWire
* NetworkManager

MuliOS also includes custom components such as the MuliOS installer, MUpdate, system utilities, desktop configuration, and profile infrastructure.

The technology stack may evolve as development continues.

---

## Installation

MuliOS is distributed as bootable installation media.

```text
Download MuliOS
      |
Create bootable USB
      |
Boot the computer
      |
Launch the MuliOS installer
      |
Choose your configuration
      |
Install MuliOS
      |
Configure your system
```

For current installation instructions and releases, see the **MuliOS-Arch** repository.

---

## Updates

MuliOS uses **MUpdate** to synchronize supported MuliOS system components with the official MuliOS repository.

MUpdate provides features including:

* System file synchronization
* GitHub blob verification
* Automatic backups of replaced files
* Safe update handling
* Force update mode
* Dry-run support
* Self-updating
* MuliOS desktop/theme synchronization

MUpdate currently focuses on the Arch-based MuliOS system.

For more information, see the [MUpdate repository](https://github.com/MuliOS-dev/update).

> Always maintain a backup of important personal data before performing major system changes or updates.

---

## Development Status

### MuliOS Arch

**Active development**

The Arch edition is currently the primary actively developed MuliOS distribution.

### MuliOS Ubuntu

**Paused**

The Ubuntu edition remains part of the project but is not currently the primary development target.

MuliOS is continuously evolving, and components may change significantly between releases.

Current development areas include:

* Core operating system
* Installer
* Profile system
* Package configuration
* MUpdate
* Desktop integration
* System configuration
* Boot and UEFI reliability
* Documentation
* ISO build infrastructure

---

## Contributing

Contributions are welcome.

You can contribute by:

* Reporting bugs
* Suggesting features
* Contributing code
* Improving packages and configurations
* Improving documentation
* Testing development builds
* Improving the user interface
* Helping test hardware compatibility

Before contributing, check the contribution guidelines of the relevant repository.

---

## Philosophy

### Choice

Users should be able to decide how their system is configured.

### Performance

The system should avoid unnecessary overhead and provide the resources applications actually need.

### Simplicity

Complexity should stay behind the scenes whenever possible.

### Modularity

Components should be replaceable and independently maintainable.

### Openness

MuliOS is built around open-source software and transparent development.

---

## Organisation

MuliOS is developed under the [MuliOS GitHub organization](https://github.com/MuliOS-dev).

Explore the repositories to learn more about the operating system, contribute to development, or experiment with the latest builds.

---

## Project Status

| Component           | Status             |
| ------------------- | ------------------ |
| Core OS             | Active development |
| Arch-based edition  | Active development |
| Installer           | Active development |
| Profiles            | Active development |
| MUpdate             | Active development |
| Desktop integration | Active development |
| ISO build system    | Active development |
| Documentation       | Active development |
| Ubuntu edition      | Paused             |

---

## License

MuliOS uses the **GNU General Public License v3.0 (GPL-3.0)**.

Individual repositories may contain additional licensing information for bundled or third-party components.

See the `LICENSE` file of the relevant repository for the applicable license.

---

<div align="center">

## MuliOS

**People change, your OS too.**

`Build • Customize • Experiment • Use`

</div>
