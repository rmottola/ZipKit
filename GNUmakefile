#
# GNUmakefile
#
ifeq ($(GNUSTEP_MAKEFILES),)
 GNUSTEP_MAKEFILES := $(shell gnustep-config --variable=GNUSTEP_MAKEFILES 2>/dev/null)
  ifeq ($(GNUSTEP_MAKEFILES),)
    $(warning )
    $(warning Unable to obtain GNUSTEP_MAKEFILES setting from gnustep-config!)
    $(warning Perhaps gnustep-make is not properly installed,)
    $(warning so gnustep-config is not in your PATH.)
    $(warning )
    $(warning Your PATH is currently $(PATH))
    $(warning )
  endif
endif
ifeq ($(GNUSTEP_MAKEFILES),)
 $(error You need to set GNUSTEP_MAKEFILES before compiling!)
endif

include $(GNUSTEP_MAKEFILES)/common.make

#
# Framework
#
VERSION = 0.1
PACKAGE_NAME = ZipKit
FRAMEWORK_NAME = ZipKit
ZipKit_CURRENT_VERSION_NAME = 0.1
ZipKit_DEPLOY_WITH_CURRENT_VERSION = yes


#
# Public headers (will be installed)
#
ZipKit_HEADER_FILES = \
ZipKit/ZipKit.h \
ZipKit/NSData+ZKAdditions.h \
ZipKit/NSDate+ZKAdditions.h \
ZipKit/NSDictionary+ZKAdditions.h \
ZipKit/NSFileHandle+ZKAdditions.h \
ZipKit/NSFileManager+ZKAdditions.h \
ZipKit/NSString+ZKAdditions.h \
ZipKit/ZKArchive.h \
ZipKit/ZKCDHeader.h \
ZipKit/ZKCDTrailer.h \
ZipKit/ZKCDTrailer64.h \
ZipKit/ZKCDTrailer64Locator.h \
ZipKit/ZKDataArchive.h \
ZipKit/ZKDefs.h \
ZipKit/ZKFileArchive.h \
ZipKit/ZKLFHeader.h \
ZipKit/ZKLog.h 

#
# Objective-C Class files
#
ZipKit_OBJC_FILES = \
ZipKit/NSData+ZKAdditions.m \
ZipKit/NSDate+ZKAdditions.m \
ZipKit/NSDictionary+ZKAdditions.m \
ZipKit/NSFileHandle+ZKAdditions.m \
ZipKit/NSFileManager+ZKAdditions.m \
ZipKit/NSString+ZKAdditions.m \
ZipKit/ZKArchive.m \
ZipKit/ZKCDHeader.m \
ZipKit/ZKCDTrailer.m \
ZipKit/ZKCDTrailer64.m \
ZipKit/ZKCDTrailer64Locator.m \
ZipKit/ZKDataArchive.m \
ZipKit/ZKDefs.m \
ZipKit/ZKFileArchive.m \
ZipKit/ZKLFHeader.m \
ZipKit/ZKLog.m

#
# Makefiles
#
-include GNUmakefile.preamble
include $(GNUSTEP_MAKEFILES)/aggregate.make
include $(GNUSTEP_MAKEFILES)/framework.make
-include GNUmakefile.postamble
