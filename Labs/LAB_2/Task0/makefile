all:count-words

count-words: count-words.o
	gcc -g -m32 -Wall -o count-words count-words.o

count-words.o: count-words.c
	gcc -g -m32 -Wall -c -o count-words.o count-words.c

.PHONY: clean
clean:
	rm -f *.o count-words
