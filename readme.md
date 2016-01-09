# Scripts

A collection of scripts I wrote for various tasks.

## Install

add the following to `.bashrc`

```bash
export PATH=$PATH:absolute/path/to/bin
export MANPATH=$MANPATH:absolute/path/to/man
```

## License

GPL v3 - https://www.gnu.org/licenses/gpl-3.0.en.html

## List of Scripts

### install-font

A simple script to install fonts from files and remote github repo.

##### My usual non-standard fonts

```bash
sudo install-font -g :khaledhosny/amiri-font :khaledhosny/aref-ruqaa :dejavu-fonts/dejavu-fonts
```

### progress-bar

Output an indicator for progress like `[==>______]` or `[██▓░░░░░░]`.
