# MyCPPTemplate

## Make the following changes

### ***configure.ac***

>AC_INIT([test],[0.1])

test will be the name of your app and 0.1 will be your version

### ***Makefile.am***
>bin_PROGRAMS = test
test_SOURCES = src/main.cpp

test will be name of your final binary

### rerun configure tools

>autoreconf

>./configure

>make
