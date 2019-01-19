 # System Application Monitor
The goal of this project was to provide laptop users a better System Monitor. We wanted to provide a simple and easy to use application that also informed the user about a process that is using too much memory and if possibly it could have a memory leak. 

In addition, we also provided features that allowed the user to utilise multiple power consumption profiles to either allow them to use the full potential off their processor or help them extend their battery usage.

This project was developed in C/C++ in conjunction with Qt for the Graphical User interface. It is possible to use the program in console only mode, however. No additional packages were used. The intention was to provide a bare bone experience in the sense that any user could install this program and only need this program with no dependencies (aside from Qt).

## BUILDING REQUIREMENTS
For libprocps:

> sudo apt install libprocps-dev:i386 libprocps-dev

For cpupower:

> sudo apt install linux-tools-common

### For Ubuntu users
Update your OSD to allow for -t to work here http://www.webupd8.org/2010/05/finally-easy-way-to-customize-notify.html

## Background

Using the Linux operating system, this utility offers a simple to use system monitor, that provides system information for temperatures of various hardware components. In addition, the software also the ability to detect memory leaks from running processes.


## Motivation

The built in software does not have this capability and requires more work that necessary.

## Goals

Our goal is provide the user with a friendly graphical interface that allows the user to view their system's information without doing a ton of work. We also aim to provide the user with useful tools that detect potential problems, such as a memory leak.

## Authors

- **Tamara Alhajj** - *Intial Work* - [Github Page](https://github.com/TamaraAlhajj)

* **Mohamad Yassine** - *Intial Work* - [Github Page](https://github.com/moyass)
