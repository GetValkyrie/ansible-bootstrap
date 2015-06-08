Ansible Bootstrap
=================

[![Build Status](https://travis-ci.org/GetValkyrie/ansible-bootstrap.svg?branch=master)](https://travis-ci.org/GetValkyrie/ansible-bootstrap)

This simple script allows the installation of Ansible from sources. You can
specify a branch using the '-b' option, or setting the ANSIBLE_BRANCH
environment variable.  Using the '-c' option, or setting the ANSIBLE_CHECKOUT
environment variable, you can specify a particular commit to checkout.

Example one-liner:

    curl https://raw.githubusercontent.com/GetValkyrie/ansible-bootstrap/master/install-ansible.sh| sudo env ANSIBLE_BRANCH=devel /bin/sh

See the included Vagrantfile and .travis.yml for examples of methods you might
want to use in your projects.
