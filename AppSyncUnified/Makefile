ARCHS = armv7 armv7s arm64

include $(THEOS)/makefiles/common.mk

TWEAK_NAME = AppSyncUnified
AppSyncUnified_FILES = AppSyncUnified.x dump.cpp
AppSyncUnified_CFLAGS += -fvisibility=hidden -DKAREN_ASU
AppSyncUnified_LIBRARIES = substrate

include $(THEOS_MAKE_PATH)/tweak.mk
