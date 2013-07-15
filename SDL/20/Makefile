CC	= g++

INC	= -I /usr/include/SDL
LIB	= -lSDL_image
all : lesson20

lesson20 : lesson20.o
	$(CC) -o $@ $< $(LIB)

lesson20.o : lesson20.cpp
	$(CC) -c $< $(INC)

clean :
	rm -rf lesson20 lesson20.o
