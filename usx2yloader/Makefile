# Makefile.in generated by automake 1.7.6 from Makefile.am.
# usx2yloader/Makefile.  Generated from Makefile.in by configure.

# Copyright 1994, 1995, 1996, 1997, 1998, 1999, 2000, 2001, 2002, 2003
# Free Software Foundation, Inc.
# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.



srcdir = .
top_srcdir = ..

pkgdatadir = $(datadir)/alsa-firmware
pkglibdir = $(libdir)/alsa-firmware
pkgincludedir = $(includedir)/alsa-firmware
top_builddir = ..

am__cd = CDPATH="$${ZSH_VERSION+.}$(PATH_SEPARATOR)" && cd
INSTALL = .././install-sh -c
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
ACLOCAL = ${SHELL} /storage/emulated/0/Android/data/me.sheimi.sgit/files/repo/alsa-firmware-1.0.9/missing --run aclocal-1.7
AMDEP_FALSE = #
AMDEP_TRUE = 
AMTAR = ${SHELL} /storage/emulated/0/Android/data/me.sheimi.sgit/files/repo/alsa-firmware-1.0.9/missing --run tar
AS31 = 
AS31_FLAGS = -Fhex
AUTOCONF = ${SHELL} /storage/emulated/0/Android/data/me.sheimi.sgit/files/repo/alsa-firmware-1.0.9/missing --run autoconf
AUTOHEADER = ${SHELL} /storage/emulated/0/Android/data/me.sheimi.sgit/files/repo/alsa-firmware-1.0.9/missing --run autoheader
AUTOMAKE = ${SHELL} /storage/emulated/0/Android/data/me.sheimi.sgit/files/repo/alsa-firmware-1.0.9/missing --run automake-1.7
AWK = awk
BUILD_FW_FALSE = 
BUILD_FW_TRUE = #
CC = gcc
CCDEPMODE = depmode=gcc3
CFLAGS = -Os -s 
CPP = gcc -E
CPPFLAGS = 
CYGPATH_W = echo
DEFS = -DPACKAGE_NAME=\"\" -DPACKAGE_TARNAME=\"\" -DPACKAGE_VERSION=\"\" -DPACKAGE_STRING=\"\" -DPACKAGE_BUGREPORT=\"\" -DPACKAGE=\"alsa-firmware\" -DVERSION=\"1.0.9\" -DSTDC_HEADERS=1 
DEPDIR = .deps
ECHO_C = \c
ECHO_N = 
ECHO_T = 
EGREP = grep -E
EXEEXT = 
HOTPLUGFWDIR = /usr/lib/hotplug/firmware
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_PROGRAM = ${INSTALL}
INSTALL_SCRIPT = ${INSTALL}
INSTALL_STRIP_PROGRAM = ${SHELL} $(install_sh) -c -s
LDFLAGS = 
LIBOBJS = 
LIBS = 
LTLIBOBJS = 
MAKEINFO = ${SHELL} /storage/emulated/0/Android/data/me.sheimi.sgit/files/repo/alsa-firmware-1.0.9/missing --run makeinfo
OBJEXT = o
PACKAGE = alsa-firmware
PACKAGE_BUGREPORT = 
PACKAGE_NAME = 
PACKAGE_STRING = 
PACKAGE_TARNAME = 
PACKAGE_VERSION = 
PATH_SEPARATOR = :
SET_MAKE = 
SHELL = sh
STRIP = strip
USE_HOTPLUG_FALSE = #
USE_HOTPLUG_TRUE = 
USE_LOADER_FALSE = #
USE_LOADER_TRUE = 
VERSION = 1.0.9
ac_ct_CC = gcc
ac_ct_STRIP = strip
am__fastdepCC_FALSE = #
am__fastdepCC_TRUE = 
am__include = include
am__leading_dot = .
am__quote = 
bindir = ${exec_prefix}/bin
build_alias = i686
datadir = ${prefix}/share
exec_prefix = ${prefix}
host_alias = -h
includedir = ${prefix}/include
infodir = ${prefix}/info
install_sh = /storage/emulated/0/Android/data/me.sheimi.sgit/files/repo/alsa-firmware-1.0.9/install-sh
libdir = ${exec_prefix}/lib
libexecdir = ${exec_prefix}/libexec
localstatedir = ${prefix}/var
mandir = ${prefix}/man
oldincludedir = /usr/include
prefix = /usr/local
program_transform_name = s,x,x,
sbindir = ${exec_prefix}/sbin
sharedstatedir = ${prefix}/com
sysconfdir = ${prefix}/etc
target_alias = 
MYNAME = usx2yloader

