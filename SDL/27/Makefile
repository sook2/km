CC	= g++

INC	= -I /usr/include/SDL
LIB	= -lSDL_image
all : lesson27

lesson27 : lesson27.o
	$(CC) -o $@ $< $(LIB)

lesson27.o : lesson27.cpp
	$(CC) -c $< $(INC)

clean :
	rm -rf lesson27 lesson27.o
