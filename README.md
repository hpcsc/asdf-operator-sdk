# asdf-operator-sdk

This is a plugin for [asdf](https://github.com/asdf-vm/asdf) to install/manage [operator-sdk cli](https://github.com/operator-framework/operator-sdk)

## Installation

```
asdf plugin-add operator-sdk https://github.com/hpcsc/asdf-operator-sdk.git
```

## Usage

Check out the [asdf](https://github.com/asdf-vm/asdf) readme for general usage of asdf.

Most common usage:

```
asdf list-all operator-sdk # to list available versions of operator-sdk installation files
asdf install operator-sdk [latest|x.y.z] # to get latest|x.y.z version of operator-sdk installation files
asdf global operator-sdk x.y.z # set version x.y.z as global
```
