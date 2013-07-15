CC	= g++

INC	= -I /usr/include/SDL
LIB	= -lSDL_image -lSDL_ttf -lfreetype
all : lesson12

lesson12 : lesson12.o
	$(CC) -o $@ $< $(LIB)

lesson12.o : lesson12.cpp
	$(CC) -c $< $(INC)

clean :
	rm -rf lesson12 lesson12.o
