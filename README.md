# my_scripts

These are all my scripts that I use daily.

## Use

To be able to use these scripts in any directory you may want to add the following line to your .bashrc or .zshrc or any other shell config file depending on the shell you use:

```bash
export PATH=$HOME/path-to-my_scripts/:$PATH
```

If you want to also be able to use it in root do this also for the root user.

# build_csfml.sh

This script installs the csfml library for Epitech.

# clean

This script deletes temporary files for c and python and also .vscode folders.

# clone

This script clones an epitech repo you need to give it the epitech email of the owner of the repo as the first agument and the repo name as the second argument as follow:

```bash
clone <firstname.lastname@epitech.eu> <repo_name>
```

# install_criterion.sh

This script installs the criterion library to allow you to make unit tests for your C and C++ programs.

# push

This script adds all the files then commit them with the commit message you gave it in argument and finally pushes everything. If you use a Makefile it will do a make if the make fails it warns you and doesn't push but if you do not use any Makefile then you could use the <no_make> option.
You need to use the script this way:

```bash
push <commit message> <no_make>
```

# repo

This is a script to create an Epitech repo, to use it change the email adress by yours and the repo name is given as an argument.

## Use

```bash
repo <repo_name>
```

# run

This script runs the disk image of the moulinette at Epitech to allow you to verify if your program works with the versions of python of the moulinette for example.
You first need to install docker then you need to start Docker with the following command:

```bash
sudo systemctl start docker
```

In the run script put the filepath of your project to be sure that docker will have the poject you want to test.
Finally you just have to switch to root and run the script as follow:

```bash
sudo su
run
```
