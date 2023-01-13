AS=nasm
CFLAGS=-g -f elf32 -g -F dwarf

NAME=hexDumpUtility

all:
	$(AS) $(CFLAGS) $(NAME).asm
	ld -m elf_i386 -o $(NAME) $(NAME).o

clean:
	rm $(NAME).out
