CC	= g++

INC	= -I /usr/include/SDL
LIB	= -lSDL_image -lSDL_ttf -lfreetype -lSDL_mixer
all : lesson11

lesson11 : lesson11.o
	$(CC) -o $@ $< $(LIB)

lesson11.o : lesson11.cpp
	$(CC) -c $< $(INC)

clean :
	rm -rf lesson11 lesson11.o
