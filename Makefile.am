AUTOMAKE_OPTIONS = foreign
bin_PROGRAMS = my_program
my_program_SOURCES = main.cpp
dist_deb: $(srcdir)/$(PACKAGE).tar.gz
    dpkg-buildpackage -us -uc

