#
# Copyright (C) 2019-2025 The Sirpdboy Team <herboy2008@gmail.com>    
#
# This is free software, licensed under the Apache License, Version 2.0 .
#

include $(TOPDIR)/rules.mk
THEME_NAME:=kucat
THEME_TITLE:=Kucat Theme
PKG_NAME:=luci-theme-$(THEME_NAME)
LUCI_TITLE:=Kucat Theme by sirpdboy
LUCI_DEPENDS:=
PKG_VERSION:=2.6.11
PKG_RELEASE:=20250723

define Package/luci-theme-$(THEME_NAME)/conffiles
/www/luci-static/resources/background/
/www/luci-static/kucat/img/
/etc/config/kucat
endef

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
