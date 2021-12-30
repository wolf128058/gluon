include $(TOPDIR)/rules.mk

PKG_NAME:=gluon-usteer

include ../gluon.mk

define Package/gluon-usteer
  TITLE:=Gluon integration for the usteer daemon
  DEPENDS:=+usteer
endef

$(eval $(call BuildPackageGluon,gluon-usteer))
