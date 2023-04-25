# Emacs
Learning emacs-lisp

## Overview
> Custom emac org file taken from [SystemCrafters](https://github.com/SystemCrafters) and modified to a windows OS configuration.

## How to Run
> Install emacs from the provider of your choice. Here we use ***Chocolatey*** which can easily be installed from this org file (either install emacs by hand or ***Chocolatey*** - your choice). After installation, open emacs and search for the org file using ```C-x C-f```, find ***emacs.org*** under ```~/Users/emacs``` and load the file. Keep in mind that the ***init.el*** used by emacs and loaded at startup doesn't exist. With the org file frame active, use ```M-x org-babel-tangle``` to generate the ***init.el*** file and close the application. Re-open emacs so it can pickup the newly generated ***init.el*** and the configuration packages will be installed.

#### Note : Env PATH variables are required to be set on your Operating system. Git, Gh, Mingw, etc... should be added in order for emacs to access shell commands from the command line. Dependencies can be installed through ***Chocolatey*** using the emacs configuration provided.

#### Keybinds : ```C-x``` -> ```Ctrl-x```, ```M-x``` -> ```Alt-x```
