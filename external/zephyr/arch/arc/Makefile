ccflags-y +=-I$(srctree)/arch/arc/platforms/$(strip $(CONFIG_PLATFORM))
asflags-y +=-I$(srctree)/arch/arc/platforms/$(strip $(CONFIG_PLATFORM))

obj-y = core/

obj-y += prep_c.o \
         reset.o \
         vector_table.o

obj-$(CONFIG_PLATFORM_QUARK_SE_ARC) += platforms/quark_se-arc/
