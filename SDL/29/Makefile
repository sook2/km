CC	= g++

INC	= -I /usr/include/SDL
LIB	= -lSDL_image
all : lesson29

lesson29 : lesson29.o
	$(CC) -o $@ $< $(LIB)

lesson29.o : lesson29.cpp
	$(CC) -c $< $(INC)

clean :
	rm -rf lesson29 lesson29.o
