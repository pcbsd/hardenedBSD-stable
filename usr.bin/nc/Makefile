# $FreeBSD$

.PATH: ${.CURDIR}/../../contrib/netcat

PROG=	nc
SRCS=	netcat.c atomicio.c socks.c

CFLAGS+=-DIPSEC
LIBADD=	ipsec
WANTS_PIE=	yes

WARNS?=	2

.include <bsd.prog.mk>
