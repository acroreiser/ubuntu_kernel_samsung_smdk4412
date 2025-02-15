#
# Makefile for the touchscreen drivers.
#

# Each configuration option enables a list of files.

wm97xx-ts-y := wm97xx-core.o

obj-$(CONFIG_TOUCHSCREEN_88PM860X)	+= 88pm860x-ts.o
obj-$(CONFIG_TOUCHSCREEN_AD7877)	+= ad7877.o
obj-$(CONFIG_TOUCHSCREEN_AD7879)	+= ad7879.o
obj-$(CONFIG_TOUCHSCREEN_AD7879_I2C)	+= ad7879-i2c.o
obj-$(CONFIG_TOUCHSCREEN_AD7879_SPI)	+= ad7879-spi.o
obj-$(CONFIG_TOUCHSCREEN_ADS7846)	+= ads7846.o
obj-$(CONFIG_TOUCHSCREEN_ATMEL_MXT)	+= atmel_mxt_ts.o
obj-$(CONFIG_TOUCHSCREEN_ATMEL_MXT224)	+= mxt224.o
obj-$(CONFIG_TOUCHSCREEN_ATMEL_MXT224_GC)	+= mxt224_gc.o
obj-$(CONFIG_TOUCHSCREEN_ATMEL_MXT224_U1)       += mxt224_u1.o
obj-$(CONFIG_TOUCHSCREEN_ATMEL_MXT224_GRANDE)       += mxt224_grande.o
obj-$(CONFIG_TOUCHSCREEN_ATMEL_MXT224S_GRANDE)       += mxt224s_grande.o
obj-$(CONFIG_TOUCHSCREEN_ATMEL_MXT1536E)       += mxt1536e.o
obj-$(CONFIG_TOUCHSCREEN_ATMEL_MXT1664S)       += mxt1664s.o mxt1664s_sec.o
obj-$(CONFIG_TOUCHSCREEN_ATMEL_TSADCC)	+= atmel_tsadcc.o
obj-$(CONFIG_TOUCHSCREEN_BITSY)		+= h3600_ts_input.o
obj-$(CONFIG_TOUCHSCREEN_BU21013)       += bu21013_ts.o
obj-$(CONFIG_TOUCHSCREEN_CY8CTMG110)	+= cy8ctmg110_ts.o
obj-$(CONFIG_TOUCHSCREEN_DA9034)	+= da9034-ts.o
obj-$(CONFIG_TOUCHSCREEN_DYNAPRO)	+= dynapro.o
obj-$(CONFIG_TOUCHSCREEN_EDT_FT5X06)	+= edt-ft5x06.o
obj-$(CONFIG_TOUCHSCREEN_HAMPSHIRE)	+= hampshire.o
obj-$(CONFIG_TOUCHSCREEN_GUNZE)		+= gunze.o
obj-$(CONFIG_TOUCHSCREEN_EETI)		+= eeti_ts.o
obj-$(CONFIG_TOUCHSCREEN_EGALAX)	+= egalax_i2c.o
obj-$(CONFIG_TOUCHSCREEN_ELO)		+= elo.o
obj-$(CONFIG_TOUCHSCREEN_FUJITSU)	+= fujitsu_ts.o
obj-$(CONFIG_TOUCHSCREEN_INEXIO)	+= inexio.o
obj-$(CONFIG_TOUCHSCREEN_INTEL_MID)	+= intel-mid-touch.o
obj-$(CONFIG_TOUCHSCREEN_LPC32XX)	+= lpc32xx_ts.o
obj-$(CONFIG_TOUCHSCREEN_MAX11801)	+= max11801_ts.o
obj-$(CONFIG_TOUCHSCREEN_MC13783)	+= mc13783_ts.o
#obj-$(CONFIG_TOUCHSCREEN_MCS5000)	+= mcs5000_ts.o
obj-$(CONFIG_TOUCHSCREEN_MMS114)	+= mms114.o
obj-$(CONFIG_TOUCHSCREEN_MIGOR)		+= migor_ts.o
obj-$(CONFIG_TOUCHSCREEN_MMS114)	+= mms114.o
obj-$(CONFIG_TOUCHSCREEN_MTOUCH)	+= mtouch.o
obj-$(CONFIG_TOUCHSCREEN_MK712)		+= mk712.o
obj-$(CONFIG_TOUCHSCREEN_HP600)		+= hp680_ts_input.o
obj-$(CONFIG_TOUCHSCREEN_HP7XX)		+= jornada720_ts.o
obj-$(CONFIG_TOUCHSCREEN_HTCPEN)	+= htcpen.o
obj-$(CONFIG_TOUCHSCREEN_USB_COMPOSITE)	+= usbtouchscreen.o
obj-$(CONFIG_TOUCHSCREEN_PCAP)		+= pcap_ts.o
obj-$(CONFIG_TOUCHSCREEN_PENMOUNT)	+= penmount.o
obj-$(CONFIG_TOUCHSCREEN_S3C2410)	+= s3c2410_ts.o
obj-$(CONFIG_TOUCHSCREEN_EXYNOS4)	+= s5pc210_ts.o s5pc210_ts_gpio_i2c.o s5pc210_ts_sysfs.o
obj-$(CONFIG_TOUCHSCREEN_PIXCIR)	+= pixcir_i2c_ts.o
obj-$(CONFIG_TOUCHSCREEN_ST1232)	+= st1232.o
obj-$(CONFIG_TOUCHSCREEN_STMPE)		+= stmpe-ts.o
obj-$(CONFIG_TOUCHSCREEN_TNETV107X)	+= tnetv107x-ts.o
obj-$(CONFIG_TOUCHSCREEN_SYNAPTICS_I2C_RMI)	+= synaptics_i2c_rmi.o
obj-$(CONFIG_TOUCHSCREEN_TOUCHIT213)	+= touchit213.o
obj-$(CONFIG_TOUCHSCREEN_TOUCHRIGHT)	+= touchright.o
obj-$(CONFIG_TOUCHSCREEN_TOUCHWIN)	+= touchwin.o
obj-$(CONFIG_TOUCHSCREEN_TSC_SERIO)	+= tsc40.o
obj-$(CONFIG_TOUCHSCREEN_TSC2005)	+= tsc2005.o
obj-$(CONFIG_TOUCHSCREEN_TSC2007)	+= tsc2007.o
obj-$(CONFIG_TOUCHSCREEN_UCB1400)	+= ucb1400_ts.o
obj-$(CONFIG_TOUCHSCREEN_WACOM_W8001)	+= wacom_w8001.o
obj-$(CONFIG_INPUT_WACOM)		+= wacom/
obj-$(CONFIG_TOUCHSCREEN_WM831X)	+= wm831x-ts.o
obj-$(CONFIG_TOUCHSCREEN_WM97XX)	+= wm97xx-ts.o
wm97xx-ts-$(CONFIG_TOUCHSCREEN_WM9705)	+= wm9705.o
wm97xx-ts-$(CONFIG_TOUCHSCREEN_WM9712)	+= wm9712.o
wm97xx-ts-$(CONFIG_TOUCHSCREEN_WM9713)	+= wm9713.o
obj-$(CONFIG_TOUCHSCREEN_WM97XX_ATMEL)	+= atmel-wm97xx.o
obj-$(CONFIG_TOUCHSCREEN_WM97XX_MAINSTONE)	+= mainstone-wm97xx.o
obj-$(CONFIG_TOUCHSCREEN_WM97XX_ZYLONITE)	+= zylonite-wm97xx.o
obj-$(CONFIG_TOUCHSCREEN_W90X900)	+= w90p910_ts.o
obj-$(CONFIG_TOUCHSCREEN_TPS6507X)	+= tps6507x-ts.o
obj-$(CONFIG_TOUCHSCREEN_MELFAS)	+= mms_ts.o
obj-$(CONFIG_TOUCHSCREEN_MELFAS_MMS)	+= melfas_mms_ts.o
obj-$(CONFIG_TOUCHSCREEN_MELFAS_GC)	+= mms_ts_gc.o
obj-$(CONFIG_TOUCHSCREEN_MMS152)	+= mms152.o mms152_download.o mms152_isc_download.o
obj-$(CONFIG_TOUCHSCREEN_MELFAS_NOTE)	+= mms152_ts.o
obj-$(CONFIG_MELFAS_TOUCHKEY)		+= melfas_touchkey.o melfas_download.o
obj-$(CONFIG_TOUCHSCREEN_ZINITIX)	+= zinitix_touch.o
obj-$(CONFIG_TOUCHSCREEN_ATMEL_MXT540E)	+= mxt540e.o
obj-$(CONFIG_TOUCHSCREEN_MXT1386)	+= atmel_mxt1386.o atmel_mxt1386_cfg.o
obj-$(CONFIG_TOUCHSCREEN_MXT768E)	+= mxt768e.o
obj-$(CONFIG_TOUCHSCREEN_SYNAPTICS_S7301)      += synaptics_s7301.o synaptics_fw_updater.o synaptics_sysfs.o
obj-$(CONFIG_KEYPAD_MELFAS_TOUCH)                += grande_touchkey.o grande_download.o
obj-$(CONFIG_TOUCHSCREEN_ATMEL_MXT540S)       += mxt540s.o
obj-$(CONFIG_TOUCHSCREEN_CYTTSP4)   += cyttsp4_i2c.o cyttsp4_core.o

ifeq ($(TARGET_BUILD_VARIANT), eng)
KBUILD_CFLAGS		+= -DSEC_TSP_EVENT_DEBUG
endif
