# ldap-cpp
OpenLDAP Client in C++ for Windows

This is a [fork](https://github.com/winlibs/openldap/tree/master/contrib/ldapc%2B%2B) of the OpenLDAP C++ client found in the OpenLDAP distribution contrib folder.

[Documention](http://www.openldap.org/conf/odd-tuebingen-2006/Ralf.pdf)

####Dependencies
* A port of [openldap](https://github.com/winlibs/openldap.git) with VS project files
* [cyrus-sasl](https://github.com/dinhviethoa/cyrus-sasl/tree/master/build-windows) build for VS2013
* Precompiled [openssl-1.0.1](http://www.npcglib.org/~stathis/blog/precompiled-openssl/) binaries built with VS2013

####Linker Dependencies
* libldap.lib
* liblber.lib
* libsasl2.lib
* ssleay32.lib
* libeay32.lib
* ws2_32.lib


