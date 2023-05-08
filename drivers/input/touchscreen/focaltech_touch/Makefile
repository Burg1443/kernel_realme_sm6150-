# Makefile for the focaltech touchscreen drivers.


obj-$(CONFIG_TOUCHSCREEN_FTS)	+=  focaltech_core.o
obj-$(CONFIG_TOUCHSCREEN_FTS)	+=  focaltech_ex_fun.o
obj-$(CONFIG_TOUCHSCREEN_FTS)	+=  focaltech_ex_mode.o
obj-$(CONFIG_TOUCHSCREEN_FTS)	+=  focaltech_gesture.o
obj-$(CONFIG_TOUCHSCREEN_FTS)	+=  focaltech_esdcheck.o
obj-$(CONFIG_TOUCHSCREEN_FTS)	+=  focaltech_point_report_check.o

obj-$(CONFIG_TOUCHSCREEN_FTS)	+=  focaltech_i2c.o
obj-$(CONFIG_TOUCHSCREEN_FTS)	+=  focaltech_flash.o
obj-$(CONFIG_TOUCHSCREEN_FTS)	+=  focaltech_flash/
obj-$(CONFIG_TOUCHSCREEN_FTS) += focaltech_fts.o

focaltech_fts-y	:= focaltech_core.o focaltech_ex_fun.o focaltech_ex_mode.o \
	focaltech_gesture.o focaltech_esdcheck.o focaltech_point_report_check.o\
	focaltech_i2c.o focaltech_flash.o \
	focaltech_flash/focaltech_upgrade_ft3518.o
