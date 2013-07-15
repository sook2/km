CC	= g++

INC	= -I /usr/include/SDL
LIB	= -lSDL -lGL -lGLU
all : lesson36

lesson36 : lesson36.o
	$(CC) -o $@ $< $(LIB)

lesson36.o : lesson36.cpp
	$(CC) -c $< $(INC)

clean :
	rm -rf lesson36 lesson36.o
