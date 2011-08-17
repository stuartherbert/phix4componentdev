phix4componentdev
=================

phix4componentdev is a meta-package that installs phix itself, and all of the dependencies needed for creating and maintaining PHP components.

phix is a general-purpose, easily-extensible command-line tool for PHP. It has the advantage of being framework-agnostic, allowing you to create your own command-line tools today that will not break when you upgrade or switch frameworks.

System-Wide Installation
------------------------

phix4componentdev should be installed using the [PEAR Installer](http://pear.php.net). This installer is the community's de-facto standard for distributing PHP components.

    sudo pear channel-discover pear.phix-project.org
    sudo pear install --alldeps phix/phix4componentdev

After installation, you will find phix inside your local PEAR repository, which on Linux systems is normally /usr/share/php.

Documentation
-------------

phix is self-documenting; use 'phix help' to get started.

An online manual is coming soon.  You can also see Stuart's blog series on creating PHP components: http://blog.stuartherbert.com/php/php-components/

Development Environment
-----------------------

If you want to patch or enhance this component, everything you need has already been installed.

To submit patches to this component, please clone our GitHub repo:

  http://github.com/stuartherbert/phix4componentdev
