CC	= g++

INC	= -I /usr/include/SDL
LIB	= -lSDL_image
all : lesson25

lesson25 : lesson25.o
	$(CC) -o $@ $< $(LIB)

lesson25.o : lesson25.cpp
	$(CC) -c $< $(INC)

clean :
	rm -rf lesson25 lesson25.o
