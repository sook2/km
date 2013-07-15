CC	= g++

INC	= -I /usr/include/SDL
LIB	= -lSDL_image
all : lesson04

lesson04 : lesson04.o
	$(CC) -o $@ $< $(LIB)

lesson04.o : lesson04.cpp
	$(CC) -c $< $(INC)

clean :
	rm -rf lesson04 lesson04.o
