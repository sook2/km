CC	= g++

INC	= -I /usr/include/SDL
LIB	= -lSDL_image
all : lesson31

lesson31 : lesson31.o
	$(CC) -o $@ $< $(LIB)

lesson31.o : lesson31.cpp
	$(CC) -c $< $(INC)

clean :
	rm -rf lesson31 lesson31.o
