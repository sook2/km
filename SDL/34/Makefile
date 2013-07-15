CC	= g++

INC	= -I /usr/include/SDL
LIB	= -lSDL_image -lSDL_ttf -lfreetype
all : lesson34

lesson34 : lesson34.o
	$(CC) -o $@ $< $(LIB)

lesson34.o : lesson34.cpp
	$(CC) -c $< $(INC)

clean :
	rm -rf lesson34 lesson34.o
