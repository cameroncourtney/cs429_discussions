# Usage:
# make        # compile all binary
# make clean  # remove ALL binaries and objects

.PHONY = all clean

CC = gcc
CFLAGS = --std=c99 -g -Wall -Wextra -Werror

all: hello

hello: hello.o func.o
	$(CC) $(CFLAGS) -o hello hello.o func.o

hello.o: hello.c hello.h
	$(CC) $(CFLAGS) -c hello.c

func.o: func.c
	$(CC) $(CFLAGS) -c func.c

clean:
	rm -f hello *.o
