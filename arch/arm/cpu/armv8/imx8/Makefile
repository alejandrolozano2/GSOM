#
# Copyright 2017 NXP
#
# SPDX-License-Identifier:	GPL-2.0+
#

obj-y += cpu.o
obj-y += clock.o
obj-y += fsl_mu_hal.o
obj-y += fuse.o
obj-y += iomux.o
obj-y += image.o
ifneq ($(CONFIG_SPL_BUILD),y)
obj-y += partition.o
endif
obj-$(CONFIG_AHAB_BOOT) += ahab.o
obj-$(CONFIG_VIDEO_IMXDPUV1) += video_common.o
