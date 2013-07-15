CC	= g++

INC	= -I /usr/include/SDL
LIB	= -lSDL_image -lSDL_ttf -lfreetype
all : lesson23

lesson23 : lesson23.o
	$(CC) -o $@ $< $(LIB)

lesson23.o : lesson23.cpp
	$(CC) -c $< $(INC)

clean :
	rm -rf lesson23 lesson23.o
