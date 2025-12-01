# Project Planner (Final-Project-for-technion)

## Introduction

As a final project, may I have the distinct honor to present to you **Project Planner**.

With **Project Planner** You can calculate the amount of compute resources needed for your project.

There are currently 3 main functionalities:
### Inventory Items ###
An _item_ is made out of:
* Name
* CPU count
* RAM amount
* Hard Disk size
* Price

### Projects ###
A _project_ is made out of:
* Name
* Types and quantities of _invnetory items_

### Statistics ###
In the end you get calculations which might help you plan your projects more effectively.

## Requirements
The project in built on Python 3.13 (and Flask 3.1.1 for web version).
It has automation to compile it into a Docker image for the web version.

For CLI, please clone the repo and run the CLI.py file. It is interractive!

The automations were built for Bash and were tested on an Ubuntu 22.04 machine, but it should normally run in any modern Linux machine with preinstalled docker.

The endgame deployment should run the project in AWS in HA mode, so please make sure to have an account before deployment.

## Basic usage

### Inventory Items ###
**Show all items**

**Add an item** - The name should be unique and you should add quantities of each displayed aspect.

**Modify existing item** - Same as 'add' but the projects that use this item will also be updated accordingly.

**Delete item** - If the item is not used by any project, it can be deleted.

### Projects ###
**Show all projects**

**Add a project** - The porject name should be unique. You should then map amounts of resources to a project.

**Modify a project** - Same as 'add' for an existing project.

**Delete project**

### Statistics ###
**Display statistics**


## Deployment instructions

In your README file, Eli :)

Enjoy!
