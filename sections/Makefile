CC=icc
CFLAGS=-Wall -O3 -qopenmp

sections : sections.c
	$(CC) -o $@ $< $(CFLAGS)

.PHONY: clean

clean :
	rm -f sections