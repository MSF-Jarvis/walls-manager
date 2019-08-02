# walls-manager [![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/python/black)

## DEPRECATED

The sync script is feature-complete and the bot part has been replaced by [walls-bot](https://github.com/msfjarvis/walls-bot).

Tooling used to maintain my public collection of desktop walls

## Usage

- Create a `config.ini` files based on the sample provided in this repository
- Run `manager.py` with the needed arguments

```
$ ./manager.py -h
usage: manager.py [-h] [-d] [-m] [-s SYNC]

optional arguments:
  -h, --help            show this help message and exit
  -d, --details         List statistics of local directory
  -m, --markdown        Output file names as Markdown links
  -s SYNC, --sync SYNC  Set direction of sync, local for pull and remote for
                        push
```
