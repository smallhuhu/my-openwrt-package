# Copyright (C) 2018-2020 Lienol <lawlienol@gmail.com>
#
# This is free software, licensed under the Apache License, Version 2.0 .
#

include $(TOPDIR)/rules.mk
LUCI_TITLE:=lienolLuCI support for IPSec VPN Server
LUCI_DEPENDS:=+strongswan +strongswan-minimal +strongswan-mod-xauth-generic
LUCI_PKGARCH:=all
PKG_VERSION:=1
PKG_RELEASE:=8-20200513

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
