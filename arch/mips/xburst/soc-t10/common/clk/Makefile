ifeq ($(CONFIG_BOARD_FPGA_T10),y)
obj-y += clk_fpga.o
else
obj-y += clk_sources.o clk.o clk_cgu.o  clk_cpccr.o  clk_gate.o  clk_pll.o cpm_pwc.o
endif
