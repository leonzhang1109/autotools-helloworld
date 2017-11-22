Autotools Helloworld
=========
Before to build this project, you should have your [autoconf][1] and [automake][1] installed.

[1]:https://ftp.gnu.org/gnu/autoconf/autoconf-latest.tar.gz
[2]:https://ftp.gnu.org/gnu/automake/automake-1.15.1.tar.gz

To build configure script, using the following steps:

> autoheader

> aclocal

> automake --add-missing

> autoconf

To build the whole project, using the following:

> ./configure

> make

> make install

Also, you can archive this project using `make dist`

