# Development installation script 
![CI Install Curl Wget and Dbeaver](https://github.com/danielso2007/development_installation_script/workflows/CI%20Install%20Curl%20Wget%20and%20Dbeaver/badge.svg)
[![Build Status](https://travis-ci.org/danielso2007/development_installation_script.svg?branch=master)](https://travis-ci.org/danielso2007/development_installation_script) ![GitHub repo size](https://img.shields.io/github/repo-size/danielso2007/development_installation_script.svg) ![GitHub All Releases](https://img.shields.io/github/downloads/danielso2007/development_installation_script/total.svg) ![GitHub issues](https://img.shields.io/github/issues/danielso2007/development_installation_script.svg) ![GitHub followers](https://img.shields.io/github/followers/danielso2007.svg) ![GitHub package.json version](https://img.shields.io/github/package-json/v/danielso2007/development_installation_script.svg?color=green) ![GitHub language count](https://img.shields.io/github/languages/count/danielso2007/development_installation_script.svg) ![GitHub top language](https://img.shields.io/github/languages/top/danielso2007/development_installation_script.svg)

- [Installation](#installation)
- [Complete installation](#complete-installation)
- [Individual installation](#individual-installation)
  - [Installing each tool](#installing-each-tool)


# Installation

Script used for basic tool installations for a development environment.
It is an installation for Java and / or Android developments.
Clone this repository and run the commands below.
It is important that your user ($ USER) has read and write access to the / opt directory. Otherwise, perform the following steps:
```shell
sudo chown $ {USER}:"REPORT GROUP" /opt -R
```
Then permission on the subfolders:
```shell
sudo chmod 2770 /opt/ -R
```
- Please, if you have a better solution, please report me your solution.

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