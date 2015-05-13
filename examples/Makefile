TARGET = Main
CC = g++
LFLAGS = -Wall -pthread

CFLAGS_LOW = -Wall -Wshadow -Werror -O3
CFLAGS_MID = $(CFLAGS_LOW) -Weffc++ -pedantic -std=c++0x 
CFLAGS_HIGH = $(CFLAGS_MID) -Wextra 
CFLAGS_DEBUG = -g -O0 

CFLAGS = $(CFLAGS_LOW) -pthread #$(CFLAGS_DEBUG) 

INCLUDE_FOLDERS= ../ ../Common/ 
OBJECT_FOLDERS= ./ ../Common/ 

OUTPUT_DIR=./

#Bulk of work automatically handled
include ../WillMake