cfg_files = us122.conf us224.conf us428.conf \
		us122.prepad us224.prepad us428.prepad \
		us122.rbt us224.rbt us428.rbt \
		tascam_loader.ihx \
		us122fw.ihx us224fw.ihx us428fw.ihx


#bin_SCRIPTS = tascam_loader

EXTRA_DIST = $(cfg_files) \
	tascam_loader.asm \
	an2131.asm


firmwaredir = $(datadir)/alsa/firmware/$(MYNAME)
firmware_DATA = $(cfg_files)
subdir = usx2yloader
ACLOCAL_M4 = $(top_srcdir)/aclocal.m4
mkinstalldirs = $(SHELL) $(top_srcdir)/mkinstalldirs
CONFIG_CLEAN_FILES =
SCRIPTS = $(bin_SCRIPTS)

DIST_SOURCES =
DATA = $(firmware_DATA)

DIST_COMMON = README Makefile.am Makefile.in
all: all-am

.SUFFIXES:
$(srcdir)/Makefile.in:  Makefile.am  $(top_srcdir)/configure.in $(ACLOCAL_M4)
	cd $(top_srcdir) && \
	  $(AUTOMAKE) --foreign  usx2yloader/Makefile
Makefile:  $(srcdir)/Makefile.in  $(top_builddir)/config.status
	cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe)
binSCRIPT_INSTALL = $(INSTALL_SCRIPT)
install-binSCRIPTS: $(bin_SCRIPTS)
	@$(NORMAL_INSTALL)
	$(mkinstalldirs) $(DESTDIR)$(bindir)
	@list='$(bin_SCRIPTS)'; for p in $$list; do \
	  if test -f "$$p"; then d=; else d="$(srcdir)/"; fi; \
	  if test -f $$d$$p; then \
	    f=`echo "$$p" | sed 's|^.*/||;$(transform)'`; \
	    echo " $(binSCRIPT_INSTALL) $$d$$p $(DESTDIR)$(bindir)/$$f"; \
	    $(binSCRIPT_INSTALL) $$d$$p $(DESTDIR)$(bindir)/$$f; \
	  else :; fi; \
	done

uninstall-binSCRIPTS:
	@$(NORMAL_UNINSTALL)
	@list='$(bin_SCRIPTS)'; for p in $$list; do \
	  f=`echo "$$p" | sed 's|^.*/||;$(transform)'`; \
	  echo " rm -f $(DESTDIR)$(bindir)/$$f"; \
	  rm -f $(DESTDIR)$(bindir)/$$f; \
	done
uninstall-info-am:
firmwareDATA_INSTALL = $(INSTALL_DATA)
install-firmwareDATA: $(firmware_DATA)
	@$(NORMAL_INSTALL)
	$(mkinstalldirs) $(DESTDIR)$(firmwaredir)
	@list='$(firmware_DATA)'; for p in $$list; do \
	  if test -f "$$p"; then d=; else d="$(srcdir)/"; fi; \
	  f="`echo $$p | sed -e 's|^.*/||'`"; \
	  echo " $(firmwareDATA_INSTALL) $$d$$p $(DESTDIR)$(firmwaredir)/$$f"; \
	  $(firmwareDATA_INSTALL) $$d$$p $(DESTDIR)$(firmwaredir)/$$f; \
	done

uninstall-firmwareDATA:
	@$(NORMAL_UNINSTALL)
	@list='$(firmware_DATA)'; for p in $$list; do \
	  f="`echo $$p | sed -e 's|^.*/||'`"; \
	  echo " rm -f $(DESTDIR)$(firmwaredir)/$$f"; \
	  rm -f $(DESTDIR)$(firmwaredir)/$$f; \
	done
