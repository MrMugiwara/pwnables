.PHONY: clean

all: clean server single_thread_server

server:
	gcc -m32 -ggdb -mpreferred-stack-boundary=2 -z execstack -fno-stack-protector -o server server.c
	
single_thread_server:
	gcc -m32 -ggdb -mpreferred-stack-boundary=2 -z execstack -fno-stack-protector -o single_thread_server single_thread_server.c
	
clean:
	rm -f server single_thread_server
