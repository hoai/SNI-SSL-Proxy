AM_CFLAGS = -O3 -pipe -W -Wall -fno-strict-aliasing

bin_PROGRAMS = sniproxy

sniproxy_SOURCES = \
    log.c buffer.c proxy.c socks5.c tcprelay.c utils.c main.c \
    log.h buffer.h proxy.h socks5.h tcprelay.h utils.h
sniproxy_LDADD = $(LIB_MILL)
