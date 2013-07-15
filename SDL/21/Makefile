CC	= g++

INC	= -I /usr/include/SDL
LIB	= -lSDL_image
all : lesson21

lesson21 : lesson21.o
	$(CC) -o $@ $< $(LIB)

lesson21.o : lesson21.cpp
	$(CC) -c $< $(INC)

clean :
	rm -rf lesson21 lesson21.o
