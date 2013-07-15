CC	= g++

INC	= -I /usr/include/SDL
LIB	= -lSDL_image
all : lesson35

lesson35 : lesson35.o
	$(CC) -o $@ $< $(LIB)

lesson35.o : lesson35.cpp
	$(CC) -c $< $(INC)

clean :
	rm -rf lesson35 lesson35.o
