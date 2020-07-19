# wal_g810

Automate [g810-led](https://github.com/MatMoul/g810-led) theme creation from generated [pywal](https://github.com/dylanaraps/pywal) colors

## About

`wal_g810` is a small Python utility meant to work with `wal` by reading colors generated from a JSON file and translating them into a `g810-led` compliant profile file.

## Installation

Install and update using [pip](https://pip.pypa.io/en/stable/quickstart/):  

```bash
pip install wal-g810
```

### Requirements

* [python3](https://www.python.org/)

    Tested with Python 3.8.3. Uses standard sys calls so should function across all Python 3.

* [pywal](https://github.com/dylanaraps/pywal)

* [g810-led](https://github.com/MatMoul/g810-led)

## Usage

**Be sure you've run `wal` at least once to generate colors.json file.**

Simply invoke `wal-g810`  
The generated profile can then be applied by invoking `g810-led -p $HOME/.cache/wal/colors-wal-g810`
