subdir-ccflags-y += -I$(srctree)/drivers/misc/mediatek/typec/tcpc/inc
subdir-ccflags-y += -I$(srctree)/drivers/power/supply/mediatek/misc/
subdir-ccflags-y += -I$(srctree)/drivers/power/supply/mediatek/charger/

obj-y += ln8410.o
obj-y += ln8000.o

# Disable stack protector for ln8000.o
CFLAGS_REMOVE_ln8000.o := -fstack-protector-strong
CFLAGS_REMOVE_ln8410.o := -fstack-protector-strong