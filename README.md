# My dotfiles
My dotfiles managed with [GNU stow](https://www.gnu.org/software/stow/)

### Apply dotfiles
1. Install [GNU stow](https://www.gnu.org/software/stow/)
2. Clone this repository into your home directory
3. Cd into the repository and run either
    * `stow <package1> <package2> ...` to apply specific packages
    * `sh ./stow_all.sh` to apply all packages
### Unstow dotfiles
* `stow --delete <package1> <package2> ...` to unstow specific packages
* `sh ./unstow_all.sh` to unstow all packages
