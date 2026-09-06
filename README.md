# MuliOS

[![Arch Linux](https://img.shields.io/badge/Arch%20Linux-1793D1?style=flat\&logo=archlinux\&logoColor=white)](https://archlinux.org/)
[![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat&logo=ubuntu&logoColor=white)](https://ubuntu.com/)
[![GitHub Organization](https://img.shields.io/badge/GitHub-MuliOS-181717?style=flat\&logo=github\&logoColor=white)](https://github.com/MuliOS)

### A Linux distribution built around choice, performance, and simplicity.

MuliOS is an independent Linux distribution project focused on creating a flexible operating system that adapts to what you actually use your computer for.

Whether you're gaming, coding, studying, working with AI, or simply using your PC, MuliOS aims to provide a clean and configurable Linux environment.

---

## What is MuliOS?

MuliOS is built around one simple idea:

> **Your operating system should adapt to you — not the other way around.**

MuliOS uses configurable profiles to provide different environments depending on how you use your computer.

### Profiles

* **Gaming** — Gaming-focused packages and optimizations
* **Coding** — Development tools and programming environments
* **AI** — Tools for AI and machine-learning workloads
* **School** — Tools for studying and everyday school work
* **Privacy** — Privacy-focused configuration
* **Casual** — A balanced everyday setup
* **More** — Additional and custom configurations

---

## Projects

The MuliOS organisation contains the components that make up the operating system.

| Project                  | Description                                      |
| ------------------------ | ------------------------------------------------ |
| **MuliOS**               | Main operating system and user-facing components |
| **MuliOS-Arch**          | Arch Linux-based MuliOS development              |
| **MuliOS Installer**     | Graphical installation and setup system          |
| **MuliOS Profiles**      | Profile-specific configurations and packages     |
| **MuliOS Packages**      | Packages and system components                   |
| **MuliOS Tools**         | Utilities used throughout the project            |
| **MuliOS Documentation** | Documentation, guides and technical information  |

---

## Architecture

MuliOS is designed to be modular and configurable.

```text
                         MuliOS
                           |
              +------------+------------+
              |                         |
       System Components          User Environment
              |                         |
       +------+------+------+      +----+----+
       |      |      |      |      |         |
    Kernel Packages Config Tools Profiles   UI
                                    |
              +---------------------+---------------------+
              |          |          |          |          |
           Gaming     Coding       AI       School    Privacy
                                                   |
                                                 Casual
```

The goal is to keep components independent wherever possible, making MuliOS easier to maintain, modify and expand.

---

## Technology

MuliOS uses a combination of open-source technologies, including:

* Linux
* Arch Linux
* Python
* PySide6
* systemd
* Calamares
* Bash
* Git
* GitHub

The underlying technologies may evolve as the project develops.

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
Launch the installer
      |
Choose your profile
      |
Install MuliOS
      |
Configure your system
```

See the relevant repository for current installation instructions.

---

## Updates

MuliOS is designed with an update system for managing system components, configurations and packages.

The update infrastructure is actively being developed.

---

## Development Status

> **MuliOS is currently under active development.**

Some components may change significantly between releases.

Current development areas include:

* Core operating system
* Installer
* Profile system
* Package management
* Update infrastructure
* System configuration
* Arch-based edition
* Documentation

---

## Contributing

Contributions are welcome.

You can contribute by:

* Reporting bugs
* Suggesting features
* Contributing code
* Creating or improving packages
* Improving documentation
* Testing development builds
* Improving the user interface

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

All MuliOS projects are developed under the MuliOS GitHub organisation.

Explore the repositories to learn more about the operating system, contribute to development, or experiment with the latest builds.

---

## Project Status

| Component          | Status         |
| ------------------ | -------------- |
| Core OS            | In development |
| Installer          | In development |
| Profiles           | In development |
| Package system     | In development |
| Update system      | In development |
| Documentation      | In development |
| Arch-based edition | In development |

---

## License

Individual MuliOS repositories may use different licenses depending on their purpose and included components.

Check the `LICENSE` file of each repository for the applicable license.

---

<div align="center">

## MuliOS

**A Linux distribution made to be yours.**

`Build • Customize • Experiment • Use`

</div>
