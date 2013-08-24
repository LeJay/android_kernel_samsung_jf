GCC_VERSION      := $(shell $(CONFIG_SHELL) $(PWD)/scripts/gcc-version.sh $(CROSS_COMPILE)gcc)
EXTRA_CFLAGS += -Idrivers/media/video/msm
EXTRA_CFLAGS += -Idrivers/media/video/msm/io
obj-$(CONFIG_MSM_ACTUATOR) += msm_actuator.o
ifdef CONFIG_MACH_JACTIVE_EUR
obj-$(CONFIG_MSM_ACTUATOR) += hvca_actuator.o
endif
ifdef CONFIG_MACH_JACTIVE_ATT
obj-$(CONFIG_MSM_ACTUATOR) += hvca_actuator.o
endif
