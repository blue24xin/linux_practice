

.PHONY :all
all:client server

client:client.c
	clang -o client client.c
server:server.c
	clang -o server server.c

.PHONY :clean
clean:
	rm -rf client server
