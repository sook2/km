CC	= g++

INC	= -I /usr/include/SDL
LIB	= -lSDL_image
all : lesson19

lesson19 : lesson19.o
	$(CC) -o $@ $< $(LIB)

lesson19.o : lesson19.cpp
	$(CC) -c $< $(INC)

clean :
	rm -rf lesson19 lesson19.o
