#Montyhall

The player is shown 3 doors.
One door makes them a winner,
the other two make them a loser.
After they have chosen a door, "open" one of the other doors:
- If the door they picked was the winning door, randomly open one of the other two
- If the door they picked was a losing door, open the other losing door
Ask if they want to change their choice. If so, record their choice. Otherwise, keep their original choice.
Show whether they have ultimately picked the winning door.

#Example
The program secretly selects door 2 as the winning door.

Program : Choose which door you'd like to pick (1, 2, 3)
Player  : 2
Program : (shows door 3) -> goat
Program : Do you want to change your choice? Y/N
Player  : N

Program shows what is behind door 2 and declares the player a winner.