tags: TAGS
TAGS:

ctags: CTAGS
CTAGS:

DISTFILES = $(DIST_COMMON) $(DIST_SOURCES) $(TEXINFOS) $(EXTRA_DIST)

top_distdir = ..
distdir = $(top_distdir)/$(PACKAGE)-$(VERSION)

distdir: $(DISTFILES)
	@srcdirstrip=`echo "$(srcdir)" | sed 's|.|.|g'`; \
	topsrcdirstrip=`echo "$(top_srcdir)" | sed 's|.|.|g'`; \
	list='$(DISTFILES)'; for file in $$list; do \
	  case $$file in \
	    $(srcdir)/*) file=`echo "$$file" | sed "s|^$$srcdirstrip/||"`;; \
	    $(top_srcdir)/*) file=`echo "$$file" | sed "s|^$$topsrcdirstrip/|$(top_builddir)/|"`;; \
	  esac; \
	  if test -f $$file || test -d $$file; then d=.; else d=$(srcdir); fi; \
	  dir=`echo "$$file" | sed -e 's,/[^/]*$$,,'`; \
	  if test "$$dir" != "$$file" && test "$$dir" != "."; then \
	    dir="/$$dir"; \
	    $(mkinstalldirs) "$(distdir)$$dir"; \
	  else \
	    dir=''; \
	  fi; \
	  if test -d $$d/$$file; then \
	    if test -d $(srcdir)/$$file && test $$d != $(srcdir); then \
	      cp -pR $(srcdir)/$$file $(distdir)$$dir || exit 1; \
	    fi; \
	    cp -pR $$d/$$file $(distdir)$$dir || exit 1; \
	  else \
	    test -f $(distdir)/$$file \
	    || cp -p $$d/$$file $(distdir)/$$file \
	    || exit 1; \
	  fi; \
	done
check-am: all-am
check: check-am
all-am: Makefile $(SCRIPTS) $(DATA)

installdirs:
	$(mkinstalldirs) $(DESTDIR)$(bindir) $(DESTDIR)$(firmwaredir)
install: install-am
install-exec: install-exec-am
install-data: install-data-am
uninstall: uninstall-am

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am

installcheck: installcheck-am
install-strip:
	$(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	  INSTALL_STRIP_FLAG=-s \
	  `test -z '$(STRIP)' || \
	    echo "INSTALL_PROGRAM_ENV=STRIPPROG='$(STRIP)'"` install
mostlyclean-generic:

clean-generic:

distclean-generic:
	-rm -f Makefile $(CONFIG_CLEAN_FILES)

maintainer-clean-generic:
	@echo "This command is intended for maintainers to use"
	@echo "it deletes files that may require special tools to rebuild."
clean: clean-am

clean-am: clean-generic mostlyclean-am

distclean: distclean-am

distclean-am: clean-am distclean-generic

dvi: dvi-am

dvi-am:

info: info-am

info-am:

install-data-am: install-firmwareDATA

install-exec-am: install-binSCRIPTS

install-info: install-info-am

install-man:

installcheck-am:

maintainer-clean: maintainer-clean-am

maintainer-clean-am: distclean-am maintainer-clean-generic

mostlyclean: mostlyclean-am

mostlyclean-am: mostlyclean-generic

pdf: pdf-am

pdf-am:

ps: ps-am

ps-am:

uninstall-am: uninstall-binSCRIPTS uninstall-firmwareDATA \
	uninstall-info-am

.PHONY: all all-am check check-am clean clean-generic distclean \
	distclean-generic distdir dvi dvi-am info info-am install \
	install-am install-binSCRIPTS install-data install-data-am \
	install-exec install-exec-am install-firmwareDATA install-info \
	install-info-am install-man install-strip installcheck \
	installcheck-am installdirs maintainer-clean \
	maintainer-clean-generic mostlyclean mostlyclean-generic pdf \
	pdf-am ps ps-am uninstall uninstall-am uninstall-binSCRIPTS \
	uninstall-firmwareDATA uninstall-info-am

#tascam_loader: 
#	$(AS31) $(AS31_FLAGS) -s tascam_loader.asm > tascam_loader.ihx
# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
