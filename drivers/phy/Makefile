# SPDX-License-Identifier: GPL-2.0
#
# Makefile for the phy drivers.
#

obj-$(CONFIG_GENERIC_PHY)		+= phy-core.o
obj-$(CONFIG_GENERIC_PHY_MIPI_DPHY)	+= phy-core-mipi-dphy.o
obj-$(CONFIG_PHY_LPC18XX_USB_OTG)	+= phy-lpc18xx-usb-otg.o
obj-$(CONFIG_PHY_XGENE)			+= phy-xgene.o
obj-$(CONFIG_PHY_PISTACHIO_USB)		+= phy-pistachio-usb.o
obj-$(CONFIG_ARCH_SUNXI)		+= allwinner/
obj-$(CONFIG_ARCH_MESON)		+= amlogic/
obj-$(CONFIG_ARCH_MEDIATEK)		+= mediatek/
obj-$(CONFIG_ARCH_RENESAS)		+= renesas/
obj-$(CONFIG_ARCH_ROCKCHIP)		+= rockchip/
obj-$(CONFIG_ARCH_TEGRA)		+= tegra/
obj-y					+= broadcom/	\
					   cadence/	\
					   freescale/	\
					   hisilicon/	\
					   lantiq/	\
					   marvell/	\
					   motorola/	\
					   mscc/	\
					   qualcomm/	\
					   ralink/	\
					   samsung/	\
					   socionext/	\
					   st/		\
					   ti/
obj-$(CONFIG_PHY_XILINX_ZYNQMP)		+= phy-zynqmp.o
