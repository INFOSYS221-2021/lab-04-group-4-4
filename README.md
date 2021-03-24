# Lab-04
## Group 4.4
## Names:
### Andrew Bolton, Daniyal Mahmood, Nicholas Challinor
Update this README to include your team name and team members. Don't forget to record all your answers to lab 04 here.

##### Exercise ONE
* 1
     - String (letter = "")
    - List (dupeBoard = [])
     - Boolean (gameIsPlaying = True)
 
 * 2
    - Value Variables
        - theBoard = [' '] * 10
        - turn = 'computer'
    - Reference Variables
        - move = getComputerMove(theBoard, computerLetter) 

 * 3
    - drawBoard(theBoard)<br>
    print('Hooray! You have won the game!')<br>
    gameIsPlaying = False
    
 * 4
    - if letter == 'X':<br>
    return ['X', 'O']<br>
    else:<br>
    return ['O', 'X']

* 5
     - dupeBoard = []<br>
     for i in board:<br>
          dupeBoard.append(i)
          
* 6
     - theBoard = [' '] * 10<br>
     There is 10 empty items in the list
     
* 7
     - def getBoardCopy(board):<br>
     dupeBoard = []<br>
     for i in board:<br>
     dupeBoard.append(i)<br>
     return dupeBoard<br>
     This function loops through the 'board' parameter and appeands each item to another list, then returns that new list
     
* 8
     - isWinner
          - This compares if there are 3 of the same entries (X or O) in a row. If it returns true, then it stops the game, but if false then it continues.
     - isBoardFull
          - This checks if there are any free spaces on the board to input. If there are no free spots, then the game ends and its a tie
* 9
     - No it will not change the behaviour of the program. The break is used to get out of the current iteration of the while loop, and move on to the next, so by changing that line to gameIsPlaying = False, it will stop the current iteration, and move on with the next iteration.

* 10
     - while True means that it will keep repeating infinitely until the a 'break' is hit
     
