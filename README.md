<h1><a href = "https://github.com/YaakovBaker/Rock-Paper-Scissors"><Strong>Rock, Paper, Scissors</Strong></a></h1>

<h3><Strong>Summary</Strong></h3>
  <p><br>•	Built a command line rock, paper, scissors game in Java. Printed to the terminal are the rules and instructions. The user must input how many wins they want to play to, so if they input 5 then the user or program, whichever reaches 5 wins first, wins the game. The program then randomly picks rock, paper, or scissors from an array of choices before the user does. The user then types their choice and the program compares the choices to see who wins the round and keeps track of the score and prints it to the terminal after each round. When a player reaches the goal and wins the program prints to the terminal the final score and messages depending on wether the user won or lose. There are also some command arguments like end then the program is terminated. There is also an easter egg.</p> 
  
 
 <h3><a href = "https://github.com/YaakovBaker/Rock-Paper-Scissors/blob/main/rpsgame/src/main/java/game/rps/project/Game.java"><Strong>Game.java</Strong></a></h3>
 <p><br>• <i>Game.java</i> is an interface that that declares a few methods that would be common in any game. The other purpose for creating this interface is that at the time I made this in Intro to Computer Science the topic we were learning was interfaces and I wan't to get some practice with them.</P>
 
 <h3><a href = "https://github.com/YaakovBaker/Rock-Paper-Scissors/blob/main/rpsgame/src/main/java/game/rps/project/rpsgame/RockPaperScissorsRunner.java"><Strong>RockPaperScissorsRunner.java</Strong></a></h3>
 <p><br>• <i>RockPaperScissorsRunner.java</i> is the class that is run to start my command line rock, paper, scissors game. It uses the <b>Scanner</b> object from <b>java.util.Scanner</b> to read user input like their name, how many points they want to play to and which version of the game they'd like to play. It then sets the game to be played to 5 points if the user inputed a number less than 0. Afterwards it constructs the <b>RockPaperScissors</b> object from <i>RockPaperScissors.java</i> and calls the <i>rules()</i> to print out the rules of the game and <i>game()</i> to start the game.</p>
 
 
<h3><a href = "https://github.com/YaakovBaker/Rock-Paper-Scissors/blob/main/rpsgame/src/main/java/game/rps/project/rpsgame/RockPaperScissors.java"><Strong>RockPaperScissorsRunner.java</Strong></a></h3>
<p><br>• <i>RockPaperScissors.java</i> is an object to be constructed by my runner class. This object contains logic for printing out the rules and starting the game as well as private methods to help make the code cleaner inside the game method. rules() simply prints out the rules of the game and game() contains the real stuff like the game creation and logic. game() begins by constructing a <b>Scanner</b> object from <b>java.util.Scanner</b> to read user input like their choice of rock, paper, or scissors and end to stop the game. The program then prints out the iconic phrases of "Rock! Paper! Scissors! Shoot!" with a slight delay to each print of those words like one does when actually playing rock, paper, scissors. The user then inputs their choice and the program randomly picks one of the options: rock, paper, scissors. Then with some basic logic it determines the winner and awards that player with a point. Once a player wins the game ends and a different message is printed out depending on who won.</P>




<p>There are a few kinks to the programs as I haven't started the second RockPaperScissors game yet. I plan to improve the logic and flow of these classes when I have sufficient free time, but I have more important priorities at the moment.</p>
