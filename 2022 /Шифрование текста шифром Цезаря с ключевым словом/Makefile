clean: main
	del *.o
main:	main.o func.o keycezar.o dekeycezar.o 
	gcc -o Program main.o Func.o KeyCezar.o DeKeyCezar.o
main.o:
	gcc -c main.c -o main.o 	
func.o:
	gcc -c Func.c -o Func.o
keycezar.o:
	gcc -c KeyCezar.c -o KeyCezar.o
dekeycezar.o:
	gcc -c DeKeyCezar.c -o DeKeyCezar.o

