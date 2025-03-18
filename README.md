# BChecks for BurpSuite Professional

## Overview

BChecks for BurpSuite Professional is a simple Git repository that submodules all repositories from the [BChecks-Collection](https://github.com/emadshanab/BChecks-Collection). This collection includes various BChecks scripts designed to enhance security testing with BurpSuite.

> Use with the [BCheck Helper](https://portswigger.net/bappstore/41274be469184a56b06d6a791ce8a9ce) BurpSuite Extension.

## Installation

To clone this repository along with all its submodules, use the following command:

```sh
git clone --recurse-submodules https://github.com/your-username/BChecks-for-BurpSuite.git
```

If you've already cloned the repository without submodules, initialize and update them using:

```sh
git submodule update --init --recursive
```

## Updating Submodules

To update the submodules to their latest versions, run:

```sh
git submodule update --remote --merge
```

## Usage

After cloning the repository, you can use the BChecks scripts in BurpSuite Professional to enhance your security testing workflow. Simply import the required scripts into BurpSuite as needed.

## Contributing

If you want to contribute to this project, feel free to fork the repository and submit pull requests.

## License

This repository follows the license terms of the original [BChecks-Collection](https://github.com/emadshanab/BChecks-Collection). Please review their licensing policies before usage.

## Acknowledgments

Special thanks to [Emad Shanab](https://github.com/emadshanab) for maintaining the BChecks-Collection.
