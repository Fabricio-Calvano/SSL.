# Variables
CC = gcc
CFLAGS = -Wall -Wextra -g -std=c2x -pedantic-errors

# Regla principal: compila el ejecutable 'hello'
hello: hello.c
	$(CC) $(CFLAGS) hello.c -o hello

# Regla para ejecutar (Punto 3.f de la consigna)
run: hello
	./hello

# Regla para limpiar archivos generados
clean:
	rm -rf hello hello.dSYM output.txt