
SHELL = /bin/sh

# V=0 quiet, V=1 verbose.  other values don't work.
V = 0
Q1 = $(V:1=)
Q = $(Q1:0=@)
ECHO1 = $(V:1=@ :)
ECHO = $(ECHO1:0=@ echo)
NULLCMD = :

#### Start of system configuration section. ####

srcdir = .
topdir = /Users/tanvirmahdad/.rvm/rubies/ruby-2.4.1/include/ruby-2.4.0
hdrdir = $(topdir)
arch_hdrdir = /Users/tanvirmahdad/.rvm/rubies/ruby-2.4.1/include/ruby-2.4.0/x86_64-darwin18
PATH_SEPARATOR = :
VPATH = $(srcdir):$(arch_hdrdir)/ruby:$(hdrdir)/ruby
prefix = $(DESTDIR)/Users/tanvirmahdad/.rvm/rubies/ruby-2.4.1
rubysitearchprefix = $(rubylibprefix)/$(sitearch)
rubyarchprefix = $(rubylibprefix)/$(arch)
rubylibprefix = $(libdir)/$(RUBY_BASE_NAME)
exec_prefix = $(prefix)
vendorarchhdrdir = $(vendorhdrdir)/$(sitearch)
sitearchhdrdir = $(sitehdrdir)/$(sitearch)
rubyarchhdrdir = $(rubyhdrdir)/$(arch)
vendorhdrdir = $(rubyhdrdir)/vendor_ruby
sitehdrdir = $(rubyhdrdir)/site_ruby
rubyhdrdir = $(includedir)/$(RUBY_VERSION_NAME)
vendorarchdir = $(vendorlibdir)/$(sitearch)
vendorlibdir = $(vendordir)/$(ruby_version)
vendordir = $(rubylibprefix)/vendor_ruby
sitearchdir = $(DESTDIR)./.gem.20220314-35496-1ri18yb
sitelibdir = $(DESTDIR)./.gem.20220314-35496-1ri18yb
sitedir = $(rubylibprefix)/site_ruby
rubyarchdir = $(rubylibdir)/$(arch)
rubylibdir = $(rubylibprefix)/$(ruby_version)
sitearchincludedir = $(includedir)/$(sitearch)
archincludedir = $(includedir)/$(arch)
sitearchlibdir = $(libdir)/$(sitearch)
archlibdir = $(libdir)/$(arch)
ridir = $(datarootdir)/$(RI_BASE_NAME)
mandir = $(datarootdir)/man
localedir = $(datarootdir)/locale
libdir = $(exec_prefix)/lib
psdir = $(docdir)
pdfdir = $(docdir)
dvidir = $(docdir)
htmldir = $(docdir)
infodir = $(datarootdir)/info
docdir = $(datarootdir)/doc/$(PACKAGE)
oldincludedir = $(SDKROOT)/usr/include
includedir = $(prefix)/include
localstatedir = $(prefix)/var
sharedstatedir = $(prefix)/com
sysconfdir = $(prefix)/etc
datadir = $(datarootdir)
datarootdir = $(prefix)/share
libexecdir = $(exec_prefix)/libexec
sbindir = $(exec_prefix)/sbin
bindir = $(exec_prefix)/bin
archdir = $(rubyarchdir)


CC = gcc
CXX = g++
LIBRUBY = $(LIBRUBY_SO)
LIBRUBY_A = lib$(RUBY_SO_NAME)-static.a
LIBRUBYARG_SHARED = -l$(RUBY_SO_NAME)
LIBRUBYARG_STATIC = -l$(RUBY_SO_NAME)-static -framework CoreFoundation
empty =
OUTFLAG = -o $(empty)
COUTFLAG = -o $(empty)
CSRCFLAG = $(empty)

