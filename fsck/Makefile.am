AM_CFLAGS = -Wall -Werror -Wunused-parameter \
	    -Wno-address-of-packed-member \
	    -include $(top_srcdir)/config.h -I$(top_srcdir)/include -fno-common
fsck_exfat_LDADD = $(top_builddir)/lib/libexfat.la

sbin_PROGRAMS = fsck.exfat

fsck_exfat_SOURCES = fsck.c repair.c
