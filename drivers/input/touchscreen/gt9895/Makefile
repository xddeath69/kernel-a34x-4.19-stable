TARGET = goodix_ts_berlin

$(TARGET)-objs := goodix_brl_i2c.o goodix_ts_core.o goodix_brl_hw.o \
			goodix_cfg_bin.o goodix_ts_utils.o goodix_brl_fwupdate.o goodix_ts_gesture.o \
			goodix_ts_inspect.o goodix_ts_tools.o goodix_ts_cmd.o

obj-$(CONFIG_TOUCHSCREEN_GOODIX_9895_BRL) += $(TARGET).o

ccflags-y += -Wformat
