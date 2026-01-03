# Copyright 2019 X-WRT <dev@x-wrt.com>
# Copyright 2022-2023 sirpdboy  

include $(TOPDIR)/rules.mk

PKG_NAME:=luci-app-networkwizard
PKG_VERSION:=1.8.8
PKG_RELEASE:=20260103

PKG_LICENSE:=GPLv3
PKG_LICENSE_FILES:=LICENSE
PKG_MAINTAINER:=Chen Minqiang <ptpt52@gmail.com>

LUCI_TITLE:=LuCI Support for Wizard
LUCI_DEPENDS:=+luci-compat
LUCI_PKGARCH:=all

define Package/$(PKG_NAME)/conffiles
/etc/config/networkwizard
endef

include $(TOPDIR)/feeds/luci/luci.mk

define Package/luci-app-networkwizard/postinst
endef

# call BuildPackage - OpenWrt buildroot signature
