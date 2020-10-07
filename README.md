# ColabCode

[![license](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)
[![PyPI version](https://badge.fury.io/py/colabcode.svg)](https://badge.fury.io/py/colabcode)
![python version](https://img.shields.io/badge/python-3.6%2C3.7%2C3.8-blue?logo=python)


## Installation

Installation is easy!

```
$ pip install git+https://github.com/uplara/colabcode.git
```

Run code server on Google Colab or Kaggle Notebooks

## Getting Started


ColabCode also has a command-line script. So you can just run `colabcode` from command line.

`colabcode -h` will give the following:

```
usage: colabcode [-h] --port PORT [--password PASSWORD] [--mount_drive]

ColabCode: Run VS Code On Colab / Kaggle Notebooks

required arguments:
  --port PORT          the port you want to run code-server on

optional arguments:
  --password PASSWORD  password to protect your code-server from unauthorized access
  --mount_drive        if you use --mount_drive, your google drive will be mounted
```

Else, you can do the following:


```shell

# import colabcode
$ from colabcode import ColabCode

# run colabcode with by deafult options.
$ ColabCode()

# ColabCode has the following arguments:
# - port: the port you want to run code-server on, default 10000
# - password: password to protect your code server from being accessed by someone else. Note that there is no password by default!
# - mount_drive: True or False to mount your Google Drive

# Available Ports
5000 - 5000.colabcode.uplara.com
5001 - 5001.colabcode.uplara.com
5002 - 5002.colabcode.uplara.com
5003 - 5003.colabcode.uplara.com
5004 - 5004.colabcode.uplara.com
5005 - 5005.colabcode.uplara.com

$ ColabCode(port=500X, password="password", mount_drive=True)
```
## How to use it?
Colab starter notebook: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/abhishekkrthakur/colabcode/blob/master/colab_starter.ipynb)

`ColabCode` comes pre-installed with some VS Code extensions.

##### See an example in youtube video     [![YouTube Video](https://img.shields.io/youtube/views/7kTbM3D02jU?style=social)](https://youtu.be/7kTbM3D02jU)

## License

[MIT](LICENSE)
