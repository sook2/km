CC	= g++

INC	= -I /usr/include/SDL
LIB	= -lSDL_image
all : lesson24

lesson24 : lesson24.o
	$(CC) -o $@ $< $(LIB)

lesson24.o : lesson24.cpp
	$(CC) -c $< $(INC)

clean :
	rm -rf lesson24 lesson24.o
