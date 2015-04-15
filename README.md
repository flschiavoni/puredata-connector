# puredata-connector

Connector is a Pure Data external used to connect objects in a patch. I know, it doesn't make sense! 

![My image](https://github.com/flschiavoni/puredata-connector/blob/gh-pages/connector.png)


TO COMPILE
==========
`make`

TO INSTALL
==========
`make install`

(In Linux you should use `sudo make install`)


TO INSTALL ONLY TO USER (Linux)
========================

`mkdir -p ~/pd-externals/connector`

`cp connector.pd_linux ~/pd-externals/connector/.`

`cp connector-help.pd  ~/pd-externals/connector/.`

`cp connector-meta.pd  ~/pd-externals/connector/.`

FILES INFORMATION
=================

Makefile is based on oficial Pure Data Makefile Template available in:

https://puredata.info/docs/developer/MakefileTemplate

Header files (.h) was copied from Pure Data oficial repository available in:

https://svn.code.sf.net/p/pure-data/svn/trunk/pd/src/


Have fun!

https://flschiavoni.github.io/puredata-connector
