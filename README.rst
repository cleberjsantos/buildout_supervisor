.. contents:: Table of Contents
   :depth: 2

*****************************************************
supervisor.buildout
*****************************************************

Overview
--------

A system for controlling process state under UNIX.
Supervisor is a client/server system that allows its users to control a number of processes on UNIX-like operating systems.


Installation
^^^^^^^^^^^^^

You need to run::

    $ python bootstrap.py
    
This will install zc.buildout for you.

To create an instance supervisor immediately, run::

    $ bin/buildout -Nv -t 30

You can start your Supervisor instance by running::

    bin/supervisord -c etc/supervisord.conf
