# automation-scripts

This repository contains a collection of Python automation scripts packaged as a Python package.

## Installation

To install the package locally, clone the repository and install it in editable mode:

```bash
git clone https://github.com/dl0278/automation-scripts.git
cd automation-scripts
pip install -e .
```

## Usage

After installation, you can run the Hello World script:

```bash
python -m automation.hello
```

This will print:

```
Hello, World!
```

You can also import functions from the `automation` package in your own scripts:

```python
from automation.hello import hello_world

hello_world()
```
