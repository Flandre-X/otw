# overthewire

A command line convenience utility for [OverTheWire](https://overthewire.org).

## Installation

```bash
sudo apt install ssh sshpass
git clone https://github.com/Flandre-X/otw.git
```

### Optional

```bash
sudo apt install xclip xdg-utils
```

## Usage

**Warning:** otw will store passwords within the current working directory. Make sure you always run it in the same directory, or else unexpected results will ensue!

```bash
./otw <game> <level>
```

For example,

```bash
./otw bandit 3
```

To see more options, run `./otw --help`.

## Introduction

This utility saves manual typing and copy-pasting by:

1. Managing level passwords automatically
2. Generating ssh commands

Dependencies: ssh, sshpass
Optional Dependencies: git, xclip, xdg-open