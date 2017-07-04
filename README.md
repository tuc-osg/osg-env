# OSG Environment

A set of Ansible scripts to prepare a machine in our group. You will get:

  - All TU Chemnitz fonts being set up for LaTex.
  - The TU Chemnitz beamer template being setup for LaTex.

The scripts are tested on:

  - macOS Sierra

## How to run

  - Download this: https://www.tu-chemnitz.de/uk/corporate_design/vorlagen/font/tucroboto.zip
  - Download this: https://www.tu-chemnitz.de/uk/corporate_design/vorlagen/dokumente/latex/tucbeamer2014.zip
  - Install Ansible (sudo pip install ansible)
  - Run this: ansible-playbook -i ./localhost.ini ./osg.yaml --ask-become-pass
  - Done.
