# httpyd

## Requirements

- Python 3.6 or higher
- [netifaces](https://pypi.org/project/netifaces/)

## Preparation

```console
$ git clone https://github.com/y-sira/httpyd.git
$ cd httpyd
$ python3 -m venv venv
$ source venv/bin/activate
$ pip install netifaces
$ deactivate
```

Before using this script, please activate the virtual environment by:

```console
$ source venv/bin/activate
```

Please deactivate the virtual environment after using this script by:

```console
$ deactivate
```

## Usage

```
usage: httpyd [-h] [--port PORT] interface

HTTPy server daemon

positional arguments:
  interface    interface name

optional arguments:
  -h, --help   show this help message and exit
  --port PORT  port number (default: 80)
```
