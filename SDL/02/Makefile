CC	= g++

INC	= -I /usr/include/SDL
LIB	= -lSDL
all : lesson02

lesson02 : lesson02.o
	$(CC) -o $@ $< $(LIB)

lesson02.o : lesson02.cpp
	$(CC) -c $< $(INC)

clean :
	rm -rf lesson02 lesson02.o
