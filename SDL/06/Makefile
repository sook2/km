CC	= g++

INC	= -I /usr/include/SDL
LIB	= -lSDL_image
all : lesson06

lesson06 : lesson06.o
	$(CC) -o $@ $< $(LIB)

lesson06.o : lesson06.cpp
	$(CC) -c $< $(INC)

clean :
	rm -rf lesson06 lesson06.o
