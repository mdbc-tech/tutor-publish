Tutor plugin edx publisher based on cookiecutter 🍪
============================

This is a `cookiecutter <https://cookiecutter.readthedocs.io/en/latest/tutorial2.html>`__ for installing open edx publisher modules  its based on `Tutor plugins <https://docs.tutor.overhang.io/plugins.html>`__. and I don't know if it will work
.

Requirements
------------

::

    pip install cookiecutter

Usage
-----

::

    cookiecutter https://github.com/mdbc-tech/tutor-publish

Please keep the "contrib" part in your generated package name to differentiate from official plugins.

Once you have generated your plugin, you can start using it right away (even if it won't do anything)::

    pip install -e ./tutor-publisher
    tutor plugins list # your plugin should appear here
    tutor plugins enable tutor-publisher # hack at it!

License
-------

This software is licensed under the terms of the `AGPLv3 <https://www.gnu.org/licenses/agpl-3.0.en.html>`__.
