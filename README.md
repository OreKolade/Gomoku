Currently finding my way through python.

Note this code is a revisitation of a sizable project in my first year com-sci class.  Wasn't able to finish it with my teammate and didn't understand how to code yet.(Project Linked in a folder )

This is my first try after a year 😃 , and with a more dedicated mindset to go beyond the basics  .  

My Thought Process for this Code.
    The computer (which plays with the black stones) always moves first. After the first move, the user’s and the computer’s moves alternate. The computer determines its move by finding the move that maximises the return value of the score function (which is provided by the Professor of the Course;haven't matured yet to fully code a decent AI based on mathematics and not If/Else statements  ).

Functions in the code accepts board as one of its arguments.The square (y,x) on the board is stored in board[y][x]. The value of the square is:
• " ", if the square is empty,
• "b", if the square has a black stone on it, and
• "w", if the square has a white stone on it.

Functions Written by the Professor:-
	• print_board(board)
      This function prints out the Gomoku board
	• score(board)
      This function computes and returns the score for the position of the board. It assumes that black
      has just moved
  • play_gomoku(board_size)
      This function allows the user to play against a computer on a board of size board size × board size.
  •put_seq_on_board(board, y, x, d_y, d_x, length, col)
      This helper function adds the sequence of stones of colour col of length length to board , starting
      at location (y,x) and moving in the direction (d_y, d_x). This function facilitates the testing of
      the AI engine.

  •analysis(board):
      This function analyses the position of the board by computing the number of open and semi-open
      sequences of both colours
  
Functions Written by Me:-
•    is_empty(board)
•    is_bounded(board, y_end, x_end, length, d_y, d_x)
•    detect row(board, col, y start, x start, length, d y, d x)
•    detect rows(board, col, length)
•    search max(board)
•    is win(board)

Hopefully , I plan tto expand the project and make a decent visual UI for the project 
Something like this:-

