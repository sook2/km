CC	= g++

INC	= -I /usr/include/SDL
LIB	= -lSDL_image
all : lesson18

lesson18 : lesson18.o
	$(CC) -o $@ $< $(LIB)

lesson18.o : lesson18.cpp
	$(CC) -c $< $(INC)

clean :
	rm -rf lesson18 lesson18.o
