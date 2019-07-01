# Development installation script [![Build Status](https://travis-ci.org/danielso2007/development_installation_script?branch=master)][3] [![nvm version](https://img.shields.io/badge/version-v0.0.0-yellow.svg)][4] [![CII Best Practices](https://bestpractices.coreinfrastructure.org/projects/684/badge)](https://bestpractices.coreinfrastructure.org/projects/684)

- [Installation](#installation)
- [Complete installation](#complete-installation)
- [Individual installation](#individual-installation)
 - [Installing each tool](#installing-each-tool)


# Installation

Script used for basic tool installations for a development environment.
It is an installation for Java and / or Android developments.
Clone this repository and run the commands below.

# Complete installation

After cloning the repository, run the shell file:
```shell
./install_dev_script
```
If the file is not executable, run the command:
```shell
chmod a + x install_dev_script
```
A complete installation will be done with the following tools:
```
curl        => Curl is a tool to transfer data from or to a server
wget        => Wget command is a Linux command line utility that helps us to download the files from the web
nvm         => Node Version Manager
yvm         => Yarn Version Manager
sdk         => SDKMAN! is a tool for managing parallel versions of multiple Software Development Kits on most Unix based systems
toolbox     => A control panel for your tools and projects (Jetbrains)
postgres    => PostgreSQL is a powerful, open source object-relational database system ( ORDBMS )
umake       => Ubuntu Make is a command line tool which allows you to download the latest version of popular developer tools
eclipse-jee => Installing eclipse jee by umake
sts         => Install spring-tools-suite by umake
vscode      => Visual Studio Code is a cross-platform text editor made available by Microsoft for web application development
chrome      => O Google Chrome é um navegador de internet, desenvolvido pela companhia Google
mongodb     => MongoDB is a new database idea bringing Document Oriented Database concepts
compass     => The GUI for MongoDB. Visually explore your data. Run ad hoc queries in seconds
```

# Individual installation

For individual installation, run the command for help:
```shell
./install_dev_script -h
```

## Installing each tool

Run the command for expensive tool presented in the help, for example:
```shell
./install_dev_script -i curl
```
The curl tool will be installed.
```shell
./install_dev_script -i mongodb
```
It will be installed to mongodb database.