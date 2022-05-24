# FE16-AlgoDS-Day1-Sanja-Gerlinde

Basic
1. Guessing game
Let's play a little game to give you an idea of how different algorithms for the same problem can have wildly different efficiencies. The computer is going to randomly select an integer from 1 to N. You'll keep guessing numbers until you find the computer's number and the computer will tell you each time if your guess was too high or too low:

For instance,  if you selected 4, the computer will produce one of the following answers:


“My number is higher than 4, guess again higher!”

“My number is lower than 4, guess again lower!”

“You are correct - the random number is 4”


Create a flowchart and pseudocode that is guiding the computer.

Think about possible algorithmic approaches for a human player. Think about the optimal strategy (in terms of number of guesses), then formalize it in a flowchart/pseudocode.

Intermediate
2. Seconds to Week/Day/Hour/Minutes/Seconds


Create an algorithm  that prompts the user to enter an integer representing an elapsed time in seconds and  output it in the format “WW weeks DD days HH hours MM minutes and SS seconds.”

For example, if the user enters the number 2000000, the message

“3 weeks 2 days 3 hours 33 minutes and 20 seconds”

should be displayed. Use www.draw.io and/or pseudocode statements.


(Hint: you can use of the quotient and the remainder of an integer division)



3. ATM machine



Inside an ATM bank machine there are notes of 100, 50, 20, and 10 EUR. Create an algorithm that prompts the user to enter the amount of money he or she wants to withdraw (using an integer value) and then displays the least number of notes the ATM should give. For example, if the user enters an amount of 280 EUR, the algorithm should instruct the ATM to give:  


2 notes of 100 EUR,

1 note of  50 EUR,

1 note of 20 EUR and

1 note of 10 EUR.

b) Expand the procedure to a real-life case when, for instance, 50 EUR notes are not available anymore. Expand the algorithm to cover all denominations and handle the cases like “60 EUR is not possible, I do not have 10 EUR notes at this moment”  

c) At what point would you send a message to the bank that a specific ATM machine should be refilled?


d) If you enjoy mathematics, start reading here:

https://en.wikipedia.org/wiki/Greedy_algorithm

Challenge
4. Sorting & Co
You have been given a random array of numbers, like:

{1, 3, 5, 4, 5, 9, 6, 1, 2, 6, 5, 4, 4, 9, 7 }

Create an algorithmic procedure to sort this based on the “find maximum” brute force solution. 

Once you have created your initial algorithm, start reading:

https://en.wikipedia.org/wiki/Quicksort#Algorithm

https://www.geeksforgeeks.org/divide-and-conquer-introduction/


Play Video


5. Crossroad signalization


Create an algorithm that manages the crossroad´s light. What could be the input parameters?

Start thinking bigger - what, if you need to optimize the traffic lights of several junctions in your city? What are the parameters that you need to take into account (like date/time, rush hours, average speed of cars, average numbers of cars per lane in seconds etc. ) ?



6. Hunt the Pacman!


You are the Red Ghost (red character in the Pacman game) and you need to find the shortest way to the Pacman.

Create an optimal algorithm (www.draw.io  and/or pseudocode) that allows Red Ghost to get to Pacman’s current position in the shortest possible time.

What are the rules that the Pacman must follow (in regard to user input and game’s constraints)? For instance, it is obvious that once you know the Ghost’s algorithm, think about how the actual game is working (google “Play Pacman Online”). Obviously, not all ghosts are released at the same time, and they are also not always following the optimal (direct) route to the Pacman. Improve your initial algorithm to make the Pacman game more playable.  

