# Makefile.in generated by automake 1.14.1 from Makefile.am.
# kernel/network/Makefile.  Generated from Makefile.in by configure.

# Copyright (C) 1994-2013 Free Software Foundation, Inc.

# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.




am__is_gnu_make = test -n '$(MAKEFILE_LIST)' && test -n '$(MAKELEVEL)'
am__make_running_with_option = \
  case $${target_option-} in \
      ?) ;; \
      *) echo "am__make_running_with_option: internal error: invalid" \
              "target option '$${target_option-}' specified" >&2; \
         exit 1;; \
  esac; \
  has_opt=no; \
  sane_makeflags=$$MAKEFLAGS; \
  if $(am__is_gnu_make); then \
    sane_makeflags=$$MFLAGS; \
  else \
    case $$MAKEFLAGS in \
      *\\[\ \	]*) \
        bs=\\; \
        sane_makeflags=`printf '%s\n' "$$MAKEFLAGS" \
          | sed "s/$$bs$$bs[$$bs $$bs	]*//g"`;; \
    esac; \
  fi; \
  skip_next=no; \
  strip_trailopt () \
  { \
    flg=`printf '%s\n' "$$flg" | sed "s/$$1.*$$//"`; \
  }; \
  for flg in $$sane_makeflags; do \
    test $$skip_next = yes && { skip_next=no; continue; }; \
    case $$flg in \
      *=*|--*) continue;; \
        -*I) strip_trailopt 'I'; skip_next=yes;; \
      -*I?*) strip_trailopt 'I';; \
        -*O) strip_trailopt 'O'; skip_next=yes;; \
      -*O?*) strip_trailopt 'O';; \
        -*l) strip_trailopt 'l'; skip_next=yes;; \
      -*l?*) strip_trailopt 'l';; \
      -[dEDm]) skip_next=yes;; \
      -[JT]) skip_next=yes;; \
    esac; \
    case $$flg in \
      *$$target_option*) has_opt=yes; break;; \
    esac; \
  done; \
  test $$has_opt = yes
am__make_dryrun = (target_option=n; $(am__make_running_with_option))
am__make_keepgoing = (target_option=k; $(am__make_running_with_option))
pkgdatadir = $(datadir)/hellox
pkgincludedir = $(includedir)/hellox
pkglibdir = $(libdir)/hellox
pkglibexecdir = $(libexecdir)/hellox
am__cd = CDPATH="$${ZSH_VERSION+.}$(PATH_SEPARATOR)" && cd
install_sh_DATA = $(install_sh) -c -m 644
install_sh_PROGRAM = $(install_sh) -c
install_sh_SCRIPT = $(install_sh) -c
INSTALL_HEADER = $(INSTALL_DATA)
transform = $(program_transform_name)
NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
build_triplet = x86_64-unknown-linux-gnu
host_triplet = x86_64-unknown-linux-gnu
DIST_COMMON = $(top_srcdir)/kernel/kernel.mk $(srcdir)/Makefile.in \
	$(srcdir)/Makefile.am $(top_srcdir)/depcomp
subdir = kernel/network
ACLOCAL_M4 = $(top_srcdir)/aclocal.m4
am__aclocal_m4_deps = $(top_srcdir)/configure.ac
am__configure_deps = $(am__aclocal_m4_deps) $(CONFIGURE_DEPENDENCIES) \
	$(ACLOCAL_M4)
