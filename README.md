# MyCPPTemplate

## Make the following changes

### ***configure.ac*** test will be the name of your app and 0.1 will be your version

    AC_INIT([test],[0.1])

### ***Makefile.am*** test will be name of your final binary

    bin_PROGRAMS = test
    test_SOURCES = src/main.cpp

### rerun configure tools

    autoreconf --make
