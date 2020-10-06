hello_world: hello_world.o
	clang++ -o hello_world hello_world.o

hello_world.o: hello_world.cpp
	clang++ -std=c++17 -c -g -Wall -pedantic -Werror -o hello_world.o hello_world.cpp
