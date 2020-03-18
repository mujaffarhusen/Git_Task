all:add.o sub.o main.o
	cc main.o add.o sub.o
main.o:main.c
	cc -c main.c
add.o:add.c
	cc -c add.c
sub.o:sub.c
	cc -c sub.c
clean:
	rm -rf *.o
	rm -rf a.out 
