lib_LTLIBRARIES = libgstsctp-1.5.la

libgstsctp_1_5_la_SOURCES = \
    sctpsendmeta.c \
    sctpreceivemeta.c

libgstsctp_1_5_la_CFLAGS = \
    $(GST_PLUGINS_BASE_CFLAGS) \
    $(GST_BASE_CFLAGS) \
    $(GST_CFLAGS)

libgstsctp_1_5_la_LIBADD = $(GST_LIBS) $(GST_BASE_LIBS)

libgstsctp_1_5_includedir = $(includedir)/gstreamer-1.5/gst/sctp
libgstsctp_1_5_include_HEADERS = \
    sctpsendmeta.h \
    sctpreceivemeta.h

-include $(top_srcdir)/git.mk
