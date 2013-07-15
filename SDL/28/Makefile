CC	= g++

INC	= -I /usr/include/SDL
LIB	= -lSDL_image
all : lesson28

lesson28 : lesson28.o
	$(CC) -o $@ $< $(LIB)

lesson28.o : lesson28.cpp
	$(CC) -c $< $(INC)

clean :
	rm -rf lesson28 lesson28.o
