AM_CFLAGS = -Wall

DISTCLEANFILES = ftconfig.h

include_HEADERS = ftlib.h ftqueue.h
lib_LTLIBRARIES = libft.la

libft_la_SOURCES = ftio.c ftswap.c ftencode.c ftdecode.c ftprof.c bit1024.c \
 fmt.c support.c ftfile.c fttlv.c ftmap.c ftrec.c fterr.c \
 ftchash.c ftsym.c radix.c fttag.c ftfil.c ftstat.c getdate.y ftxfield.c \
 ftmask.c ftvar.c ftxlate.c ftqueue.h radix.h ftconfig.h \
 ftpaths.c ftinclude.h radix.h

libft_la_LIBADD = $(LTLIBOBJS) $(CRYPTOLIB)
libft_la_CPPFLAGS = $(AM_CPPFLAGS) -DSYSCONFDIR=\"$(sysconfdir)\"
