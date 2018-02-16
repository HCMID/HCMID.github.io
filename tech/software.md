---
layout: page
title: Software for editing manuscripts
---



## Version control

Since we manage all our work using `git` for version control,  all members of your team should:

- install git: <https://github.com/>
- be able to start up a terminal running a `bash` shell.
    - OS X users: `Terminal.app` is already in `/Applications/Utilities`
    - Windows users: use `gitbash` (installed with Windows versions of `git`)
    - Linux users: any of your favorite terminals

## Text editor

We edit several types of documents:  tables of data in delimited text files, diplomatic editions marked up in XML, scripts in the Scala language, and texts, slide shows and web pages composed in Markdown.  The [Atom editor](https://atom.io/) provides excellent support for all of these when configured with appropriate plugins.

Download and install atom from <https://atom.io/>. If on OS X, open atom and choose from the Atom menu, "Install Shell Commands".  (This step should not be necessary on Windows or Linux operating systems.)


### Configuring Atom for scholarly work on manuscripts


Installing atom should have installed the command-line atom package manager `apm`.   Copy and paste the following commands into a bash shell to install a suite of packages:

    apm install intentions
    apm install busy-signal
    apm install linter
    apm install linter-ui-default
    apm install linter-autocomplete-jing
    apm install atom-xsltransform
    apm install tablr
    apm install xml-formatter


Download the file [atom-tablr-conf.cson](http://hcmid.github.io/tech/atom-tablr-conf.cson), and copy it to atom's default location for config files. You can do that with the `cp` command in your terminal.

    cp atom-tablr-conf.cson $HOME/.atom/config.cson


(Gotcha: if your browser renames your file for you  when you download -- e.g., if it calls it `atom-tablr-conf.txt` -- it, you'll have to use the name it chose instead of `atom-tablr-conf.cson`.)


Finally,

1. add the [linter-autocomplete-jing](https://github.com/aerhard/linter-autocomplete-jing) plugin
2. install [this package](https://github.com/neelsmith/atomic-tei) for automatic validation of documents following the Text Encoding Initiative (TEI) schema
