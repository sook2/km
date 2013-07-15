CC	= g++

INC	= -I /usr/include/SDL
LIB	= -lSDL_image
all : lesson30

lesson30 : lesson30.o
	$(CC) -o $@ $< $(LIB)

lesson30.o : lesson30.cpp
	$(CC) -c $< $(INC)

clean :
	rm -rf lesson30 lesson30.o
