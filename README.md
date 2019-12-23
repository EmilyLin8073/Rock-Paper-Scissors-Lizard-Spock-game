# Rock-Paper-Scissors-Lizard-Spock-game

A Rock, Paper, Scissors, Lizard, Spock game. 
This is an augmented version of the traditional Rock, Paper, Scissors game. 
The implementation will be a two player game where each player is a separate client and the game is run by a server. 
The server and clients will use the same machine; with the server choosing a port on the local host and clients knowing 
the local host and port number. Each round of the game will be worth one point. 
Games will be played until one of the players has three points. 
At the end of each game, each user will be able to play again or quit.
All networking is done utilizing Java Sockets. 
The server handle each client on a separate thread.
