#
# Copyright 2019 Nick Peng <pymumu@gmail.com>
# Licensed to the public under the GPL V3 License.
#

include $(TOPDIR)/rules.mk

PKG_LICENSE:=GPL-3.0
PKG_MAINTAINER:=Nick Peng <pymumu@gmail.com>

LUCI_TITLE:=LuCI for smartdns
LUCI_DESCRIPTION:=Provides Luci for smartdns
LUCI_DEPENDS:=+luci-mod-admin-full +smartdns
LUCI_PKGARCH:=all
PKG_RELEASE:=1

include ../../luci.mk

# call BuildPackage - OpenWrt buildroot signature