mkinstalldirs = $(install_sh) -d
CONFIG_HEADER = $(top_builddir)/kernel/config.h
CONFIG_CLEAN_FILES =
CONFIG_CLEAN_VPATH_FILES =
LIBRARIES = $(noinst_LIBRARIES)
ARFLAGS = cru
AM_V_AR = $(am__v_AR_$(V))
am__v_AR_ = $(am__v_AR_$(AM_DEFAULT_VERBOSITY))
am__v_AR_0 = @echo "  AR      " $@;
am__v_AR_1 = 
libnetwork_a_AR = $(AR) $(ARFLAGS)
libnetwork_a_LIBADD =
am__dirstamp = $(am__leading_dot)dirstamp
am_libnetwork_a_OBJECTS = ./netif/ethernetif.$(OBJEXT) \
	./netif/slipif.$(OBJEXT) ./netif/etharp.$(OBJEXT) \
	./core/dns.$(OBJEXT) ./core/pbuf.$(OBJEXT) \
	./core/def.$(OBJEXT) ./core/stats.$(OBJEXT) \
	./core/sys.$(OBJEXT) ./core/memp.$(OBJEXT) \
	./core/icmp.$(OBJEXT) ./core/ip_frag.$(OBJEXT) \
	./core/ip.$(OBJEXT) ./core/inet.$(OBJEXT) ./core/udp.$(OBJEXT) \
	./core/tcp_out.$(OBJEXT) ./core/inet_chksum.$(OBJEXT) \
	./core/init.$(OBJEXT) ./core/ip_addr.$(OBJEXT) \
	./core/timers.$(OBJEXT) ./core/netif.$(OBJEXT) \
	./core/mem.$(OBJEXT) ./core/raw.$(OBJEXT) \
	./core/dhcp.$(OBJEXT) ./core/tcp.$(OBJEXT) \
	./core/autoip.$(OBJEXT) ./core/tcp_in.$(OBJEXT) \
	./core/igmp.$(OBJEXT) ./arch/sys_arch.$(OBJEXT) \
	./api/tcpip.$(OBJEXT) ./api/netbuf.$(OBJEXT) \
	./api/err.$(OBJEXT) ./api/netdb.$(OBJEXT) \
	./api/api_msg.$(OBJEXT) ./api/api_lib.$(OBJEXT) \
	./api/sockets.$(OBJEXT) ./api/netifapi.$(OBJEXT) \
	./ethernet/ethentry.$(OBJEXT) ./ethernet/ethif.$(OBJEXT)
libnetwork_a_OBJECTS = $(am_libnetwork_a_OBJECTS)
AM_V_P = $(am__v_P_$(V))
am__v_P_ = $(am__v_P_$(AM_DEFAULT_VERBOSITY))
am__v_P_0 = false
am__v_P_1 = :
AM_V_GEN = $(am__v_GEN_$(V))
am__v_GEN_ = $(am__v_GEN_$(AM_DEFAULT_VERBOSITY))
am__v_GEN_0 = @echo "  GEN     " $@;
am__v_GEN_1 = 
AM_V_at = $(am__v_at_$(V))
am__v_at_ = $(am__v_at_$(AM_DEFAULT_VERBOSITY))
am__v_at_0 = @
am__v_at_1 = 
DEFAULT_INCLUDES = -I. -I$(top_builddir)/kernel
depcomp = $(SHELL) $(top_srcdir)/depcomp
am__depfiles_maybe = depfiles
am__mv = mv -f
COMPILE = $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) \
	$(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS)
AM_V_lt = $(am__v_lt_$(V))
am__v_lt_ = $(am__v_lt_$(AM_DEFAULT_VERBOSITY))
am__v_lt_0 = --silent
am__v_lt_1 = 
LTCOMPILE = $(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) \
	$(LIBTOOLFLAGS) --mode=compile $(CC) $(DEFS) \
	$(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) \
	$(AM_CFLAGS) $(CFLAGS)
AM_V_CC = $(am__v_CC_$(V))
am__v_CC_ = $(am__v_CC_$(AM_DEFAULT_VERBOSITY))
am__v_CC_0 = @echo "  CC      " $@;
am__v_CC_1 = 
CCLD = $(CC)
LINK = $(LIBTOOL) $(AM_V_lt) --tag=CC $(AM_LIBTOOLFLAGS) \
	$(LIBTOOLFLAGS) --mode=link $(CCLD) $(AM_CFLAGS) $(CFLAGS) \
	$(AM_LDFLAGS) $(LDFLAGS) -o $@
AM_V_CCLD = $(am__v_CCLD_$(V))
am__v_CCLD_ = $(am__v_CCLD_$(AM_DEFAULT_VERBOSITY))
am__v_CCLD_0 = @echo "  CCLD    " $@;
am__v_CCLD_1 = 
SOURCES = $(libnetwork_a_SOURCES)
DIST_SOURCES = $(libnetwork_a_SOURCES)
am__can_run_installinfo = \
  case $$AM_UPDATE_INFO_DIR in \
    n|no|NO) false;; \
    *) (install-info --version) >/dev/null 2>&1;; \
  esac
am__tagged_files = $(HEADERS) $(SOURCES) $(TAGS_FILES) $(LISP)
# Read a list of newline-separated strings from the standard input,
# and print each of them once, without duplicates.  Input order is
# *not* preserved.
am__uniquify_input = $(AWK) '\
  BEGIN { nonempty = 0; } \
  { items[$$0] = 1; nonempty = 1; } \
  END { if (nonempty) { for (i in items) print i; }; } \
'
# Make sure the list of sources is unique.  This is necessary because,
# e.g., the same source file might be shared among _SOURCES variables
# for different programs/libraries.
am__define_uniq_tagged_files = \
  list='$(am__tagged_files)'; \
  unique=`for i in $$list; do \
    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
  done | $(am__uniquify_input)`
