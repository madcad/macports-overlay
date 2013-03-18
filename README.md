This [MacPorts overlay][overlay] contains fixes and enhancements to the stable
version of the MacPorts ports tree for Mac OS X.

Installation
============

Add the line

    file:///path/to/this/directory

to `/opt/local/etc/macports/sources.conf` *before* the rsync source and run

    sudo portindex

in the same directory where this README is located.

[overlay]: http://guide.macports.org/#development.local-repositories