RUBY_EXTCONF_H = 
cflags   = $(optflags) $(debugflags) $(warnflags)
cxxflags = $(optflags) $(debugflags) $(warnflags)
optflags = -O3 -fno-fast-math
debugflags = -ggdb3
warnflags = -Wall -Wextra -Wno-unused-parameter -Wno-parentheses -Wno-long-long -Wno-missing-field-initializers -Wno-tautological-compare -Wno-parentheses-equality -Wno-constant-logical-operand -Wno-self-assign -Wunused-variable -Wimplicit-int -Wpointer-arith -Wwrite-strings  -Wshorten-64-to-32  -Wdivision-by-zero -Wdeprecated-declarations -Wextra-tokens
CCDLFLAGS = -fno-common
CFLAGS   = $(CCDLFLAGS) $(cflags)  -fno-common -pipe $(ARCH_FLAG)
INCFLAGS = -I. -I$(arch_hdrdir) -I$(hdrdir)/ruby/backward -I$(hdrdir) -I$(srcdir)
DEFS     = 
CPPFLAGS =  -I/usr/local/opt/v8@3.15/include  -I/usr/local/opt/libyaml/include -I/usr/local/opt/libksba/include -I/usr/local/opt/readline/include -I/usr/local/opt/zlib/include -I/usr/local/opt/openssl@1.1/include -D_XOPEN_SOURCE -D_DARWIN_C_SOURCE -D_DARWIN_UNLIMITED_SELECT -D_REENTRANT $(DEFS) $(cppflags) -Wall -g -rdynamic
CXXFLAGS = $(CCDLFLAGS) $(cxxflags) $(ARCH_FLAG)
ldflags  = -L. -fstack-protector -L/usr/local/lib -L/usr/local/opt/libyaml/lib -L/usr/local/opt/libksba/lib -L/usr/local/opt/readline/lib -L/usr/local/opt/zlib/lib -L/usr/local/opt/openssl@1.1/lib
dldflags = -Wl,-undefined,dynamic_lookup -Wl,-multiply_defined,suppress -L/usr/local/opt/libyaml/lib -L/usr/local/opt/libksba/lib -L/usr/local/opt/readline/lib -L/usr/local/opt/zlib/lib -L/usr/local/opt/openssl@1.1/lib 
ARCH_FLAG = 
DLDFLAGS = $(ldflags) $(dldflags) $(ARCH_FLAG)
LDSHARED = $(CC) -dynamic -bundle
LDSHAREDXX = $(CXX) -dynamic -bundle
AR = ar
EXEEXT = 

RUBY_INSTALL_NAME = $(RUBY_BASE_NAME)
RUBY_SO_NAME = ruby.2.4.1
RUBYW_INSTALL_NAME = 
RUBY_VERSION_NAME = $(RUBY_BASE_NAME)-$(ruby_version)
RUBYW_BASE_NAME = rubyw
RUBY_BASE_NAME = ruby

arch = x86_64-darwin18
sitearch = $(arch)
ruby_version = 2.4.0
ruby = $(bindir)/$(RUBY_BASE_NAME)
RUBY = $(ruby)
ruby_headers = $(hdrdir)/ruby.h $(hdrdir)/ruby/backward.h $(hdrdir)/ruby/ruby.h $(hdrdir)/ruby/defines.h $(hdrdir)/ruby/missing.h $(hdrdir)/ruby/intern.h $(hdrdir)/ruby/st.h $(hdrdir)/ruby/subst.h $(arch_hdrdir)/ruby/config.h

RM = rm -f
RM_RF = $(RUBY) -run -e rm -- -rf
RMDIRS = rmdir -p
MAKEDIRS = /usr/local/opt/coreutils/bin/gmkdir -p
INSTALL = /usr/local/opt/coreutils/bin/ginstall -c
INSTALL_PROG = $(INSTALL) -m 0755
INSTALL_DATA = $(INSTALL) -m 644
COPY = cp
TOUCH = exit >

#### End of system configuration section. ####

preload = 
libpath = . $(libdir) /usr/local/opt/v8@3.15/lib /usr/local/opt/libyaml/lib /usr/local/opt/libksba/lib /usr/local/opt/readline/lib /usr/local/opt/zlib/lib /usr/local/opt/openssl@1.1/lib
LIBPATH =  -L. -L$(libdir) -L/usr/local/opt/v8@3.15/lib -L/usr/local/opt/libyaml/lib -L/usr/local/opt/libksba/lib -L/usr/local/opt/readline/lib -L/usr/local/opt/zlib/lib -L/usr/local/opt/openssl@1.1/lib
DEFFILE = 

CLEANFILES = mkmf.log
DISTCLEANFILES = 
DISTCLEANDIRS = 

extout = 
extout_prefix = 
target_prefix = /v8
LOCAL_LIBS = 
LIBS = $(LIBRUBYARG_SHARED) -lv8 -lobjc -lpthread  -lpthread -lgmp -ldl -lobjc 
ORIG_SRCS = accessor.cc array.cc backref.cc constants.cc constraints.cc context.cc date.cc exception.cc external.cc function.cc gc.cc handles.cc heap.cc init.cc invocation.cc locker.cc message.cc object.cc primitive.cc rr.cc script.cc signature.cc stack.cc string.cc template.cc trycatch.cc v8.cc value.cc
SRCS = $(ORIG_SRCS) 
OBJS = accessor.o array.o backref.o constants.o constraints.o context.o date.o exception.o external.o function.o gc.o handles.o heap.o init.o invocation.o locker.o message.o object.o primitive.o rr.o script.o signature.o stack.o string.o template.o trycatch.o v8.o value.o
HDRS = $(srcdir)/rr.h
LOCAL_HDRS = 
TARGET = init
TARGET_NAME = init
TARGET_ENTRY = Init_$(TARGET_NAME)
DLLIB = $(TARGET).bundle
EXTSTATIC = 
STATIC_LIB = 

