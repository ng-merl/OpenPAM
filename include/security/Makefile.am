# $Id$

securitydir = $(includedir)/security

security_HEADERS = \
	openpam.h \
	openpam_attr.h \
	openpam_version.h \
	pam_appl.h \
	pam_constants.h \
	pam_modules.h \
	pam_types.h

if WITH_OATH
security_HEADERS += \
	oath.h \
	oath_constants.h \
	oath_rfc3986.h \
	oath_rfc4648.h \
	oath_types.h
endif
