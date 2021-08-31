mymake:mymake.o graph.o
	gcc mymake.o graph.o -o mymake
mymake.o:mymake.c graph.h
	gcc -Wall -g -c mymake.c
graph.o:graph.c graph.h
	gcc -Wall -g -c graph.c