TIMESTAMP_DIR = .
BINDIR        = $(bindir)
RUBYCOMMONDIR = $(sitedir)$(target_prefix)
RUBYLIBDIR    = $(sitelibdir)$(target_prefix)
RUBYARCHDIR   = $(sitearchdir)$(target_prefix)
HDRDIR        = $(rubyhdrdir)/ruby$(target_prefix)
ARCHHDRDIR    = $(rubyhdrdir)/$(arch)/ruby$(target_prefix)
TARGET_SO_DIR =
TARGET_SO     = $(TARGET_SO_DIR)$(DLLIB)
CLEANLIBS     = $(TARGET_SO) 
CLEANOBJS     = *.o  *.bak

all:    $(DLLIB)
static: $(STATIC_LIB) install-rb
.PHONY: all install static install-so install-rb
.PHONY: clean clean-so clean-static clean-rb

clean-static::
clean-rb-default::
clean-rb::
clean-so::
clean: clean-so clean-static clean-rb-default clean-rb
		-$(Q)$(RM) $(CLEANLIBS) $(CLEANOBJS) $(CLEANFILES) .*.time

distclean-rb-default::
distclean-rb::
distclean-so::
distclean-static::
distclean: clean distclean-so distclean-static distclean-rb-default distclean-rb
		-$(Q)$(RM) Makefile $(RUBY_EXTCONF_H) conftest.* mkmf.log
		-$(Q)$(RM) core ruby$(EXEEXT) *~ $(DISTCLEANFILES)
		-$(Q)$(RMDIRS) $(DISTCLEANDIRS) 2> /dev/null || true

realclean: distclean
install: install-so install-rb

install-so: $(DLLIB) $(TIMESTAMP_DIR)/.sitearchdir.-.v8.time
	$(INSTALL_PROG) $(DLLIB) $(RUBYARCHDIR)
clean-static::
	-$(Q)$(RM) $(STATIC_LIB)
install-rb: pre-install-rb do-install-rb install-rb-default
install-rb-default: pre-install-rb-default do-install-rb-default
pre-install-rb: Makefile
pre-install-rb-default: Makefile
do-install-rb:
do-install-rb-default:
pre-install-rb-default:
	@$(NULLCMD)
$(TIMESTAMP_DIR)/.sitearchdir.-.v8.time:
	$(Q) $(MAKEDIRS) $(@D) $(RUBYARCHDIR)
	$(Q) $(TOUCH) $@

site-install: site-install-so site-install-rb
site-install-so: install-so
site-install-rb: install-rb

.SUFFIXES: .c .m .cc .mm .cxx .cpp .o .S

.cc.o:
	$(ECHO) compiling $(<)
	$(Q) $(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -c $(CSRCFLAG)$<

.cc.S:
	$(ECHO) translating $(<)
	$(Q) $(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -S $(CSRCFLAG)$<

.mm.o:
	$(ECHO) compiling $(<)
	$(Q) $(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -c $(CSRCFLAG)$<

.mm.S:
	$(ECHO) translating $(<)
	$(Q) $(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -S $(CSRCFLAG)$<

.cxx.o:
	$(ECHO) compiling $(<)
	$(Q) $(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -c $(CSRCFLAG)$<

.cxx.S:
	$(ECHO) translating $(<)
	$(Q) $(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -S $(CSRCFLAG)$<

.cpp.o:
	$(ECHO) compiling $(<)
	$(Q) $(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -c $(CSRCFLAG)$<

.cpp.S:
	$(ECHO) translating $(<)
	$(Q) $(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -S $(CSRCFLAG)$<

.c.o:
	$(ECHO) compiling $(<)
	$(Q) $(CC) $(INCFLAGS) $(CPPFLAGS) $(CFLAGS) $(COUTFLAG)$@ -c $(CSRCFLAG)$<

.c.S:
	$(ECHO) translating $(<)
	$(Q) $(CC) $(INCFLAGS) $(CPPFLAGS) $(CFLAGS) $(COUTFLAG)$@ -S $(CSRCFLAG)$<

.m.o:
	$(ECHO) compiling $(<)
	$(Q) $(CC) $(INCFLAGS) $(CPPFLAGS) $(CFLAGS) $(COUTFLAG)$@ -c $(CSRCFLAG)$<

.m.S:
	$(ECHO) translating $(<)
	$(Q) $(CC) $(INCFLAGS) $(CPPFLAGS) $(CFLAGS) $(COUTFLAG)$@ -S $(CSRCFLAG)$<

$(TARGET_SO): $(OBJS) Makefile
	$(ECHO) linking shared-object v8/$(DLLIB)
	-$(Q)$(RM) $(@)
	$(Q) $(LDSHAREDXX) -o $@ $(OBJS) $(LIBPATH) $(DLDFLAGS) $(LOCAL_LIBS) $(LIBS)
	$(Q) $(POSTLINK)



$(OBJS): $(HDRS) $(ruby_headers)
