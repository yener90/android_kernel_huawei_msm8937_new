#
# Makefile for the QCOM specific video device drivers
# based on V4L2.
#
obj-$(CONFIG_MSM_VIDC_V4L2) += vidc/
obj-y += broadcast/
obj-$(CONFIG_DVB_MPQ) += dvb/
ifeq ($(CONFIG_MACH_XIAOMI),y)
ifeq ($(CONFIG_MACH_XIAOMI_MSM8937),y)
ifeq ($(CONFIG_MACH_XIAOMI_LAND),y)
obj-$(CONFIG_MSMB_CAMERA) += camera_v2-land/
endif
else ifeq ($(CONFIG_MACH_XIAOMI_MSM8940),y)
ifeq ($(CONFIG_MACH_XIAOMI_SANTONI),y)
obj-$(CONFIG_MSMB_CAMERA) += camera_v2-santoni/
endif
endif
else ifeq ($(CONFIG_MACH_HUAWEI),y)
ifeq ($(CONFIG_MACH_HUAWEI_MSM8940),y)
ifeq ($(CONFIG_MACH_HUAWEI_DIEGO),y)
obj-$(CONFIG_MSMB_CAMERA) += camera_v2-diego/
endif
endif
else
obj-$(CONFIG_MSMB_CAMERA) += camera_v2/
endif
obj-$(CONFIG_MSM_AIS) += ais/
obj-y += sde/
