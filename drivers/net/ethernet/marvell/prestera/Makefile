# SPDX-License-Identifier: GPL-2.0
obj-$(CONFIG_PRESTERA)	+= prestera.o
prestera-objs		:= prestera_main.o \
			   prestera_hw.o prestera_switchdev.o prestera_devlink.o prestera_fw_log.o \
			   prestera_rxtx.o prestera_rxtx_sdma.o prestera_dsa.o prestera_router.o \
			   prestera_acl.o prestera_flower.o prestera_debugfs.o

obj-$(CONFIG_PRESTERA_PCI)	+= prestera_pci.o

prestera-$(CONFIG_MRVL_PRESTERA_DEBUG) += prestera_log.o
ccflags-$(CONFIG_MRVL_PRESTERA_DEBUG) += -DCONFIG_MRVL_PRESTERA_DEBUG
