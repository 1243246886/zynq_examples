###########################################
#Makefile for simple programs
###########################################
INC= -I../xlib/
LIB= 

CC=gcc
CC_FLAG=-Wall 

PRG=main
OBJ=main.o  ../xlib/xil_dma.o

$(PRG):$(OBJ)
	$(CC)  -o $@ $(OBJ) $(INC) $(LIB)
	
.SUFFIXES: .c .o .cpp
.cpp.o:
	$(CC)  -c $*.cpp -o $*.o $(INC) $(LIB)

.PRONY:clean
clean:
	@echo "Removing linked and compiled files......"
	rm -f $(OBJ) $(PRG)
