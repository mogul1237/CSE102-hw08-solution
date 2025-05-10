# CSE102-hw08-solution

Download Here: [CSE102#hw08 solution](https://jarviscodinghub.com/assignment/cse102hw08-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

In this homework, you will write a 2-player chess game using your hw#05. You will submit your homework via KADI. #function prototypes You will change the signature of isPieceMovable function, and implement some other functions, as well. You are expected to implement functions given below.
Signature
int isPieceMovable(char *board, char sc, int sr, char tc, int tr);
int isInCheck(char* board);
int makeMove(char *board, char sc, int sr, char tc, int tr);
Parameters
char* board : Board array (as defined in hw#05) char sc: The column of the piece at source int sr: The row of the piece at source char tc: The column of the piece at target int tr: The row of the piece at target
Return values and function definitions
isPieceMovable Defined in hw#05. isInCheck: Checks whether a king is in check or not. If white king is in check, returns 1 If black king is in check, returns 2 If there is no check, returns 0 makeMove: Moves a piece from source to destination if current player’s king is not in check and piece can move from source to destination. If player’s king is in check, move should not be made and board should remain same. If move is invalid, returns 0 If move is invalid because same player’s king is in check, returns 1 If move is valid, returns 2 If move is valid and opponent player’s king is in check, returns 3
#notes • You are free to write any additional functions. • You will use your own HW#05, using someone else’s homework will be regarded as cheating. • Sample main function and output of a sample run are given; you should not modify the given main function. • There are some limitations and modifications from classical chess game to make your homework much easier. You can see the some of them in sample run file. • The assignment must be your original work. Duplicate or very similar assignments are both going to be considered as cheating. • Ask your questions via moodle.
