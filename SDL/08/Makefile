CC	= g++

INC	= -I /usr/include/SDL
LIB	= -lSDL_image -lSDL_ttf -lfreetype
all : lesson08

lesson08 : lesson08.o
	$(CC) -o $@ $< $(LIB)

lesson08.o : lesson08.cpp
	$(CC) -c $< $(INC)

clean :
	rm -rf lesson08 lesson08.o
