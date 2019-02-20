CC=icc
CFLAGS=-Wall -O3 -qopenmp

hello : hello.c
	$(CC) -o $@ $< $(CFLAGS)

.PHONY: clean

clean :
	rm -f hello