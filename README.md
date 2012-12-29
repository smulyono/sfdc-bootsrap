# [SFDC-Bootstrap v1.0]

Forked from Bootstrap v2.2.2 (http://twitter.github.com/bootstrap)

## Goal

Ability to use bootstrap in friendly manner under SFDC environment. 

## Modification

Modify bootstrap less with several nested rules. All modifications note can be seen under /less/bootstrap.less.
All bootstrap tags / styles can be used under nested id/class 'bootstrap-panel'.

## Quick start

* [Download the latest release] (https://github.com/smulyono/sfdc-bootsrap/archive/master.zip)
  Clone the repo `git clone git://github.com/smulyono/sfdc-bootsrap.git`.
* Zip the bootstrap (build directory) to 'sfdc-bootstrap.zip' or Run `make zip-bootstrap`. To be able to compile / build
  follow the instructions on how to generate / build.
* Upload sfdc-bootstrap.zip file to static resources
* Example of usage under /pages/testBootstrap.page
  or see live demo : https://smulyono-developer-edition.na9.force.com/testBootstrap

## How to Generate / Build

* Follow the instructions to [compile Bootstrap less] (file http://twitter.github.com/bootstrap/extend.html#compiling)
* Run `make zip-bootstrap` to generate the sfdc-bootstrap.zip files
