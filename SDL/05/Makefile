CC	= g++

INC	= -I /usr/include/SDL
LIB	= -lSDL_image
all : lesson05

lesson05 : lesson05.o
	$(CC) -o $@ $< $(LIB)

lesson05.o : lesson05.cpp
	$(CC) -c $< $(INC)

clean :
	rm -rf lesson05 lesson05.o
