ccflags-y += -Idrivers/media/platform/msm/camera_v2-diego
ccflags-y += -Idrivers/media/platform/msm/camera_v2-diego/sensor
ccflags-y += -Idrivers/media/platform/msm/camera_v2-diego/codecs
ccflags-y += -Idrivers/media/platform/msm/camera_v2-diego/isps
ccflags-y += -Idrivers/media/platform/msm/camera_v2-diego/pproc
ccflags-y += -Idrivers/media/platform/msm/camera_v2-diego/msm_vb2
ccflags-y += -Idrivers/media/platform/msm/camera_v2-diego/camera
ccflags-y += -Idrivers/media/platform/msm/camera_v2-diego/jpeg_10
ccflags-y += -Idrivers/media/platform/msm/camera_v2-diego/jpeg_dma
ccflags-y += -Idrivers/media/platform/msm/camera_v2-diego/fd
ccflags-y += -Idrivers/media/platform/msm/camera_v2-diego/common

obj-$(CONFIG_MSMB_CAMERA) += common/
obj-$(CONFIG_MSMB_CAMERA) += msm.o
obj-$(CONFIG_MSMB_CAMERA) += hw_camera_common.o
obj-$(CONFIG_HUAWEI_DSM) += msm_camera_dsm.o
obj-$(CONFIG_MSMB_CAMERA) += camerafs.o
obj-$(CONFIG_MSMB_CAMERA) += camera/
obj-$(CONFIG_MSMB_CAMERA) += msm_vb2/
obj-$(CONFIG_MSMB_CAMERA) += sensor/
obj-$(CONFIG_MSMB_CAMERA) += pproc/
obj-$(CONFIG_MSMB_CAMERA) += isp/
obj-$(CONFIG_MSMB_CAMERA) += ispif/
obj-$(CONFIG_MSMB_JPEG) += jpeg_10/
obj-$(CONFIG_MSM_JPEGDMA) += jpeg_dma/
obj-$(CONFIG_MSMB_CAMERA) += msm_buf_mgr/
obj-$(CONFIG_MSM_FD) += fd/
