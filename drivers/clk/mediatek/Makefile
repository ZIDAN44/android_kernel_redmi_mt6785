# SPDX-License-Identifier: GPL-2.0

ccflags-y += -I$(srctree)/drivers/misc/mediatek/include/

obj-$(CONFIG_COMMON_CLK_MEDIATEK) += clk-mtk.o clk-pll.o clk-gate.o clk-apmixed.o clk-cpumux.o clk-mux.o
obj-$(CONFIG_RESET_CONTROLLER) += reset.o
ifneq ($(CONFIG_FPGA_EARLY_PORTING), y)
obj-$(CONFIG_COMMON_CLK_MT6785) += clk-mt6785.o clk-mt6785-pg.o clk-mtk-v1.o clkdbg.o clkchk.o clkdbg-mt6785.o clkchk-mt6785.o
endif
obj-$(CONFIG_COMMON_CLK_MT6797) += clk-mt6797.o
obj-$(CONFIG_COMMON_CLK_MT6797_IMGSYS) += clk-mt6797-img.o
obj-$(CONFIG_COMMON_CLK_MT6797_MMSYS) += clk-mt6797-mm.o
obj-$(CONFIG_COMMON_CLK_MT6797_VDECSYS) += clk-mt6797-vdec.o
obj-$(CONFIG_COMMON_CLK_MT6797_VENCSYS) += clk-mt6797-venc.o
obj-$(CONFIG_COMMON_CLK_MT2701) += clk-mt2701.o
obj-$(CONFIG_COMMON_CLK_MT2701_BDPSYS) += clk-mt2701-bdp.o
obj-$(CONFIG_COMMON_CLK_MT2701_ETHSYS) += clk-mt2701-eth.o
obj-$(CONFIG_COMMON_CLK_MT2701_HIFSYS) += clk-mt2701-hif.o
obj-$(CONFIG_COMMON_CLK_MT2701_IMGSYS) += clk-mt2701-img.o
obj-$(CONFIG_COMMON_CLK_MT2701_MMSYS) += clk-mt2701-mm.o
obj-$(CONFIG_COMMON_CLK_MT2701_VDECSYS) += clk-mt2701-vdec.o
obj-$(CONFIG_COMMON_CLK_MT6771) += clk-mt6771.o clk-mt6771-pg.o clk-mtk-v1.o clkdbg.o
obj-$(CONFIG_COMMON_CLK_MT6768) += clk-mt6768.o clk-mtk-v1.o clk-mt6768-pg.o clkdbg.o
obj-$(CONFIG_COMMON_CLK_MT8135) += clk-mt8135.o
obj-$(CONFIG_COMMON_CLK_MT8173) += clk-mt8173.o
obj-$(CONFIG_COMMON_CLK_MT8183) += clk-mt8183.o clk-bringup.o clkdbg.o clkdbg-mt8183.o
obj-$(CONFIG_COMMON_CLK_MT8183_AUDIOSYS) += clk-mt8183-audio.o
obj-$(CONFIG_COMMON_CLK_MT8183_CAMSYS) += clk-mt8183-cam.o
obj-$(CONFIG_COMMON_CLK_MT8183_IMGSYS) += clk-mt8183-img.o
obj-$(CONFIG_COMMON_CLK_MT8183_IPU_CORE0) += clk-mt8183-ipu0.o
obj-$(CONFIG_COMMON_CLK_MT8183_IPU_CORE1) += clk-mt8183-ipu1.o
obj-$(CONFIG_COMMON_CLK_MT8183_IPU_ADL) += clk-mt8183-ipu_adl.o
obj-$(CONFIG_COMMON_CLK_MT8183_IPU_CONN) += clk-mt8183-ipu_conn.o
obj-$(CONFIG_COMMON_CLK_MT8183_MFGCFG) += clk-mt8183-mfgcfg.o
obj-$(CONFIG_COMMON_CLK_MT8183_MMSYS) += clk-mt8183-mm.o
obj-$(CONFIG_COMMON_CLK_MT8183_VDECSYS) += clk-mt8183-vdec.o
obj-$(CONFIG_COMMON_CLK_MT8183_VENCSYS) += clk-mt8183-venc.o

ifeq ($(CONFIG_DEBUG_FS), y)
obj-$(CONFIG_COMMON_CLK_MT6768) +=  clkchk-mt6768.o clkdbg-mt6768.o mt6768_clkmgr.o
endif
