#
# luci-theme-ctmodem - 光猫/家庭网关风格 LuCI 主题
#
# 编译位置不限：feeds/luci/themes/、package/ 或作为第三方 feed 都可以，
# 前提是 luci feed 已安装（$(TOPDIR)/feeds/luci/luci.mk 存在）。
#
include $(TOPDIR)/rules.mk

LUCI_TITLE:=LuCI theme - ctmodem (ONT gateway style)
LUCI_DESCRIPTION:=A LuCI theme reproducing the classic orange/blue home gateway \
 (ONT) web interface layout: top level tabs, secondary bar and a left navigation column.
LUCI_PKGARCH:=all
LUCI_DEPENDS:=+luci-base

# luci.mk 用的是 LUCI_MAINTAINER / LUCI_URL，不是 PKG_MAINTAINER / PKG_URL
LUCI_MAINTAINER:=hakureiyuyuko <hakureiyuyuko@users.noreply.github.com>
LUCI_URL:=https://github.com/hakureiyuyuko/luci-theme-ctmodem

PKG_LICENSE:=MIT
PKG_VERSION:=0.1.0
PKG_RELEASE:=1

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
