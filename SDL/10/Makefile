CC	= g++

INC	= -I /usr/include/SDL
LIB	= -lSDL_image -lSDL_ttf -lfreetype
all : lesson10

lesson10 : lesson10.o
	$(CC) -o $@ $< $(LIB)

lesson10.o : lesson10.cpp
	$(CC) -c $< $(INC)

clean :
	rm -rf lesson10 lesson10.o
