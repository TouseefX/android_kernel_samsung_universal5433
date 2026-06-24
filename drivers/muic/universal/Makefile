# drivers/muic/universal/Makefile
obj-$(CONFIG_MUIC_UNIVERSAL) += muic_task.o \
                                muic_state.o \
                                muic_apis.o \
                                muic_sysfs.o \
                                muic_debug.o \
                                muic_dt.o \
                                muic_i2c.o \
                                muic_regmap.o \
                                muic_vps.o

obj-$(CONFIG_MUIC_UNIVERSAL_SM5703)  += muic_regmap_sm5703.o
obj-$(CONFIG_MUIC_UNIVERSAL_S2MM001) += muic_regmap_s2mm001b.o
obj-$(CONFIG_MUIC_UNIVERSAL_MAX77849)+= muic_regmap_max77849.o
