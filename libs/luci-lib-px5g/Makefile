#
# Copyright (C) 2008-2014 The LuCI Team <luci@lists.subsignal.org>
#
# This is free software, licensed under the Apache License, Version 2.0 .
#

include $(TOPDIR)/rules.mk

LUCI_TITLE:=RSA/X.509 Key Generator (required for LuCId SSL support)
LUCI_DEPENDS:=+lua +luci-lib-nixio

PKG_BUILD_FLAGS:=no-mips16
PKG_LICENSE:=LGPL-2.1

include ../../luci.mk

# call BuildPackage - OpenWrt buildroot signature
