CC	= g++

INC	= -I /usr/include/SDL
LIB	= -lSDL_image
all : lesson15

lesson15 : lesson15.o
	$(CC) -o $@ $< $(LIB)

lesson15.o : lesson15.cpp
	$(CC) -c $< $(INC)

clean :
	rm -rf lesson15 lesson15.o
