all: 
	@echo "kompilacja: "
	gcc -lm -g -o program Source.c add.s

test: program
	@echo "test: "	
	./program
clean:
	@echo "Czyszczenie katalogu: "
	rm -rf *.o
	rm program
