CC	= g++

INC	= -I /usr/include/SDL
LIB	= -lSDL_image
all : lesson16

lesson16 : lesson16.o
	$(CC) -o $@ $< $(LIB)

lesson16.o : lesson16.cpp
	$(CC) -c $< $(INC)

clean :
	rm -rf lesson16 lesson16.o
