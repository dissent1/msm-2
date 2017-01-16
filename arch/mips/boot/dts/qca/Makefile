# All DTBs
dtb-$(CONFIG_ATH79)			+= ar9132_tl_wr1043nd_v1.dtb ath79_ap152.dtb ath79_ap152_dual.dtb \
						ath79_ap151.dtb ath79_ap147.dtb ath79_ap137.dtb \
						ath79_ap135.dtb

# Select a DTB to build in the kernel
obj-$(CONFIG_DTB_TL_WR1043ND_V1)	+= ar9132_tl_wr1043nd_v1.dtb.o

# Force kbuild to make empty built-in.o if necessary
obj-				+= dummy.o

always				:= $(dtb-y)
clean-files			:= *.dtb *.dtb.S