ETAGS = etags
CTAGS = ctags
DISTFILES = $(DIST_COMMON) $(DIST_SOURCES) $(TEXINFOS) $(EXTRA_DIST)
ACLOCAL = ${SHELL} /media/gaojie/Java/hellox/HelloX_OS/missing aclocal-1.14
ALLOCA = 
AMTAR = $${TAR-tar}
AM_DEFAULT_VERBOSITY = 1
AR = ar
AUTOCONF = ${SHELL} /media/gaojie/Java/hellox/HelloX_OS/missing autoconf
AUTOHEADER = ${SHELL} /media/gaojie/Java/hellox/HelloX_OS/missing autoheader
AUTOMAKE = ${SHELL} /media/gaojie/Java/hellox/HelloX_OS/missing automake-1.14
AWK = gawk
CC = gcc
CCAS = gcc
CCASDEPMODE = depmode=gcc3
CCASFLAGS = -g -O2
CCDEPMODE = depmode=gcc3
CFLAGS = -g -O2
CPP = gcc -E
CPPFLAGS = 
CXX = g++
CXXCPP = g++ -E
CXXDEPMODE = depmode=gcc3
CXXFLAGS = -g -O2
CYGPATH_W = echo
DEFS = -DHAVE_CONFIG_H
DEPDIR = .deps
DLLTOOL = false
DSYMUTIL = 
DUMPBIN = 
ECHO_C = 
ECHO_N = -n
ECHO_T = 
EGREP = /bin/grep -E
EXEEXT = 
FGREP = /bin/grep -F
GREP = /bin/grep
INSTALL = /usr/bin/install -c
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_PROGRAM = ${INSTALL}
INSTALL_SCRIPT = ${INSTALL}
INSTALL_STRIP_PROGRAM = $(install_sh) -c -s
LD = /usr/bin/ld -m elf_x86_64
LDFLAGS = 
LIBOBJS = 
LIBS = 
LIBTOOL = $(SHELL) $(top_builddir)/libtool
LIPO = 
LN_S = ln -s
LTLIBOBJS = 
MAKEINFO = ${SHELL} /media/gaojie/Java/hellox/HelloX_OS/missing makeinfo
MANIFEST_TOOL = :
MKDIR_P = /bin/mkdir -p
NM = /usr/bin/nm -B
NMEDIT = 
OBJDUMP = objdump
OBJEXT = o
OTOOL = 
OTOOL64 = 
PACKAGE = hellox
PACKAGE_BUGREPORT = BUG-REPORT-ADDRESS
PACKAGE_NAME = HelloX
PACKAGE_STRING = HelloX 1.78
PACKAGE_TARNAME = hellox
PACKAGE_URL = 
PACKAGE_VERSION = 1.78
PATH_SEPARATOR = :
RANLIB = ranlib
SED = /bin/sed
SET_MAKE = 
SHELL = /bin/bash
STRIP = strip
VERSION = 1.78
abs_builddir = /media/gaojie/Java/hellox/HelloX_OS/kernel/network
abs_srcdir = /media/gaojie/Java/hellox/HelloX_OS/kernel/network
abs_top_builddir = /media/gaojie/Java/hellox/HelloX_OS
abs_top_srcdir = /media/gaojie/Java/hellox/HelloX_OS
ac_ct_AR = ar
ac_ct_CC = gcc
ac_ct_CXX = g++
ac_ct_DUMPBIN = 
am__include = include
am__leading_dot = .
am__quote = 
am__tar = $${TAR-tar} chof - "$$tardir"
am__untar = $${TAR-tar} xf -
bindir = ${exec_prefix}/bin
build = x86_64-unknown-linux-gnu
build_alias = 
build_cpu = x86_64
build_os = linux-gnu
build_vendor = unknown
builddir = .
cflags = -m32
datadir = ${datarootdir}
datarootdir = ${prefix}/share
docdir = ${datarootdir}/doc/${PACKAGE_TARNAME}
dvidir = ${docdir}
exec_prefix = ${prefix}
host = x86_64-unknown-linux-gnu
host_alias = 
host_cpu = x86_64
host_os = linux-gnu
host_vendor = unknown
htmldir = ${docdir}
hx_arch = arch/x86
hx_drivers = drivers/x86
includedir = ${prefix}/include
infodir = ${datarootdir}/info
install_sh = ${SHELL} /media/gaojie/Java/hellox/HelloX_OS/install-sh
libdir = ${exec_prefix}/lib
libexecdir = ${exec_prefix}/libexec
localedir = ${datarootdir}/locale
localstatedir = ${prefix}/var
mandir = ${datarootdir}/man
mkdir_p = $(MKDIR_P)
oldincludedir = /usr/include
os = HelloX
pdfdir = ${docdir}
prefix = /usr/local
program_transform_name = s,x,x,
psdir = ${docdir}
sbindir = ${exec_prefix}/sbin
sharedstatedir = ${prefix}/com
srcdir = .
sysconfdir = ${prefix}/etc
target_alias = 
top_build_prefix = ../../
top_builddir = ../..
top_srcdir = ../..
AM_CFLAGS = -nostdlib -nostdinc -fno-builtin -m32 -D__GCC__ \
	-D_POSIX_ -D_M_IX86 -DMEM_LIBC_MALLOC \
	-I$(top_srcdir)/kernel/include -I$(top_srcdir)/kernel/config \
	-I$(top_srcdir)/kernel/lib/sys -I$(top_srcdir)/kernel/lib

