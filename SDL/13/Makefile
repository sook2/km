CC	= g++

INC	= -I /usr/include/SDL
LIB	= -lSDL_image -lSDL_ttf -lfreetype
all : lesson13

lesson13 : lesson13.o
	$(CC) -o $@ $< $(LIB)

lesson13.o : lesson13.cpp
	$(CC) -c $< $(INC)

clean :
	rm -rf lesson13 lesson13.o
