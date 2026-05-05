Hacky script for quick science fetching.

<p align="center">
<img src="https://raw.githubusercontent.com/dougy147/scitopdf/master/assets/example.gif" width="80%" />
</p>

`scitopdf` processes anything about a paper: DOI, URL, title, authors, journal...
leveraging Crossref, Sci-Hub and Libgen.

## Quick start

```console
$ wget https://raw.githubusercontent.com/dougy147/scitopdf/master/scitopdf
$ chmod +x ./scitopdf
$ ./scitopdf "paper you are looking for"
```

## Overviw

| Flag                       | Functionality                                                 |
|----------------------------|---------------------------------------------------------------|
| `-l`, `--list`             | Download references line by line from a bibliography file     |
| `-D`, `--download-dir`     | Store papers in a specified directory                         |
| `-u`, `--url`              | Provide Sci-Hub URL manually                                  |
| `-p`, `--no-auto-open`     | Turn auto-opening off                                         |
| `-q`, `--quiet`            | Quiet mode, no `echo` except for errors                       |
| `--ref`                    | Display BibTex references in terminal and copy to clipboard.  |
| `--dmenu`                  | Display prompt with dmenu (more support and functions to come)|
| `-w`, `--wait`             | Wait X seconds between two requests (for `--list` mode only)  |
| `-b`, `--break-after`      | Make a break every X paper search (for `--list` mode only)    |
| `-d`, `--break-for`        | Break duration in seconds (for `--list` mode only)            |
| `-h`, `--help`             | Print this help menu                                          |
| `man scitopdf`             | Check the manual for more tweaks                              |

- **Example** : `scitopdf -p "protein measurement with the folin" -q -D "$HOME/science"`

## Install

### From source

```console
$ git clone https://github.com/dougy147/scitopdf
$ cd scitopdf
$ sudo make install
```
### Linux

```console
$ yay -S scitopdf-git       # ArchLinux
$ sudo dnf install scitopdf # ROSA Linux
```

## DISCLAIMER

> bla bla bla don't hurt anyone with this tool, including yourself 3;)

## Special thanks to contributors

<a href="https://github.com/Phundrak">
  <img src="https://avatars.githubusercontent.com/u/1893080?v=4" width='50px'>
</a>
<a href="https://github.com/mikhailnov">
  <img src="https://avatars.githubusercontent.com/u/15802528?v=4" width='50px'>
</a>


## Feel free 😎

If scitopdf has been of any help to you, I'd be glad and thankful !

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/dougy147)

BTC : `bc1q4cflj0e3hwcn5edut654je86upn37p37gut5yk`
