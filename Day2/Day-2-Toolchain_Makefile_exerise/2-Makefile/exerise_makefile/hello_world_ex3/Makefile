CC=$(CROSS_COMPILE)gcc

CFLAGS=-Wl,-Map,out.map -lpthread -lm

all: hello_world

hello_world: hello_world.o hello_world_2.o

clean:
	rm -r *.o
	rm hello_world