# AUTOMAKE_OPTIONS = subdir-objects
noinst_LIBRARIES = libnetwork.a
libnetwork_a_SOURCES = ./netif/ethernetif.c \
./netif/slipif.c                             \
./netif/etharp.c                             \
./core/dns.c                                 \
./core/pbuf.c                                \
./core/def.c                                 \
./core/stats.c                               \
./core/sys.c                                 \
./core/memp.c                                \
./core/icmp.c                                \
./core/ip_frag.c                             \
./core/ip.c                                  \
./core/inet.c                                \
./core/udp.c                                 \
./core/tcp_out.c                             \
./core/inet_chksum.c                         \
./core/init.c                                \
./core/ip_addr.c                             \
./core/timers.c                              \
./core/netif.c                               \
./core/mem.c                                 \
./core/raw.c                                 \
./core/dhcp.c                                \
./core/tcp.c                                 \
./core/autoip.c                              \
./core/tcp_in.c                              \
./core/igmp.c                                \
./arch/sys_arch.c                            \
./api/tcpip.c                                \
./api/netbuf.c                               \
./api/err.c                                  \
./api/netdb.c                                \
./api/api_msg.c                              \
./api/api_lib.c                              \
./api/sockets.c                              \
./api/netifapi.c                             \
./ethernet/ethentry.c                        \
./ethernet/ethif.c

all: all-am

.SUFFIXES:
.SUFFIXES: .c .lo .o .obj
$(srcdir)/Makefile.in:  $(srcdir)/Makefile.am $(top_srcdir)/kernel/kernel.mk $(am__configure_deps)
	@for dep in $?; do \
	  case '$(am__configure_deps)' in \
	    *$$dep*) \
	      ( cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh ) \
	        && { if test -f $@; then exit 0; else break; fi; }; \
	      exit 1;; \
	  esac; \
	done; \
	echo ' cd $(top_srcdir) && $(AUTOMAKE) --foreign kernel/network/Makefile'; \
	$(am__cd) $(top_srcdir) && \
	  $(AUTOMAKE) --foreign kernel/network/Makefile
.PRECIOUS: Makefile
Makefile: $(srcdir)/Makefile.in $(top_builddir)/config.status
	@case '$?' in \
	  *config.status*) \
	    cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh;; \
	  *) \
	    echo ' cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe)'; \
	    cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe);; \
	esac;
$(top_srcdir)/kernel/kernel.mk:

$(top_builddir)/config.status: $(top_srcdir)/configure $(CONFIG_STATUS_DEPENDENCIES)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh

