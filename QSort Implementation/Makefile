# A simple Makefile
# Alex Nolan
# The compiler: gcc for C programs, g++ for C++ programs, etc

CC = gcc
CFLAGS=-g -Wall -pedantic-errors
TARGET = QSortANolan
all = $(TARGET)

$(TARGET): $(TARGET).c
	$(CC) $(CFLAGS) -o $(TARGET) $(TARGET).c 


clean:
	rm $(TARGET)
