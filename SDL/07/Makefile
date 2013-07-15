CC	= g++

INC	= -I /usr/include/SDL
LIB	= -lSDL_image -lSDL_ttf -lfreetype
all : lesson07

lesson07 : lesson07.o
	$(CC) -o $@ $< $(LIB)

lesson07.o : lesson07.cpp
	$(CC) -c $< $(INC)

clean :
	rm -rf lesson07 lesson07.o
