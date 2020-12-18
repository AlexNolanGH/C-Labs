# A simple Makefile
# Alex Nolan
# Byte Binary Conversion
# The compiler: gcc for C programs, g++ for C++ programs, etc

CC = gcc
CFLAGS=-g -Wall
TARGET = ByteBinaryConversionANolan
all = $(TARGET)

$(TARGET): $(TARGET).c
	$(CC) $(CFLAGS) -o $(TARGET) $(TARGET).c -lm


clean:
	rm $(TARGET)
