.PHONY all: hello hello.o

hello:
	nasm -f macho hello.asm

hello.o: hello.asm
	ld -o hello -e mystart hello.o -macosx_version_min 10.14.5 -lSystem

clean:
	rm hello hello.o
