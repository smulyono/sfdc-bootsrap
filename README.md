# [SFDC-Bootstrap v2.0]

Forked from Bootstrap v2.3.2 (http://twitter.github.com/bootstrap)

To get started, checkout http://getbootstrap.com!

## What is this ?

Ability to use bootstrap in friendly manner under SFDC environment or other layout / theme. The idea is
to have bootstrap play nicely with other css that is already in the page.

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
* Use the unmanaged package [here] (https://login.salesforce.com/packaging/installPackage.apexp?p0=04tE0000000UrDU). Get more information about this package [here] (https://github.com/smulyono/sfdc-customui)

## How to Generate / Build

* Follow the instructions to [compile Bootstrap less] (file http://twitter.github.com/bootstrap/extend.html#compiling)
    * $> npm install
    * Run `make zip-bootstrap` to generate the sfdc-bootstrap.zip files


