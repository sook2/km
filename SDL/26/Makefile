CC	= g++

INC	= -I /usr/include/SDL
LIB	= -lSDL_image
all : lesson26

lesson26 : lesson26.o
	$(CC) -o $@ $< $(LIB)

lesson26.o : lesson26.cpp
	$(CC) -c $< $(INC)

clean :
	rm -rf lesson26 lesson26.o
