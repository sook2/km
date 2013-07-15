CC	= g++

INC	= -I /usr/include/SDL
LIB	= -lSDL_image
all : lesson09

lesson09 : lesson09.o
	$(CC) -o $@ $< $(LIB)

lesson09.o : lesson09.cpp
	$(CC) -c $< $(INC)

clean :
	rm -rf lesson09 lesson09.o
