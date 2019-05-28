teston: test.o list.o
		cc -o teston test.o list.o
list.o: list.c list.h
		cc -std=c99 -c list.c
test.o: test.c list.h
		cc -std=c99 -c test.c

clean: 
		rm teston test.o list.o