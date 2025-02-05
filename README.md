# ByteCore Byte

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/joakimwinum/bytecore-byte/main?labpath=bytecorebyte.ipynb)

ByteCore Byte is a specialized version of the ByteCore CPU that operates within the ByteCore Emulator. It is uniquely designed using the ByteCore Assembly language but uses only 1 byte for addressing instead of 2, thus reducing the available memory from 64KB to 256 bytes.

This compact CPU setup has been adapted to run both the simple and the advanced example programs originally developed for the standard ByteCore CPU.

The programs are integrated into a Jupyter notebook which includes:

- A main Python cell containing the source code for ByteCore Byte.
- Two additional code cells, each containing one of the example programs: Simple and Advanced.

To explore these programs, follow the setup instructions below, launch the Jupyter Lab, open the [`bytecorebyte.ipynb`](bytecorebyte.ipynb) notebook, and click 'Run All'. The notebook includes Python assertions to verify the CPU's state upon halting.

## ByteCore Packages

Here are the packages used to develop the ByteCore Byte CPU:

### ByteCore Emulator

- [GitHub](https://github.com/joakimwinum/bytecore)
- [PyPI](https://pypi.org/project/bytecore/)

### ByteCore Compiler

- [GitHub](https://github.com/joakimwinum/bytecorecompiler)
- [PyPI](https://pypi.org/project/bytecorecompiler/)

## Installation and Setup

### Prerequisites

Before installing, ensure you have Python 3.11 or newer. Clone the repository and navigate to the root directory. It is recommended to set up a Python virtual environment to manage dependencies efficiently.

### Dependencies

Install the necessary dependencies with the following command:

```bash
pip3 install -r requirements.txt
```

### Starting Jupyter Lab

To start Jupyter Lab, run:

```bash
jupyter lab
```

### Codespaces

For a pre-configured development environment, use Codespaces by clicking [here](https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=joakimwinum/bytecore-byte).

### Binder

Alternatively, use Binder for a ready-to-use environment by clicking [here](https://mybinder.org/v2/gh/joakimwinum/bytecore-byte/main?labpath=bytecorebyte.ipynb).

## License

This project is licensed under the terms of the MIT License. See the [LICENSE](https://github.com/joakimwinum/bytecore-byte/blob/main/LICENSE) file for the full text.
