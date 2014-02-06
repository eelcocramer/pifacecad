pifacecad
=========

PiFace Control and Display Python module.

Contrast is adjusted with screwdriver + screw by IR node.


Documentation
=============

[http://piface.github.io/pifacecad/](http://piface.github.io/pifacecad/)

You can also find the documentation and some examples installed at:

    /usr/share/doc/python3-pifacecad/

Install on Raspbian
===================

Make sure you are using the lastest version of Raspbian:

    $ sudo apt-get update
    $ sudo apt-get upgrade

Install `pifacecad` (for Python 3 and 2) with the following command:

    $ sudo apt-get install python{,3}-pifacecad

Test by running the `sysinfo.py` program:

    $ python3 /usr/share/doc/python3-pifacecad/examples/sysinfo.py

You will need to [configure the IR receiver](http://piface.github.io/pifacecad/lirc.html#setting-up-the-infrared-receiver>`_ yourself).

Install on Arch Linux
=====================

Make sure you are using the latest version of Arch Linux:

    $ sudo pacman -Syu
    
Install `pifacecad` (for Python 3) with the following command:

    $ sudo yaourt -S pifacecad

Test by running the `weather.py` program:

    $ wget https://raw.github.com/piface/pifacecad/master/examples/weather.py
    $ python weather.py
    
