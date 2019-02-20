CC=icc
CFLAGS=-Wall -O3 -qopenmp

reduce : reduce.c
	$(CC) -o $@ $< $(CFLAGS)

.PHONY: clean

clean :
	rm -f reduce