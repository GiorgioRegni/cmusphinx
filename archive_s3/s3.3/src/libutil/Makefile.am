ARCH   = `uname -m | sed s/i.86/i386/`_`uname -s | tr A-Z a-z`

lib_LTLIBRARIES = libutil.la

libutil_la_LDFLAGS = -version-info 0:1:0

libutil_la_SOURCES = \
        bitvec.c \
        case.c \
        ckd_alloc.c \
        cmd_ln.c \
        err.c \
        filename.c \
        glist.c \
        hash.c \
        heap.c \
        io.c \
        profile.c \
        str2words.c \
        unlimit.c

noinst_HEADERS = \
        bitvec.h \
        case.h \
        ckd_alloc.h \
        cmd_ln.h \
        err.h \
        filename.h \
        glist.h \
        hash.h \
        heap.h \
        io.h \
        libutil.h \
        prim_type.h \
        profile.h \
        str2words.h \
        unlimit.h

INCLUDES = -I$(top_srcdir) \
	   -I$(top_srcdir)/include \
           -I$(top_builddir)/include 

LIBOBJS = @LIBOBJS@
