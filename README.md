

# debian-iso-builder-engine-develop




## Home

| Link | GitHub |
| ---- | ------ |
| [debian-iso-builder-engine-develop](https://samwhelp.github.io/debian-iso-builder-engine-develop/) | [GitHub](https://github.com/samwhelp/debian-iso-builder-engine-develop) |
| [debian-iso-builder-template](https://samwhelp.github.io/debian-iso-builder-template/) | [GitHub](https://github.com/samwhelp/debian-iso-builder-template) |




## Subject

* [Docker](#docker)
* [Vanilla Linux](#vanilla-linux)
* [Link](#link)




## Docker

| Docker Image |
| ------------ |
| [distro-iso-builder-docker-image](https://github.com/samwhelp/distro-iso-builder-docker-image) |
| [debian-docker-image](https://github.com/samwhelp/debian-docker-image) |




## Vanilla Linux

This repository can also be used to build the **Vanilla Linux XFCE live ISO**.

Vanilla Linux is a lightweight Debian-based distribution focused on keeping the base system clean while providing a useful toolbox for developers and normal desktop users.

### Vanilla Linux Build

The current XFCE ISO configuration follows the identity and design of the main [Vanilla Linux](https://github.com/carjam120443-netizen/vanilla-linux) project, including:

- 🍦 Vanilla Linux branding
- 🖥️ XFCE desktop environment
- 📦 Debian Stable/Trixie base with APT and DPKG
- 🔧 Calamares graphical installer
- 🔐 Installer launched with `pkexec` for administrative privileges
- 🎨 Vanilla Linux wallpaper and XFCE desktop configuration
- ⚙️ Automated GitHub Actions ISO builds on every push
- 💿 `vanilla-linux-xfce-amd64.iso` build artifact

The Vanilla Linux project is the source of the distro's branding, artwork, and overall project identity:

**Vanilla Linux:** https://github.com/carjam120443-netizen/vanilla-linux

### Build Workflow

The ISO is automatically built by:

`.github/workflows/build-debian-xfce.yml`

You can also start a build manually from the GitHub Actions tab with **Run workflow**.




## Link

| Link | GitHub |
| ---- | ------ |
| [note-about-debian-iso-builder](https://samwhelp.github.io/note-about-debian-iso-builder/) | [GitHub](https://github.com/samwhelp/note-about-debian-iso-builder) |




## Samwhelp

* [GitHub](https://github.com/samwhelp)
