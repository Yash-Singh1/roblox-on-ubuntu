<!-- markdownlint-disable MD026 -->

# Roblox is Finally on Ubuntu!

> On June 11, 2021, a user by the name of ImSlappy826 (Slappy826#0001 on Discord) created a one-line patch for Wine that allowed the Roblox Player to work again on a GNU/Linux or BSD system.

This patch was released in the development release of Wine 6.11. Here are the steps on installing it on Ubuntu:

```sh
# GrapeJuice Dependencies (https://gitlab.com/brinkervii/grapejuice)
sudo apt install -y wine wine64 wine32 git python3-pip python3-setuptools python3-wheel python3-dev pkg-config libcairo2-dev libdbus-1-dev gtk-update-icon-cache desktop-file-utils xdg-utils libgirepository1.0-dev gir1.2-gtk-3.0
sudo apt install -y --install-recommends winehq-devel # Install the 6.11 development branch

# Installing GrapeJuice
git clone https://gitlab.com/brinkervii/grapejuice.git
cd grapejuice
python3 ./install.py
```

And you are done!

## References

Here are some references for troubleshooting:

- [GrapeJuice Installation instructions](https://gitlab.com/brinkervii/grapejuice/-/wikis/Installing-from-source/Debian-10-and-similar)
- [Roblox on Linux Wiki Page](https://roblox.fandom.com/wiki/Roblox_on_Linux)
- [GrapeJuice Discord](https://discord.gg/mRTzEb6)
