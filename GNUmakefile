#
# GNUmakefile - Generated by ProjectCenter
#
ifeq ($(GNUSTEP_MAKEFILES),)
 GNUSTEP_MAKEFILES := $(shell gnustep-config --variable=GNUSTEP_MAKEFILES 2>/dev/null)
endif
ifeq ($(GNUSTEP_MAKEFILES),)
 $(error You need to set GNUSTEP_MAKEFILES before compiling!)
endif

include $(GNUSTEP_MAKEFILES)/common.make

#
# Framework
#
VERSION = 1.0.0
FRAMEWORK_NAME = ZipKit
PACKAGE_NAME = ZipKit
ZipKit_CURRENT_VERSION_NAME = 1.0
ZipKit_DEPLOY_WITH_CURRENT_VERSION = yes


#
# Public headers (will be installed)
#
ZipKit_HEADER_FILES = \
MacFUSE/GMAppleDouble.h \
GMAppleDouble+ZKAdditions.h \
NSData+ZKAdditions.h \
NSDate+ZKAdditions.h \
NSDictionary+ZKAdditions.h \
NSFileHandle+ZKAdditions.h \
NSFileManager+ZKAdditions.h \
NSString+ZKAdditions.h \
ZKArchive.h \
ZKCDHeader.h \
ZKCDTrailer.h \
ZKCDTrailer64.h \
ZKCDTrailer64Locator.h \
ZKDataArchive.h \
ZKDefs.h \
ZKFileArchive.h \
ZKLFHeader.h \
ZKLog.h \

#
# Class files
#
ZipKit_OBJC_FILES = \
MacFUSE/GMAppleDouble.m \
GMAppleDouble+ZKAdditions.m \
NSData+ZKAdditions.m \
NSDate+ZKAdditions.m \
NSDictionary+ZKAdditions.m \
NSFileHandle+ZKAdditions.m \
NSFileManager+ZKAdditions.m \
NSString+ZKAdditions.m \
ZKArchive.m \
ZKCDHeader.m \
ZKCDTrailer.m \
ZKCDTrailer64.m \
ZKCDTrailer64Locator.m \
ZKDataArchive.m \
ZKDefs.m \
ZKFileArchive.m \
ZKLFHeader.m \
ZKLog.m \

#
# Makefiles
#
include GNUmakefile.preamble
-include $(GNUSTEP_MAKEFILES)/aggregate.make
include $(GNUSTEP_MAKEFILES)/framework.make
-include GNUmakefile.postamble
