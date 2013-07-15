CC	= g++

INC	= -I /usr/include/SDL
LIB	= -lSDL_image
all : lesson22

lesson22 : lesson22.o
	$(CC) -o $@ $< $(LIB)

lesson22.o : lesson22.cpp
	$(CC) -c $< $(INC)

clean :
	rm -rf lesson22 lesson22.o
