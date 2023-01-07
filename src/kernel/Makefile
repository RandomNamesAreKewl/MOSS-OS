BUILD_DIR?=build/
ASM?=nasm

.PHONY: all clean

all: kernel

kernel: $(BUILD_DIR)/stage1.bin

$(BUILD_DIR)/kernel.bin:
	$(ASM) main.asm -f bin -o $(BUILD_DIR)/kernel.bin
