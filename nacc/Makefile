CFLAGS=-std=c11 -g -static

nacc: nacc.c

test: nacc
	./test.sh

clean:
	rm -f nacc *.o *~ tmp*

.PHONY: test clean
