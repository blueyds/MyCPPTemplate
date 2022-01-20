# MyCPPTemplate

## Make the following changes

### ***configure.ac*** test will be the name of your app and 0.1 will be your version

    AC_INIT([test],[0.1])

### ***Makefile.am*** test will be name of your final binary

    bin_PROGRAMS = test
    test_SOURCES = src/main.cpp
    
### Pull in the submodule for M4s autoconf directory by running the following

    git submodule init
    git submodule update

### rerun configure tools

    autoreconf --make