$(top_srcdir)/configure:  $(am__configure_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(ACLOCAL_M4):  $(am__aclocal_m4_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(am__aclocal_m4_deps):

clean-noinstLIBRARIES:
	-test -z "$(noinst_LIBRARIES)" || rm -f $(noinst_LIBRARIES)
netif/$(am__dirstamp):
	@$(MKDIR_P) ./netif
	@: > netif/$(am__dirstamp)
netif/$(DEPDIR)/$(am__dirstamp):
	@$(MKDIR_P) ./netif/$(DEPDIR)
	@: > netif/$(DEPDIR)/$(am__dirstamp)
./netif/ethernetif.$(OBJEXT): netif/$(am__dirstamp) \
	netif/$(DEPDIR)/$(am__dirstamp)
./netif/slipif.$(OBJEXT): netif/$(am__dirstamp) \
	netif/$(DEPDIR)/$(am__dirstamp)
./netif/etharp.$(OBJEXT): netif/$(am__dirstamp) \
	netif/$(DEPDIR)/$(am__dirstamp)
core/$(am__dirstamp):
	@$(MKDIR_P) ./core
	@: > core/$(am__dirstamp)
core/$(DEPDIR)/$(am__dirstamp):
	@$(MKDIR_P) ./core/$(DEPDIR)
	@: > core/$(DEPDIR)/$(am__dirstamp)
./core/dns.$(OBJEXT): core/$(am__dirstamp) \
	core/$(DEPDIR)/$(am__dirstamp)
./core/pbuf.$(OBJEXT): core/$(am__dirstamp) \
	core/$(DEPDIR)/$(am__dirstamp)
./core/def.$(OBJEXT): core/$(am__dirstamp) \
	core/$(DEPDIR)/$(am__dirstamp)
./core/stats.$(OBJEXT): core/$(am__dirstamp) \
	core/$(DEPDIR)/$(am__dirstamp)
./core/sys.$(OBJEXT): core/$(am__dirstamp) \
	core/$(DEPDIR)/$(am__dirstamp)
./core/memp.$(OBJEXT): core/$(am__dirstamp) \
	core/$(DEPDIR)/$(am__dirstamp)
./core/icmp.$(OBJEXT): core/$(am__dirstamp) \
	core/$(DEPDIR)/$(am__dirstamp)
./core/ip_frag.$(OBJEXT): core/$(am__dirstamp) \
	core/$(DEPDIR)/$(am__dirstamp)
./core/ip.$(OBJEXT): core/$(am__dirstamp) \
	core/$(DEPDIR)/$(am__dirstamp)
./core/inet.$(OBJEXT): core/$(am__dirstamp) \
	core/$(DEPDIR)/$(am__dirstamp)
./core/udp.$(OBJEXT): core/$(am__dirstamp) \
	core/$(DEPDIR)/$(am__dirstamp)
./core/tcp_out.$(OBJEXT): core/$(am__dirstamp) \
	core/$(DEPDIR)/$(am__dirstamp)
./core/inet_chksum.$(OBJEXT): core/$(am__dirstamp) \
	core/$(DEPDIR)/$(am__dirstamp)
./core/init.$(OBJEXT): core/$(am__dirstamp) \
	core/$(DEPDIR)/$(am__dirstamp)
./core/ip_addr.$(OBJEXT): core/$(am__dirstamp) \
	core/$(DEPDIR)/$(am__dirstamp)
./core/timers.$(OBJEXT): core/$(am__dirstamp) \
	core/$(DEPDIR)/$(am__dirstamp)
./core/netif.$(OBJEXT): core/$(am__dirstamp) \
	core/$(DEPDIR)/$(am__dirstamp)
./core/mem.$(OBJEXT): core/$(am__dirstamp) \
	core/$(DEPDIR)/$(am__dirstamp)
./core/raw.$(OBJEXT): core/$(am__dirstamp) \
	core/$(DEPDIR)/$(am__dirstamp)
./core/dhcp.$(OBJEXT): core/$(am__dirstamp) \
	core/$(DEPDIR)/$(am__dirstamp)
./core/tcp.$(OBJEXT): core/$(am__dirstamp) \
	core/$(DEPDIR)/$(am__dirstamp)
./core/autoip.$(OBJEXT): core/$(am__dirstamp) \
	core/$(DEPDIR)/$(am__dirstamp)
./core/tcp_in.$(OBJEXT): core/$(am__dirstamp) \
	core/$(DEPDIR)/$(am__dirstamp)
./core/igmp.$(OBJEXT): core/$(am__dirstamp) \
	core/$(DEPDIR)/$(am__dirstamp)
arch/$(am__dirstamp):
	@$(MKDIR_P) ./arch
	@: > arch/$(am__dirstamp)
arch/$(DEPDIR)/$(am__dirstamp):
	@$(MKDIR_P) ./arch/$(DEPDIR)
	@: > arch/$(DEPDIR)/$(am__dirstamp)
./arch/sys_arch.$(OBJEXT): arch/$(am__dirstamp) \
	arch/$(DEPDIR)/$(am__dirstamp)
api/$(am__dirstamp):
	@$(MKDIR_P) ./api
	@: > api/$(am__dirstamp)
api/$(DEPDIR)/$(am__dirstamp):
	@$(MKDIR_P) ./api/$(DEPDIR)
	@: > api/$(DEPDIR)/$(am__dirstamp)
./api/tcpip.$(OBJEXT): api/$(am__dirstamp) \
	api/$(DEPDIR)/$(am__dirstamp)
./api/netbuf.$(OBJEXT): api/$(am__dirstamp) \
	api/$(DEPDIR)/$(am__dirstamp)
./api/err.$(OBJEXT): api/$(am__dirstamp) api/$(DEPDIR)/$(am__dirstamp)
./api/netdb.$(OBJEXT): api/$(am__dirstamp) \
	api/$(DEPDIR)/$(am__dirstamp)
./api/api_msg.$(OBJEXT): api/$(am__dirstamp) \
	api/$(DEPDIR)/$(am__dirstamp)
./api/api_lib.$(OBJEXT): api/$(am__dirstamp) \
	api/$(DEPDIR)/$(am__dirstamp)
./api/sockets.$(OBJEXT): api/$(am__dirstamp) \
	api/$(DEPDIR)/$(am__dirstamp)
./api/netifapi.$(OBJEXT): api/$(am__dirstamp) \
	api/$(DEPDIR)/$(am__dirstamp)
ethernet/$(am__dirstamp):
	@$(MKDIR_P) ./ethernet
	@: > ethernet/$(am__dirstamp)
ethernet/$(DEPDIR)/$(am__dirstamp):
	@$(MKDIR_P) ./ethernet/$(DEPDIR)
	@: > ethernet/$(DEPDIR)/$(am__dirstamp)
./ethernet/ethentry.$(OBJEXT): ethernet/$(am__dirstamp) \
	ethernet/$(DEPDIR)/$(am__dirstamp)
./ethernet/ethif.$(OBJEXT): ethernet/$(am__dirstamp) \
	ethernet/$(DEPDIR)/$(am__dirstamp)

libnetwork.a: $(libnetwork_a_OBJECTS) $(libnetwork_a_DEPENDENCIES) $(EXTRA_libnetwork_a_DEPENDENCIES) 
	$(AM_V_at)-rm -f libnetwork.a
	$(AM_V_AR)$(libnetwork_a_AR) libnetwork.a $(libnetwork_a_OBJECTS) $(libnetwork_a_LIBADD)
	$(AM_V_at)$(RANLIB) libnetwork.a

mostlyclean-compile:
	-rm -f *.$(OBJEXT)
	-rm -f ./api/*.$(OBJEXT)
	-rm -f ./arch/*.$(OBJEXT)
	-rm -f ./core/*.$(OBJEXT)
	-rm -f ./ethernet/*.$(OBJEXT)
	-rm -f ./netif/*.$(OBJEXT)

distclean-compile:
	-rm -f *.tab.c

include ./api/$(DEPDIR)/api_lib.Po
include ./api/$(DEPDIR)/api_msg.Po
include ./api/$(DEPDIR)/err.Po
include ./api/$(DEPDIR)/netbuf.Po
include ./api/$(DEPDIR)/netdb.Po
include ./api/$(DEPDIR)/netifapi.Po
include ./api/$(DEPDIR)/sockets.Po
include ./api/$(DEPDIR)/tcpip.Po
include ./arch/$(DEPDIR)/sys_arch.Po
include ./core/$(DEPDIR)/autoip.Po
include ./core/$(DEPDIR)/def.Po
include ./core/$(DEPDIR)/dhcp.Po
include ./core/$(DEPDIR)/dns.Po
include ./core/$(DEPDIR)/icmp.Po
include ./core/$(DEPDIR)/igmp.Po
include ./core/$(DEPDIR)/inet.Po
include ./core/$(DEPDIR)/inet_chksum.Po
include ./core/$(DEPDIR)/init.Po
include ./core/$(DEPDIR)/ip.Po
include ./core/$(DEPDIR)/ip_addr.Po
include ./core/$(DEPDIR)/ip_frag.Po
include ./core/$(DEPDIR)/mem.Po
include ./core/$(DEPDIR)/memp.Po
include ./core/$(DEPDIR)/netif.Po
include ./core/$(DEPDIR)/pbuf.Po
include ./core/$(DEPDIR)/raw.Po
include ./core/$(DEPDIR)/stats.Po
include ./core/$(DEPDIR)/sys.Po
include ./core/$(DEPDIR)/tcp.Po
include ./core/$(DEPDIR)/tcp_in.Po
include ./core/$(DEPDIR)/tcp_out.Po
include ./core/$(DEPDIR)/timers.Po
include ./core/$(DEPDIR)/udp.Po
include ./ethernet/$(DEPDIR)/ethentry.Po
include ./ethernet/$(DEPDIR)/ethif.Po
include ./netif/$(DEPDIR)/etharp.Po
include ./netif/$(DEPDIR)/ethernetif.Po
include ./netif/$(DEPDIR)/slipif.Po

.c.o:
	$(AM_V_CC)depbase=`echo $@ | sed 's|[^/]*$$|$(DEPDIR)/&|;s|\.o$$||'`;\
	$(COMPILE) -MT $@ -MD -MP -MF $$depbase.Tpo -c -o $@ $< &&\
	$(am__mv) $$depbase.Tpo $$depbase.Po
#	$(AM_V_CC)source='$<' object='$@' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(AM_V_CC_no)$(COMPILE) -c -o $@ $<

.c.obj:
	$(AM_V_CC)depbase=`echo $@ | sed 's|[^/]*$$|$(DEPDIR)/&|;s|\.obj$$||'`;\
	$(COMPILE) -MT $@ -MD -MP -MF $$depbase.Tpo -c -o $@ `$(CYGPATH_W) '$<'` &&\
	$(am__mv) $$depbase.Tpo $$depbase.Po
#	$(AM_V_CC)source='$<' object='$@' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(AM_V_CC_no)$(COMPILE) -c -o $@ `$(CYGPATH_W) '$<'`

.c.lo:
	$(AM_V_CC)depbase=`echo $@ | sed 's|[^/]*$$|$(DEPDIR)/&|;s|\.lo$$||'`;\
	$(LTCOMPILE) -MT $@ -MD -MP -MF $$depbase.Tpo -c -o $@ $< &&\
	$(am__mv) $$depbase.Tpo $$depbase.Plo
#	$(AM_V_CC)source='$<' object='$@' libtool=yes \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(AM_V_CC_no)$(LTCOMPILE) -c -o $@ $<

mostlyclean-libtool:
	-rm -f *.lo

clean-libtool:
	-rm -rf .libs _libs

ID: $(am__tagged_files)
	$(am__define_uniq_tagged_files); mkid -fID $$unique
tags: tags-am
TAGS: tags

tags-am: $(TAGS_DEPENDENCIES) $(am__tagged_files)
	set x; \
	here=`pwd`; \
	$(am__define_uniq_tagged_files); \
	shift; \
	if test -z "$(ETAGS_ARGS)$$*$$unique"; then :; else \
	  test -n "$$unique" || unique=$$empty_fix; \
	  if test $$# -gt 0; then \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      "$$@" $$unique; \
	  else \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      $$unique; \
	  fi; \
	fi
ctags: ctags-am

CTAGS: ctags
ctags-am: $(TAGS_DEPENDENCIES) $(am__tagged_files)
	$(am__define_uniq_tagged_files); \
	test -z "$(CTAGS_ARGS)$$unique" \
	  || $(CTAGS) $(CTAGSFLAGS) $(AM_CTAGSFLAGS) $(CTAGS_ARGS) \
	     $$unique

GTAGS:
	here=`$(am__cd) $(top_builddir) && pwd` \
	  && $(am__cd) $(top_srcdir) \
	  && gtags -i $(GTAGS_ARGS) "$$here"
cscopelist: cscopelist-am

cscopelist-am: $(am__tagged_files)
	list='$(am__tagged_files)'; \
	case "$(srcdir)" in \
	  [\\/]* | ?:[\\/]*) sdir="$(srcdir)" ;; \
	  *) sdir=$(subdir)/$(srcdir) ;; \
	esac; \
	for i in $$list; do \
	  if test -f "$$i"; then \
	    echo "$(subdir)/$$i"; \
	  else \
	    echo "$$sdir/$$i"; \
	  fi; \
	done >> $(top_builddir)/cscope.files

distclean-tags:
	-rm -f TAGS ID GTAGS GRTAGS GSYMS GPATH tags

distdir: $(DISTFILES)
	@srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	topsrcdirstrip=`echo "$(top_srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	list='$(DISTFILES)'; \
	  dist_files=`for file in $$list; do echo $$file; done | \
	  sed -e "s|^$$srcdirstrip/||;t" \
	      -e "s|^$$topsrcdirstrip/|$(top_builddir)/|;t"`; \
	case $$dist_files in \
	  */*) $(MKDIR_P) `echo "$$dist_files" | \
			   sed '/\//!d;s|^|$(distdir)/|;s,/[^/]*$$,,' | \
			   sort -u` ;; \
	esac; \
	for file in $$dist_files; do \
	  if test -f $$file || test -d $$file; then d=.; else d=$(srcdir); fi; \
	  if test -d $$d/$$file; then \
	    dir=`echo "/$$file" | sed -e 's,/[^/]*$$,,'`; \
	    if test -d "$(distdir)/$$file"; then \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    if test -d $(srcdir)/$$file && test $$d != $(srcdir); then \
	      cp -fpR $(srcdir)/$$file "$(distdir)$$dir" || exit 1; \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    cp -fpR $$d/$$file "$(distdir)$$dir" || exit 1; \
	  else \
	    test -f "$(distdir)/$$file" \
	    || cp -p $$d/$$file "$(distdir)/$$file" \
	    || exit 1; \
	  fi; \
	done
check-am: all-am
check: check-am
all-am: Makefile $(LIBRARIES)
installdirs:
install: install-am
install-exec: install-exec-am
install-data: install-data-am
uninstall: uninstall-am

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am

installcheck: installcheck-am
install-strip:
	if test -z '$(STRIP)'; then \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	      install; \
	else \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	    "INSTALL_PROGRAM_ENV=STRIPPROG='$(STRIP)'" install; \
	fi
mostlyclean-generic:

clean-generic:

distclean-generic:
	-test -z "$(CONFIG_CLEAN_FILES)" || rm -f $(CONFIG_CLEAN_FILES)
	-test . = "$(srcdir)" || test -z "$(CONFIG_CLEAN_VPATH_FILES)" || rm -f $(CONFIG_CLEAN_VPATH_FILES)
	-rm -f api/$(DEPDIR)/$(am__dirstamp)
	-rm -f api/$(am__dirstamp)
	-rm -f arch/$(DEPDIR)/$(am__dirstamp)
	-rm -f arch/$(am__dirstamp)
	-rm -f core/$(DEPDIR)/$(am__dirstamp)
	-rm -f core/$(am__dirstamp)
	-rm -f ethernet/$(DEPDIR)/$(am__dirstamp)
	-rm -f ethernet/$(am__dirstamp)
	-rm -f netif/$(DEPDIR)/$(am__dirstamp)
	-rm -f netif/$(am__dirstamp)

maintainer-clean-generic:
	@echo "This command is intended for maintainers to use"
	@echo "it deletes files that may require special tools to rebuild."
clean: clean-am

clean-am: clean-generic clean-libtool clean-noinstLIBRARIES \
	mostlyclean-am

distclean: distclean-am
	-rm -rf ./api/$(DEPDIR) ./arch/$(DEPDIR) ./core/$(DEPDIR) ./ethernet/$(DEPDIR) ./netif/$(DEPDIR)
	-rm -f Makefile
distclean-am: clean-am distclean-compile distclean-generic \
	distclean-tags

dvi: dvi-am

dvi-am:

html: html-am

html-am:

info: info-am

info-am:

install-data-am:

install-dvi: install-dvi-am

install-dvi-am:

install-exec-am:

install-html: install-html-am

install-html-am:

install-info: install-info-am

install-info-am:

install-man:

install-pdf: install-pdf-am

install-pdf-am:

install-ps: install-ps-am

install-ps-am:

installcheck-am:

maintainer-clean: maintainer-clean-am
	-rm -rf ./api/$(DEPDIR) ./arch/$(DEPDIR) ./core/$(DEPDIR) ./ethernet/$(DEPDIR) ./netif/$(DEPDIR)
	-rm -f Makefile
maintainer-clean-am: distclean-am maintainer-clean-generic

mostlyclean: mostlyclean-am

mostlyclean-am: mostlyclean-compile mostlyclean-generic \
	mostlyclean-libtool

pdf: pdf-am

pdf-am:

ps: ps-am

ps-am:

uninstall-am:

.MAKE: install-am install-strip

.PHONY: CTAGS GTAGS TAGS all all-am check check-am clean clean-generic \
	clean-libtool clean-noinstLIBRARIES cscopelist-am ctags \
	ctags-am distclean distclean-compile distclean-generic \
	distclean-libtool distclean-tags distdir dvi dvi-am html \
	html-am info info-am install install-am install-data \
	install-data-am install-dvi install-dvi-am install-exec \
	install-exec-am install-html install-html-am install-info \
	install-info-am install-man install-pdf install-pdf-am \
	install-ps install-ps-am install-strip installcheck \
	installcheck-am installdirs maintainer-clean \
	maintainer-clean-generic mostlyclean mostlyclean-compile \
	mostlyclean-generic mostlyclean-libtool pdf pdf-am ps ps-am \
	tags tags-am uninstall uninstall-am


# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
