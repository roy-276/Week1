# How To Install Git on Ubuntu 20.04

![Digital Ocean Logo](https://imgs.search.brave.com/M02VNwbcMEzwbMilIIUzQb48PlsTcmzYulOUVZ0rb7s/rs:fit:711:225:1/g:ce/aHR0cHM6Ly90c2Uy/Lm1tLmJpbmcubmV0/L3RoP2lkPU9JUC5n/eE5WSWJRQXRSbTNO/UndrbUJiMzZ3SGFF/OCZwaWQ9QXBp)

[Article by Digital Ocean](https://www.digitalocean.com/community/tutorials/how-to-install-git-on-ubuntu-20-04 "Article by Digital Ocean")

## Introduction

Version control systems like Git are essential to modern software development best practices. Versioning allows you to keep track of your software at the source level. You can track changes, revert to previous stages, and branch to create alternate versions of files and directories.

### Prerequisites

You will need an Ubuntu 20.04 server with a non-root superuser account.

To set this up, you can follow our [Initial Server Setup Guide for Ubuntu 20.04.](https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-20-04)

With your server and user set up, you are ready to begin.

### Installing Git with Default Packages

The option of installing with default packages is best if you want to get up and running quickly with Git, if you prefer a widely-used stable version, or if you are not looking for the newest available functionalities. If you are looking for the most recent release, you should jump to the section on [installing from source.](https://www.digitalocean.com/community/tutorials/how-to-install-git-on-ubuntu-20-04#installing-git-from-source)

Git is likely already installed in your Ubuntu 20.04 server. You can confirm this is the case on your server with the following command:

> - $ git --version

If you receive output similar to the following, then Git is already installed.

> **Output** > _git version 2.25.1_

If this is the case for you, then you can move onto [setting up Git](https://www.digitalocean.com/community/tutorials/how-to-install-git-on-ubuntu-20-04#setting-up-git)], or you can read the next section on [how to install from source](https://www.digitalocean.com/community/tutorials/how-to-install-git-on-ubuntu-20-04#installing-git-from-source)] if you need a more up-to-date version.

However, if you did not get output of a Git version number, you can install it with the Ubuntu default package manager APT.

First, use the apt package management tools to update your local package index.

> - $ sudo apt update

With the update complete, you can install Git:

> - $ sudo apt install git

You can confirm that you have installed Git correctly by running the following command and checking that you receive relevant output.

> - $ git --version
>   **Output** > _git version 2.25.1_

With Git successfully installed, you can now move on to the Setting Up Git section of this tutorial to complete your setup.

### Installing Git from Source

[To continue reading](https://www.digitalocean.com/community/tutorials/how-to-install-git-on-ubuntu-20-04)

#### About the authors

[Lisa Tagliaferri - Developer and author at DigitalOcean.](./img/globe-light.svg)

---
