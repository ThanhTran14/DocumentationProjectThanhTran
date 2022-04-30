
TicTacToe   Github page: https://github.com/ThanhTran14/DocumentationProjectThanhTran 

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

4. Either download the files as a zip (green arrow) and then move the files into the command prompt or git clone into your file (red arrow). If downloaded the zip install WinSCP to move files into your directory/command line. Need to unzip the files.
![](Step2.jpg)

When running WinSCP there should be a window. For "Hostname" enter student2.cs.appstate.edu. Then for user name enter your userID from Appstate and hit login. Then it would ask for your password.
![winSCP1](https://user-images.githubusercontent.com/97632664/166092078-a58bca33-4f9f-4850-a5f0-708da5560af5.jpg)
![passwordwinSCP](https://user-images.githubusercontent.com/97632664/166092096-77f168ba-ffc1-4eec-8a32-4da8f763d0ae.jpg)

Then move the unzipped files into your directory by holding left click and dragging your mouse to the other window.
![drag](https://user-images.githubusercontent.com/97632664/166092202-a30f990d-b771-4a63-81f8-0430cda15240.jpg)



5. Use this line to compile the program : g++ -Wall -Werror -o tictactoe main.cc tictactoe.cc 
![compile](https://user-images.githubusercontent.com/97632664/166091865-10100696-dec4-4275-b4ab-fb345ade5d2c.jpg)

6. To run the program use ./tictactoe or tictactoe.

7. It would ask for Player 1 information it would ask for your first name and hit enter then it would ask for your age then hit enter.
![run](https://user-images.githubusercontent.com/97632664/166091951-7b580774-53ce-4be4-b383-6aefff93ac13.jpg)

8. It would do the same thing for Player 2

9. Make a valid command which would be RXCX the R meaning Row and C meaning Column, the program will keep repeating until a valid command.
![yourTurn](https://user-images.githubusercontent.com/97632664/166091966-caa61b10-b82c-43c3-bdb2-44639d51ab0a.jpg)

10. The game will end if there is a tie or someone wins.


#Functions of TicTacToe.

clearBoard()
It the method we use to clear the board so we just make it into a empty space
![ClearBoard](https://user-images.githubusercontent.com/97632664/166091788-8a3a9c97-85ee-474a-ae6c-783284a2dc6e.jpg)

getPlayerInfo()
It the method that would ask for you information and it accepts your information through the keyboard
![PlayerInfo](https://user-images.githubusercontent.com/97632664/166091791-65836be6-1c0c-476c-a39b-d3854e480c62.jpg)

printBoard()
It is the method to print out the board so you can see how it looks like. Then we made it so you can put the X or O there.
![printBoard](https://user-images.githubusercontent.com/97632664/166091793-7e20a17e-2d76-4b99-952c-f5a28da3590b.jpg)

printTurnHeader() 
It is the method to let you know whoever turn it is.
![printPlayerInfo](https://user-images.githubusercontent.com/97632664/166091792-627ecdde-1b3d-4bdc-9e80-49b57303d0de.jpg)

getMove()
It is the method to accept your import and it would check if the move is valid. If someone already placed their O or X that it would say it invalid and ask you again to place your move. It would also checked if you enter the right format.
![getMove](https://user-images.githubusercontent.com/97632664/166091796-07c92352-6e44-45c7-a50a-9ab16e5c315e.jpg)

checkWin()
It is the method where it checks if you win or not.
![checkWin](https://user-images.githubusercontent.com/97632664/166091799-97b5a31b-3d84-4dce-8bf5-23d87569757d.jpg)

checkTie()
It is the method where it checks if you have a tie.
![checkTie](https://user-images.githubusercontent.com/97632664/166091801-10858532-d777-489d-b4ab-a3a0c8975a99.jpg)

runGame()
It is the method that makes all these methods work together and in order. 
![runGame](https://user-images.githubusercontent.com/97632664/166091803-7b9cf793-3600-4fb1-b4b0-82eb2cdeceb3.jpg)

