CC	= g++

INC	= -I /usr/include/SDL
LIB	= -lSDL_image
all : lesson17

lesson17 : lesson17.o
	$(CC) -o $@ $< $(LIB)

lesson17.o : lesson17.cpp
	$(CC) -c $< $(INC)

clean :
	rm -rf lesson17 lesson17.o
