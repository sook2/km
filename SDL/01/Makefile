CC	= g++

INC	= -I /usr/include/SDL
LIB	= -lSDL
all : lesson01

lesson01 : lesson01.o
	$(CC) -o $@ $< $(LIB)

lesson01.o : lesson01.cpp
	$(CC) -c $< $(INC)

clean :
	rm -rf lesson01 lesson01.o
