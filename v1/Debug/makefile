################################################################################
# Automatically-generated file. Do not edit!
################################################################################

SHELL = cmd.exe

CG_TOOL_ROOT := C:/ti/ccs1010/ccs/tools/compiler/ti-cgt-arm_20.2.1.LTS

GEN_OPTS__FLAG := 
GEN_CMDS__FLAG := 

ORDERED_OBJS += \
"./Fapi_UserDefinedFunctions.obj" \
"./bl_check.obj" \
"./bl_flash.obj" \
"./bl_main.obj" \
"./bl_uart.obj" \
"./bl_ymodem.obj" \
"./sci_common.obj" \
"./sw_hw_ver.obj" \
"./ymodem_crc16.obj" \
"./source/HL_epc.obj" \
"./source/HL_errata.obj" \
"./source/HL_errata_SSWF021_45.obj" \
"./source/HL_esm.obj" \
"./source/HL_gio.obj" \
"./source/HL_nmpu.obj" \
"./source/HL_notification.obj" \
"./source/HL_pinmux.obj" \
"./source/HL_rti.obj" \
"./source/HL_sci.obj" \
"./source/HL_sys_core.obj" \
"./source/HL_sys_dma.obj" \
"./source/HL_sys_intvecs.obj" \
"./source/HL_sys_mpu.obj" \
"./source/HL_sys_pcr.obj" \
"./source/HL_sys_phantom.obj" \
"./source/HL_sys_pmm.obj" \
"./source/HL_sys_pmu.obj" \
"./source/HL_sys_startup.obj" \
"./source/HL_sys_vim.obj" \
"./source/HL_system.obj" \
"../lib/F021_API_CortexR4_BE_L2FMC.lib" \
"../lib/F021_API_CortexR4_BE_L2FMC_V3D16.lib" \
"../lib/F021_API_CortexR4_LE_L2FMC.lib" \
"../source/HL_sys_link.cmd" \
$(GEN_CMDS__FLAG) \
-l"C:/Users/farou/Desktop/New folder/TMS570LC4357_UART_Boot/lib/F021_API_CortexR4_BE_L2FMC.lib" \
-lrtsv7R4_T_be_v3D16_eabi.lib \

-include ../makefile.init

RM := DEL /F
RMDIR := RMDIR /S/Q

