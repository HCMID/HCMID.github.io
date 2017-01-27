---
layout: page
title: Software for editing manuscripts
---


## Basics

### Version control

Since we manage all our work using `git` for version control,  all members of your team should:

- install git: <https://github.com/>
- be able to start up a terminal running a `bash` shell.
    - OS X users: `Terminal.app` is already in `/Applications/Utilities`
    - Windows users: use `gitbash` (installed with Windows versions of `git`)
    - Linux users: any of your favorite terminals

### Validating XML editor

An excellent option is the [Atom editor](https://atom.io/).  After you install Atom:

1. add the [linter-autocomplete-jing](https://github.com/aerhard/linter-autocomplete-jing) plugin
2. install [this package](https://github.com/neelsmith/atomic-tei) for automatic validation of documents following the Text Encoding Initiative (TEI) schema


## A virtual machine for editors

Many useful tools for work on MID projects are pre-installed in [this virtual machine](https://github.com/neelsmith/dhvm).  To install it on your computer, you'll need the following software:


- [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
- [Vagrant](https://www.vagrantup.com/)

See the MID youtube playlist for [tutorials on installing and using a virtual machine](https://www.youtube.com/playlist?list=PLJTxcGcJBiz5H-BhBkDFaebI9-R9RSkIN).
