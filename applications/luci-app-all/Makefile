#
# Copyright (C) 2008-2014 The LuCI Team <luci@lists.subsignal.org>
#
# This is free software, licensed under the Apache License, Version 2.0 .
#

include $(TOPDIR)/rules.mk

LUCI_TITLE:=all SV-wrt need software
LUCI_DEPENDS:=+luci-app-wol +luci-app-aliddns +luci +nginx-full +openssh-client +openssh-server +openssh-sftp-server +openssh-sftp-client
PKG_NAME:=luci-app-all

include ../../luci.mk

# call BuildPackage - OpenWrt buildroot signature
