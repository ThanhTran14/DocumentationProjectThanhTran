
TicTacToe   Github page: https://github.com/ThanhTran14/DocumentationProjectThanhTran (Don't know if the pictures would work)

Documentation Project

By: Thanh Tran


Introduction

This is a documentation of a tictactoe program. This implementation is a Player vs Player so you need to have a friend to play with. Each player would get their turns and it would alternate unti it eithers end in a win or tie.


#How to install

Installed need files here: https://github.com/ThanhTran14/TicTacToe


#How to Start it Up

1. Need to installed either Putty or VSCode.

![Photos for Documentation](./Step1.jpg)

![Photos for Documentation](./Step1pt2.jpg)

2. If you are ASU student you can access to the student2 machine to sign in you have userID@student2.cs.appstate.edu then your password should default to your BannerID. 

3 (Putty). On Putty there is a header named "Host Name (or IP Address)" put in your userID@student2.cs.appstate.edu. Another window should pop up asking for your password. 

![Real Step 2](https://user-images.githubusercontent.com/97632664/165152707-46b8eaad-6c7e-4e9e-847d-f77fc0f747c5.jpg)

3 (VS Code). Downlaod a extenstion called RemoteSSH. Hit the green icon on the bottom left. Hitting these there should be a drop window and hit "Connect to Host". Insert your userID@student2.cs.appstate.edu and password. It may ask multiple times to insert passwrod.


Extension > Search Bar > type in Remote SSH > install it > click green bottom left > Connect to Host > type in appstateuserID@student2.cs.appstate.edu > your password (default your BannerID) > hit Explorer > click ok (blue arrow) > new terminal (red arrow)

The terminal is like Putty part

Below are some photos
![Step3VS1R](https://user-images.githubusercontent.com/97632664/166091385-9ac2a54d-859c-434f-a600-2a0daeaabf5f.jpg)
![Step3VS2R](https://user-images.githubusercontent.com/97632664/166091404-9ab77904-ab1e-4fe5-b598-101df4b128fb.jpg)
![Step3VS3R](https://user-images.githubusercontent.com/97632664/166091418-f04aea12-bae4-4fa1-aed4-60304278899b.jpg)
![Step3VS4R](https://user-images.githubusercontent.com/97632664/166091422-23571abd-4e57-48da-be08-ed03e22eac3c.jpg)
![Step3VS5R](https://user-images.githubusercontent.com/97632664/166091448-79a779ac-beae-47af-a029-bdd61f1fab89.jpg)
![Step3VS6R](https://user-images.githubusercontent.com/97632664/166091467-dc72a197-d573-4b6c-b058-363cac699011.jpg)
![Step3VS67jpgR](https://user-images.githubusercontent.com/97632664/166091490-94cf5cda-3b3b-4cfc-af52-305bb90abb05.jpg)
![Step3VS8jpgR](https://user-images.githubusercontent.com/97632664/166091506-28f5ee47-0555-4cde-aac1-5961ea81854d.jpg)


(Optional) Can make a directory to make things organize. To do this: mkdir whatevernameyouwant

3. Either download the files as a zip (green arrow) and then move the files into the command prompt or git clone into your file (red arrow). If downloaded the zip install WinSCP to move files into your directory/command line.
![](./Step2.jpg)

3. Use this line to compile the program : g++ -Wall -Werror -o tictactoe main.cc tictactoe.cc 

1[](./

4. To run the program use ./tictactoe or tictactoe.

5. It would ask for Player 1 information it would ask for your name then it would ask for you age.

6. It would do the same thing for Player 2

7. Make a valid command which would be RXCX the R meaning Row and C meaning Column, the program will keep repeating until a valid command.

8. The game will end if there is a tie or someone wins.


#Functions of TicTacToe.

clearBoard()
It the method we use to clear the board so we just make it into a empty space

getPlayerInfo()
It the method that would ask for you information and it accepts your information through the keyboard

printBoard()
It is the method to print out the board so you can see how it looks like. Then we made it so you can put the X or O there.

printTurnHeader() 
It is the method to let you know whoever turn it is.

getMove()
It is the method to accept your import and it would check if the move is valid. If someone already placed their O or X that it would say it invalid and ask you again to place your move. It would also checked if you enter the right format.

checkWin()
It is the method where it checks if you win or not.

checkTie()
It is the method where it checks if you have a tie.

runGame()
It is the method that makes all these methods work together and in order. 

