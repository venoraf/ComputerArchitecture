all: eighth

eighth: eighth.c
	gcc -lm -Wall -Werror -fsanitize=address -std=c11 eighth.c -o eighth

clean:
	rm -rf eighth
