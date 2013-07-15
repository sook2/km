CC	= g++

INC	= -I /usr/include/SDL
LIB	= -lSDL_image
all : lesson32

lesson32 : lesson32.o
	$(CC) -o $@ $< $(LIB)

lesson32.o : lesson32.cpp
	$(CC) -c $< $(INC)

clean :
	rm -rf lesson32 lesson32.o
