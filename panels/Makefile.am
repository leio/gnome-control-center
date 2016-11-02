SUBDIRS= \
	common \
	background \
	power \
	display \
	mouse \
	notifications \
	region \
	info \
	sound \
	keyboard \
	universal-access \
	user-accounts \
	datetime \
	search \
	privacy \
	sharing

if BUILD_COLOR
SUBDIRS += color
endif

if BUILD_WACOM
SUBDIRS += wacom
endif

if BUILD_PRINTERS
SUBDIRS += printers
endif

if BUILD_NETWORK
SUBDIRS += network
endif

if BUILD_BLUETOOTH
SUBDIRS += bluetooth
endif

if BUILD_ONLINE_ACCOUNTS
SUBDIRS += online-accounts
endif

-include $(top_srcdir)/git.mk
