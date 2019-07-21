.PHONY all: header print_hex

header:
	nasm multiboot_header.asm
print_hex:
	hexdump -x multiboot_header
clean:
	rm multiboot_header
