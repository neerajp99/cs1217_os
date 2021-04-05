.c.o:
	gcc -c -g $*.c
hello: main.o dumb.o
	gcc -o hello main.o dumb.o
main.o: main.c dumb.h
dumb.o: dumb.c dumb.h