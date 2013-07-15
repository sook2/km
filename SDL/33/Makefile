CC	= g++

INC	= -I /usr/include/SDL
LIB	= -lSDL_image
all : lesson33

lesson33 : lesson33.o
	$(CC) -o $@ $< $(LIB)

lesson33.o : lesson33.cpp
	$(CC) -c $< $(INC)

clean :
	rm -rf lesson33 lesson33.o
