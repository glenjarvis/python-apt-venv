# python-apt-venv

## Use Ansible Apt in a Virtual Env


This project has been absorbed into the **ansible-simple-apt** project:

https://github.com/glenjarvis/ansible-simple-apt/


We are abandoning the attempt to compile the python_apt library for a Python
virtualenv. It works against the original intent of the original Authors:

[Debian Bug #845330](https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=845330)
> Julian Andres Klode <jak@debian.org>
> Aargh, not this whole PyPI thing again. Nobody ever officially uploaded
> python-apt there. It is tightly coupled with APT, and not supposed to be
> distributed in any fashion other than via Debian packages.There is no, and
> has never been any support for PyPi. And I can say that I have absolutely no
> interest in duplicating work there.

Instead, we remove it's dependency in our version of the Ansible `apt` module.
