# Utah Tech Community Survey

This project contains example tools and processes for analyzing the data
generated in the ongoing Utah Tech Community Survey.

Additionally, any findings and insight will be published here

# Install

## Required

For each follow the links for your choosen file-system.

  * [Git](https://git-scm.com/downloads)
  * [Docker](https://docker.com/products/docker)
    * If you are using OSX or Windows using the standard installer will
    install both `docker` and `docker-compose`
    * If you are using Linux then you will also need to install
    [docker-compose](https://docs.docker.com/compose/install/)
    separately
  * [Git Large File Storage](https://github.com/git-lfs/git-lfs/releases/tag/v1.5.2)

## Optional

If you do not have a software background then the following optional
tools may help you get started.

  * [Github Desktop](https://desktop.github.com/) a visual client for
  `git` repos

# Quickstart

Once the tool dependencies are installed you will need to clone this
project repo.

**Commandline**

    $ git clone https://github.com/dgonzo/utahtechcommunity.git
    $ cd utahtechcommunity
    $ docker-compose up

**Desktop**

  * Follow directions in Github Desktop help docs for cloning a repo [here](https://help.github.com/desktop/guides/contributing/cloning-a-repository-from-github-to-github-desktop/).
  * Start the project using your favorite command prompt (e.g.
  Terminal.app or PowerShell/`cmd`) and do:
    * cd <path to cloned directory>
    * docker-compose up

If your web browser does not automatically open then navigate to
[http://localhost:8000](http://localhost:8000)


