CC	= g++

INC	= -I /usr/include/SDL
LIB	= -lSDL_image -lSDL_ttf -lfreetype
all : lesson14

lesson14 : lesson14.o
	$(CC) -o $@ $< $(LIB)

lesson14.o : lesson14.cpp
	$(CC) -c $< $(INC)

clean :
	rm -rf lesson14 lesson14.o
