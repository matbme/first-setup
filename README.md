<div align="center">
    <h1>Ubuntu Smoother</h1>
    <p>This utility is meant to be used in <a href="https://github.com/mirkobrombin/ubuntu-vanilla-gnome">Ubuntu Vanilla GNOME</a> 
    as a first-setup wizard. It's purpose is to help the user to configure the 
    system to his needs, e.g. by configuring snap, flatpak, flathub, etc.</p>
    <img src="data/screenshot-1.png">
</div>


## Build
### Dependencies
- build-essential
- meson
- libadwaita-1-dev
- gettext
- desktop-file-utils

### Build
```bash
meson build
ninja -C build
```

### Install
```bash
sudo ninja -C build install
```

## Run
```bash
ubuntu-smoother
```