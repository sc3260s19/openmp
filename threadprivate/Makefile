CC=icc
CFLAGS=-Wall -O3 -qopenmp

threadprivate : threadprivate.c
	$(CC) -o $@ $< $(CFLAGS)

.PHONY: clean

clean :
	rm -f threadprivate