$(info "CONFIG_MICROTRUST_TEE_SUPPORT=$(CONFIG_MICROTRUST_TEE_SUPPORT)")
$(info "CONFIG_MICROTRUST_TZ_DRIVER=$(CONFIG_MICROTRUST_TZ_DRIVER)")
$(info "CONFIG_MICROTRUST_VFS_DRIVER=$(CONFIG_MICROTRUST_VFS_DRIVER)")
$(info "CONFIG_MICROTRUST_FP_DRIVER=$(CONFIG_MICROTRUST_FP_DRIVER)")
$(info "CONFIG_MICROTRUST_TUI_SUPPORT=$(CONFIG_MICROTRUST_TUI_SUPPORT)")
$(info "CONFIG_MICROTRUST_DEBUG=$(CONFIG_MICROTRUST_DEBUG)")

subdir-ccflags-y  += -I$(srctree)/drivers/misc/mediatek/teei/V1.0/common/include
obj-$(CONFIG_MICROTRUST_TZ_DRIVER) += tz_driver/
obj-$(CONFIG_MICROTRUST_VFS_DRIVER) += tz_vfs/
obj-$(CONFIG_MICROTRUST_FP_DRIVER) += teei_fp/
obj-$(CONFIG_MICROTRUST_KEYMASTER_DRIVER) += ut_keymaster/
obj-$(CONFIG_MICROTRUST_TUI_SUPPORT) += ut_tui/


