dtb-$(CONFIG_PROJECT_c330ae_tinno) += c330ae.dtb

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
	dtbo-$(CONFIG_PROJECT_c330ae_tinno) += c330ae-overlay.dtbo
	c330ae-overlay.dtbo-base := c330ae.dtb
endif

always		:= $(dtb-y) $(dtbo-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb
