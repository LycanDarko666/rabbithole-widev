# Rabbithole WiDev
## About
*Test environment for testing widgets and interface design in Awesome WM and Rabbithole WM in an virtual container.*

## Requires
- [nix](https://nixos.org/download/) Install from their website and folllow their instructions. Repo versions have been known not to work.
- [Awesome WM](https://awesomewm.org/download/) - Install from [website](https://awesomewm.org/download/), git [stable](https://github.com/awesomeWM/awesome#installing-current-git-master-as-a-package-receipts), or latest stable version from your package manager

## How to Use Rabbithole WiDev
1. `git clone https://github.com/LycanDarko666/rabbithole-widev`
2. Put your widgets inside the `rabbithole-widev` folder (soon will be replaced by a directory selector)
3. `cd rabbithole-widev`
4. Run `nix-shell` inside rabbithole-widev project directory
5. Run `start` inside the nix-shell. A Xephyr window should appear with the development environment inside of it

## Todo
- [ ] Replace xephyr with docker
- [ ] Integrate x11
- [ ] OpenVNC
- [ ] kasm
