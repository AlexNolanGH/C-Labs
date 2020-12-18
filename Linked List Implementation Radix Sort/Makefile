# Radix Sorted Linked List Makefile
# Alex Nolan
# The compiler: gcc for C programs, g++ for C++ programs, etc


CC = gcc
CFLAGS = -g -Wall -O0 -pedantic-errors
TARGET = RadixSortANolan

all: $(TARGET)

$(TARGET): $(TARGET).c
	$(CC) $(CFLAGS) $(TARGET).c -o $(TARGET) -lm

clean: 
	rm -f $(TARGET)
