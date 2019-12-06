ACLOCAL_AMFLAGS = -I m4 -I @VARNISHAPI_DATAROOTDIR@/aclocal

EXTRA_DIST = \
        README.rst \
        vmod-dns.spec

DISTCHECK_CONFIGURE_FLAGS = RST2MAN=:

SUBDIRS = src

include rpm.am
