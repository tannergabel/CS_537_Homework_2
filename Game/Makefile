all: bin/chance

bin/chance: obj/main.o
	gcc obj/main.o -o bin/chance

obj/main.o: lib/main.c
	gcc -Wall -c lib/main.c -o obj/main.o

clean:
	rm obj/*.o
	rm bin/*