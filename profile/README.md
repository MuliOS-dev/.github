# MuliOS
[![UPDATE](https://img.shields.io/badge/UPDATE-50C878?style=flat&logo=github&logoColor=white)](https://github.com/MuliOS-dev/update)
[![Arch Linux](https://img.shields.io/badge/Arch%20Linux%20Builds-1793D1?style=flat&logo=archlinux&logoColor=white)](https://github.com/MuliOS-dev/MuliOS-Arch)
[![Ubuntu](https://img.shields.io/badge/Ubuntu%20Builds-E95420?style=flat&logo=ubuntu&logoColor=white)](https://github.com/MuliOS-dev/MuliOS-Ubuntu)
[![GitHub Organization](https://img.shields.io/badge/GitHub-MuliOS-181717?style=flat\&logo=github\&logoColor=white)](https://github.com/MuliOS-dev)
[![Support](https://img.shields.io/badge/Support-5865F2?style=flat&logo=discord&logoColor=white)](https://discord.gg/3FzUdGbWMf)

### Linux distribution built around choice, performance, and personalization.

MuliOS is an independent Linux distribution project focused on creating a flexible operating system that adapts to what you actually use your computer for.

MuliOS has been made with the idea to have an operating system be all you need in one place. people change, your OS too.

---

## What is MuliOS?

MuliOS is built around one simple idea:

> **Your operating system should adapt to you — not the other way around.**

MuliOS uses configurable profiles to provide different environments depending on how you use your computer.
Profiles work by modifying the kernel for various uses, and installing useful programs for that particular need. it also adapts and optimises the system for said use.

### Profiles

* **Game Focused** — Gaming-focused packages and optimizations
* **Code** — Development tools and programming environments
* **AI** — Tools for AI and machine-learning workloads
* **Study** — Tools for studying and everyday school work
* **Privacy** — Privacy-focused configuration
* **Casual** — A balanced everyday setup
* **More** — Additional and custom configurations

---

## Projects

The MuliOS organisation contains the components that make up the operating system.

| Project                  | Description                                      |
| ------------------------ | ------------------------------------------------ |
| **MuliOS-Ubuntu**        | Ubuntu-Based MuliOS Operating System             |
| **MuliOS-Arch**          | Arch Linux-based MuliOS Operating System         |
| **MuliOS Installer**     | Graphical installation and setup system          |
| **MuliOS Profiles**      | Profile-specific configurations and packages     |
| **MuliOS Packages**      | Packages and system components                   |
| **MuliOS Tools**         | Utilities used throughout the project            |
| **MuliOS Documentation** | Documentation, guides and technical information  |
| **MUpdate & OTA**        | Custom Update Manager and OTA Services           |

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

MuliOS uses a combination of open-source projects, including:

* Linux
* Arch Linux
* XUbuntu
* Python
* PySide6
* systemd
* Calamares
* Bash
* Git
* GitHub
* 7-zip
And more!

The underlying projects may evolve as the project develops.

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

## Updates & OTA

MuliOS is designed with an update system for managing system components, configurations and packages.
MuliOS will use **OTA Services** or MOTA (MuliOS Over The Air) To update main components of the operating system (E.g: UI, MUpdate, generic kernel, Arch Version...) using Split Packages and 7zip to deliver system updates.
Profile Updates will work using MUpdate, which will gather latest profile packages from GitHub (or mirrors later on) and keep the generic kernel as a fall back option.

We strongly recommend backing up all personal data alongside the built-in backup option using external drives and cloud services if needed.

The update infrastructure is actively being developed and upgraded to be better and more stable. for more reliability, it is possible to manually update the OS using the steps in our <a href="https://github.com/MuliOS-dev/update" target="_blank">
  <button>update</button>
</a> repository.

---

## Development Status

> **MuliOS Arch is currently under active development.**
> **MuliOS Ubuntu is currently paused.**

 
Some components may change significantly between releases.

Current development areas include:

* Core operating system
* Installer
* Profile systemzzz
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
Currently, MuliOS uses the GPL-3.0 License.

Check the `LICENSE` file of each repository for the applicable license.

---

<div align="center">

## MuliOS

**People change, your OS too.**

`Build • Customize • Experiment • Use`

</div>
