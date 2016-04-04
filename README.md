To compile on OSX, let say you install pliant into /opt/ so you have /opt/pliant_program directory.
Create the following shell script and save it as /usr/local/bin/pliant and make it executable

----8<----
#!/bin/sh
exec /opt/pliant_program/binary/osx-i386/pliant-debug1.exe module "/pliant/install/minimal.pli" $*
---->8----

Then, you can run each sample file like this:

$ pliant max_meta_example.pli


To understand the meta programming examples, read the following tutorial about meta programming 

http://www.fullpliant.org/page/pliant/H2A3BV4M/0EEMW25