# All of the sources participating in the build are defined here
-include sources.mk
-include subdir_vars.mk
-include lib/subdir_vars.mk
-include source/subdir_vars.mk
-include subdir_rules.mk
-include lib/subdir_rules.mk
-include source/subdir_rules.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(C55_DEPS)),)
-include $(C55_DEPS)
endif
ifneq ($(strip $(C_UPPER_DEPS)),)
-include $(C_UPPER_DEPS)
endif
ifneq ($(strip $(S67_DEPS)),)
-include $(S67_DEPS)
endif
ifneq ($(strip $(S62_DEPS)),)
-include $(S62_DEPS)
endif
ifneq ($(strip $(S_DEPS)),)
-include $(S_DEPS)
endif
ifneq ($(strip $(OPT_DEPS)),)
-include $(OPT_DEPS)
endif
ifneq ($(strip $(C??_DEPS)),)
-include $(C??_DEPS)
endif
ifneq ($(strip $(ASM_UPPER_DEPS)),)
-include $(ASM_UPPER_DEPS)
endif
ifneq ($(strip $(S??_DEPS)),)
-include $(S??_DEPS)
endif
ifneq ($(strip $(C64_DEPS)),)
-include $(C64_DEPS)
endif
ifneq ($(strip $(CXX_DEPS)),)
-include $(CXX_DEPS)
endif
ifneq ($(strip $(S64_DEPS)),)
-include $(S64_DEPS)
endif
ifneq ($(strip $(INO_DEPS)),)
-include $(INO_DEPS)
endif
ifneq ($(strip $(CLA_DEPS)),)
-include $(CLA_DEPS)
endif
ifneq ($(strip $(S55_DEPS)),)
-include $(S55_DEPS)
endif
ifneq ($(strip $(SV7A_DEPS)),)
-include $(SV7A_DEPS)
endif
ifneq ($(strip $(C62_DEPS)),)
-include $(C62_DEPS)
endif
ifneq ($(strip $(C67_DEPS)),)
-include $(C67_DEPS)
endif
ifneq ($(strip $(PDE_DEPS)),)
-include $(PDE_DEPS)
endif
ifneq ($(strip $(K_DEPS)),)
-include $(K_DEPS)
endif
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
ifneq ($(strip $(CC_DEPS)),)
-include $(CC_DEPS)
endif
ifneq ($(strip $(C++_DEPS)),)
-include $(C++_DEPS)
endif
ifneq ($(strip $(C43_DEPS)),)
-include $(C43_DEPS)
endif
ifneq ($(strip $(S43_DEPS)),)
-include $(S43_DEPS)
endif
ifneq ($(strip $(ASM_DEPS)),)
-include $(ASM_DEPS)
endif
ifneq ($(strip $(S_UPPER_DEPS)),)
-include $(S_UPPER_DEPS)
endif
ifneq ($(strip $(CPP_DEPS)),)
-include $(CPP_DEPS)
endif
ifneq ($(strip $(SA_DEPS)),)
-include $(SA_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 
EXE_OUTPUTS += \
TMS570LC4357_UART_Boot.out \

EXE_OUTPUTS__QUOTED += \
"TMS570LC4357_UART_Boot.out" \

BIN_OUTPUTS += \
TMS570LC4357_UART_Boot.bin \

BIN_OUTPUTS__QUOTED += \
"TMS570LC4357_UART_Boot.bin" \


# All Target
all: TMS570LC4357_UART_Boot.out

# Tool invocations
TMS570LC4357_UART_Boot.out: $(OBJS) $(CMD_SRCS) $(LIB_SRCS) $(GEN_CMDS)
	@echo 'Building target: "$@"'
	@echo 'Invoking: ARM Linker'
	"C:/ti/ccs1010/ccs/tools/compiler/ti-cgt-arm_20.2.1.LTS/bin/armcl" -mv7R5 --code_state=32 --float_support=VFPv3D16 -g --diag_warning=225 --diag_wrap=off --display_error_number --enum_type=packed --abi=eabi -z -m"TMS570LC4357_UART_Boot.map" --heap_size=0x800 --stack_size=0x800 -i"C:/ti/ccs1010/ccs/tools/compiler/ti-cgt-arm_20.2.1.LTS/lib" -i"C:/ti/ccs1010/ccs/tools/compiler/ti-cgt-arm_20.2.1.LTS/include" --reread_libs --diag_wrap=off --display_error_number --warn_sections --xml_link_info="TMS570LC4357_UART_Boot_linkInfo.xml" --rom_model --be32 -o "TMS570LC4357_UART_Boot.out" $(ORDERED_OBJS)
	@echo 'Finished building target: "$@"'
	@echo ' '
	@$(MAKE) --no-print-directory post-build

TMS570LC4357_UART_Boot.bin: $(EXE_OUTPUTS)
	@echo 'Building files: $(strip $(EXE_OUTPUTS__QUOTED))'
	@echo 'Invoking: ARM Hex Utility'
	"C:/ti/ccs1010/ccs/tools/compiler/ti-cgt-arm_20.2.1.LTS/bin/armhex"  -o "TMS570LC4357_UART_Boot.bin" $(EXE_OUTPUTS__QUOTED)
	@echo 'Finished building: $(strip $(EXE_OUTPUTS__QUOTED))'
	@echo ' '
	@$(MAKE) --no-print-directory post-build

# Other Targets
clean:
	-$(RM) $(BIN_OUTPUTS__QUOTED)$(EXE_OUTPUTS__QUOTED)
	-$(RM) "Fapi_UserDefinedFunctions.obj" "bl_check.obj" "bl_flash.obj" "bl_main.obj" "bl_uart.obj" "bl_ymodem.obj" "sci_common.obj" "sw_hw_ver.obj" "ymodem_crc16.obj" "source\HL_epc.obj" "source\HL_errata.obj" "source\HL_errata_SSWF021_45.obj" "source\HL_esm.obj" "source\HL_gio.obj" "source\HL_nmpu.obj" "source\HL_notification.obj" "source\HL_pinmux.obj" "source\HL_rti.obj" "source\HL_sci.obj" "source\HL_sys_core.obj" "source\HL_sys_dma.obj" "source\HL_sys_intvecs.obj" "source\HL_sys_mpu.obj" "source\HL_sys_pcr.obj" "source\HL_sys_phantom.obj" "source\HL_sys_pmm.obj" "source\HL_sys_pmu.obj" "source\HL_sys_startup.obj" "source\HL_sys_vim.obj" "source\HL_system.obj" 
	-$(RM) "Fapi_UserDefinedFunctions.d" "bl_check.d" "bl_flash.d" "bl_main.d" "bl_uart.d" "bl_ymodem.d" "sci_common.d" "sw_hw_ver.d" "source\HL_epc.d" "source\HL_errata.d" "source\HL_errata_SSWF021_45.d" "source\HL_esm.d" "source\HL_gio.d" "source\HL_nmpu.d" "source\HL_notification.d" "source\HL_pinmux.d" "source\HL_rti.d" "source\HL_sci.d" "source\HL_sys_dma.d" "source\HL_sys_pcr.d" "source\HL_sys_phantom.d" "source\HL_sys_pmm.d" "source\HL_sys_startup.d" "source\HL_sys_vim.d" "source\HL_system.d" 
	-$(RM) "ymodem_crc16.d" "source\HL_sys_core.d" "source\HL_sys_intvecs.d" "source\HL_sys_mpu.d" "source\HL_sys_pmu.d" 
	-@echo 'Finished clean'
	-@echo ' '

post-build:
	-"C:/ti/ccs1010/ccs/utils/tiobj2bin/tiobj2bin.bat" "TMS570LC4357_UART_Boot.out" "TMS570LC4357_UART_Boot.bin" "C:/ti/ccs1010/ccs/tools/compiler/ti-cgt-arm_20.2.1.LTS/bin/ofd470" "C:/ti/ccs1010/ccs/tools/compiler/ti-cgt-arm_20.2.1.LTS/bin/hex470" "C:/ti/ccs1010/ccs/utils/tiobj2bin/mkhex4bin"
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY:

-include ../makefile.targets

