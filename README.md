# Skibiditop

Skibiditop is a custom Discord desktop app

**Main features**:
- Vencord preinstalled
- Much more lightweight and faster than the official Discord app
- Linux Screenshare with sound & Wayland
- Much better privacy, since Discord has no access to your system

## Installing

Download the latest version of Skibiditop for your platform from the link below:

- [Download Latest Skibiditop Release](https://github.com/PaperTobi/Skibiditop/releases/latest)

## Building from Source

Packaging will create builds in the dist/ folder.

```sh
git clone https://github.com/PaperTobi/Skibiditop
cd Skibiditop

# Install Dependencies
pnpm i

# Either run it without packaging
pnpm start

# Or package
pnpm package
# Or only build the pacman target
pnpm package --linux pacman
# Or package to a directory only
pnpm package:dir

