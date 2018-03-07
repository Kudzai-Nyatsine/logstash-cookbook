# Chef-logstash

## Description

This cookbook is primarily for configuration and installation of recipe dependencies for the ELK project along with
other two cookbooks, Elastic search and Kiban cookbooks.

The cookbook is also for installing logstash on the virtual machine.

## Requirements

In order to run the cookbook, you need to ensure that you have

* [virtual box](https://www.virtualbox.org/wiki/Downloads)

* [vagrant](https://www.vagrantup.com/downloads.html)

installed.

Vagrant enables users to create and configure lightweight, reproducible, and portable development environments.

Vagrant comes with support out of the box for VirtualBox, a free, cross-platform consumer virtualization product.

## Installation

1. Once the logstash cookbook is installed, open it in the text editor and install the relevant recipes in the recipes folder `recipes > default.rb`.

2. In recipes folder, Install

* 	``Java`` 

* 	``logstash``.

## Test Environment

To check if the cookbook is correctly configured, run the below tests; 

1. Run

	``chefspec``

 to test your your resources and recipes.

2. Run

	``kitchen test``

in the bash command to test if the recipes were installed and configured successfully.
