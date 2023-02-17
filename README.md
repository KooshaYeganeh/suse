# suse

![SUSE](https://en.opensuse.org/images/f/f2/Button-laptop-colour.png)
![Tumbleweed](https://www.opensuse.org/build/images/tumbleweed-icon.svg)
![Leap](https://www.opensuse.org/build/images/opensuse-regular-release-icon.svg)

- [**INFO**]()
    - [Explain](https://github.com/KooshaYeganeh/suse#clearing-misunderstandings-and-explaining-the-project)
    - [Basic Info](https://github.com/KooshaYeganeh/suse#basic-information)

- [**Install**](https://github.com/KooshaYeganeh/suse#install)
- [**Basic Tutorial**](https://github.com/KooshaYeganeh/suse#basic-tutorial)
- [**Remove**](https://github.com/KooshaYeganeh/suse#remove)
- [**AboutME**](https://github.com/KooshaYeganeh/suse#aboutme)


A simple software for **openSUSE** users.

that can Make Everyday Tasks Easier for Developers and System Administrators.


 ### Clearing Misunderstandings and Explaining the Project   

There is no claim that this package manager is better or more optimal than the others
The goal is to improve platforms or make things easier
I wrote this package manager for my daily tasks I am in this philosophy that 
I try to write everything I need myself and I wanted to make it available to others.
and support and accompany us to make the conditions better for ourselves.

### Basic Information

> Supported Distrubutions : "Leap" and "Tumbleweed"  
> Update and Upgrade and dist upgrade Like ubuntu and Fedora  
> Remove Unneed packages  
> show Package Providers  
> List Installed Apps  
> Show repositories  
> Show known apps  
> Show Installation Manual  
> Support for software that is not supported by the main package manager  
> My own open source software has also been added to this script.  
> Recommending documents to read about the requested software  
> Install and Remove Packages
> Optimization of software search: It has been tried to reduce the sensitivity to upper and lowercase letters 
  or having a dash or not having a dash in the search for software, etc., and 
  if you know the name of the software, you can search or install it without any trouble. do.


## Install

```
./Install
```

## Basic Tutorial

**suse Package Manager**


**--whereis** <appname>: Each software shows in which repository it is located or which repositories provide this software. 
*Example :*
```
 suse --whereis vlc
```

**--howinstall** <appname>: It shows the installation steps. It shows which steps you should go through to install the relevant software on your system.
*Example :*
```
suse --howinstall vlc
```

**--info** : show information

```
suse --info
```
**man** : suse man ( Manual )

**--install** : use this command to install a software
*Example :*
```
suse --install vscode
```
**--remove** <appname> : use this command to remove a software and try to remove dependencies

*Example :*
```
suse --remove vlc
```
**--remove** <appname> **--clean-unnneded** : remove + clean_unnneded

**--list-app** : List Installed apps  
```
suse --list-app
```
**--search-app** <appname>: Serach in installed Apps

*Example :*
```
suse --search-app vlc
```
**--clean-unneed** : clean out all unneeded autoinstalled dependencies

```
suse --clean-unneed
```
**--suport-sytems** : Which distributions does this package manager support

```
suse --support-systems
```
**--list-repository** : list of repositories in system

```
suse --list-repo
```
**--list --known** <app name> : Known Apps to suse

*Exapmle :*
```
suse --list --known security-tools
```
**--update** : update Packages
```
suse --update
```
**--upgrade** : upgrade packages
```
suse --upgrade
```
**--dist-upgrade** : Distribution Upgrade
```
suse --dist-upgrade
```
**--document** : show recomended Documents Links
*Example :*
```
suse --document clamav
```

## Remove 

```
sudo rm /usr/bin/suse
```

## AboutME

> Developer : Koosha Yeganeh  
> [**GitHub**](https://github.com/KooshaYeganeh)  
> [**DockerHub** ](https://hub.docker.com/u/kooshakooshadv)   
> [**GitBooks** ](kooshayeganeh.gitbook.io)

and Some More :) 


