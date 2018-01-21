CC=gcc
OBJ=main.o
IFLAG=-I ./include

all: $(OBJ)
	$(CC) -o ftps $(OBJ)

main.o: main.c
	gcc $(IFLAG) -c main.c

clean:
	rm *~ *.o ftps
