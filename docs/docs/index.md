# ten

**ten** is a Python library for web exploit development. It provides a set of tools to make your life easier when writing code to test the security of web applications. The GitHub repository is available [here](https://github.com/cfreal/ten).

## Installation

Ten is available on [PyPi](https://pypi.org/project/ten/).

```bash
$ pip install ten
```

## Quick start

Create a template and make the script executable:

```shell
$ ten script.py
```

This opens a template script with your favorite editor:

```python
from ten import *


@entry
def main():
    ...


main()
```

## Documentation

Refer to [the python documentation](../tenlib/index.html) for precise description of all the available classes and methods. Check the menu on the left for quick descriptions of the most used modules, and tutorials. 
