# Connect-Four-Game Using C#
Desktop Application C# .NET Framework using GDI+, Threading, TCP protocol which applies socket programming and Filestream
Connect Four is a classic two-player game where the objective for a player is to be the first one to form four of their game coins in either a horizontal, vertical, or diagonal line.
Players can join an existing Room or create their own Room and configure its size
If a room is full other users can join it as spectators and watch the ongoing game also they can leave watching any time
After the game end players have two options -> play again in the same room or leaving room and choose another one
Data of the game ( players name, winner, Date, RoomNo ) are written in a text file on your PC

Features:
1)	Server start and wait for players 
2)	Player1(owner of room) create a new room 
3)	Player2 shows to him all the available rooms 
4)	Player2 join a room with the room id
5)	In the loopy there is (a room name list, number of players list, rooms id) and (create button, join button, watch button)
6)	If the player2 wants to join the room, there is a request join sent to the owner 
7)	The game start when the owner accepts the player2 join
8)	There is a chat between players during the game 
9)	When player2 lose there is a massage box appear says you want play again? If it no, then the player2 leave the game and if the owner presses no then the player2 will leave the game also 
10)	When the session ends (one of the players does not want to play again) There is a text file saves the player1 name with his score and palyer2 name with his score and the date of the game you will find the txt file named by a room name in the debug folder in server side folder 




