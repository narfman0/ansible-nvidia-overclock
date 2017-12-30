nvidia-overclock
================

.. image:: http://img.shields.io/badge/ansible--galaxy-nvidia-overclock-blue.svg
  :target: https://galaxy.ansible.com/narfman0/nvidia-overclock/

.. image:: https://travis-ci.org/narfman0/ansible-nvidia-overclock.png?branch=master
    :target: https://travis-ci.org/narfman0/ansible-nvidia-overclock

Ansible role that configured nvidia overclocking for linux (ubuntu) hosts

TODO
----

* Big missing part is cuda. Cuda is hard to programmatically install, but this
  script may target 16.04 (LTS) first and work from there possibly.

* Currently restarts on coolbits *shrugs*

Installation
------------

Install with ``ansible-galaxy install narfman0.nvidia-overclock``

License
-------

Copyright (c) 2017 Jon Robison

See included LICENSE for licensing information
