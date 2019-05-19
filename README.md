# Eclipse IDE Setup

This repository contains an Eclipse IDE setup file that I am using for my projects.

It contains the formatter rules I am using, save actions, plugins I am working with etc.

## Use it

* Start the Eclipse Installer
* Ensure you are using the "Advanced Mode"
** Product Version: Latest Release
* Next
* On the "Project" selection press the "+" ("Add user projects") button
** Catalog: Github Projects
** Resource URIs: https://raw.githubusercontent.com/maggu2810/eclipse-ide/master/oomph/maggu2810.setup
* Now you can mark the Project group: `Github Projects, <User>, maggu2810 base IDE setup`
* Install the IDE

## Plugins

### M2E Sourcelookup

Eclipse Plugin that provides Maven Dependencies as Source Container in JDT Launching Configuration.

https://github.com/bjmi/m2e.sourcelookup

This plugin is rather useful e.g. if you would like to debug a Karaf container with all the bundles available in the container (create a POM using KAT Bundle POM Generator).

## Notes

### Maven Development Tools

https://github.com/ifedorenko/com.ifedorenko.m2e.mavendev

This Eclipse plugin is currently not added to the setup file but I would like to keep a reference here to keep a hint if I need it some time.

It could perhaps be useful if I would like to write some Maven Plugins...
