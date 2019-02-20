CC=icc
CFLAGS=-Wall -O3 -qopenmp

critical : critical.c
	$(CC) -o $@ $< $(CFLAGS)

.PHONY: clean

clean :
	rm -f critical