#tic tac toe game
import random
#the game board
board = [0, 1, 2,
         3, 4, 5,
         6, 7, 8]

def show():
	print(boarrd[0],"|",board[1],"|",board[2])
	print("_______________________")
	print(boarrd[3],"|",board[4],"|",board[5])
	print("_______________________")
	print(boarrd[6],"|",board[7],"|",board[8])
	
    while true:
    input = raw_input("select the spot: ")
    input = int(input)

    if board[input] != "x" and board[input] != "o":
        board[input] = "x"

    while finding:
       random.seed() # gives a random generator
       opponent = random.randint(0,8)

       if board[opponent] != "o" and board[opponent] != "x":
       	   board[opponent] = "o"
           finding = false
    else:
        print("this spot is taken!")


    show()        	
