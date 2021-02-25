## Description

This script will automatically build a docker image with Python and JetBrains PyCharm Community installed, allowing you to debug python without Ultimate.

## Usage

```
Usage:

docker-pycharm [OPTIONS] [FOLDER]

options:
    -h,  --help                   : Print usage
    -pv, --python-version version : Specifies base python docker image version (defaults to 3)
    -p,  --publish list           : Passed to docker run to expose ports

folder:
    which folder will be mounted (defaults to current folder if not specified)
```
