# Combinatorics-Simulator
A simulator for different combinatorics.
This is a fairly simple program that is here to share between different people easily, although peaple can use it if they want.

*Instructions for use:*
To use the simulator, simply call multiGuess(). There are a few parameters for the function that can be modified to get different results (all of these have a default value):

*Parameters*
n=5: Changing n will change the number of times the simulator runs (it will return an array of all of the results)
printing=False: Setting this to true will cause the simulator to print more detailed information about each run. Leaving it false will skip this information
fin=True: Leaving this as true will cause the simulator to end simulation by printing the average of all the attempts
word="ABC": This is the word or phrase that the simulator is attempting to guess. Longer words are generally harder to guess
letters=None: When left blank, this will automatically generate from the string ("ABC" -> ["A", "B", "C"]), but you can also pass in a list or a string. This will be the pool of letters the simulator is trying to guess the word *from*. If the word cannot be made from the letters, the simulator will be unable to finish. If two letters are the same, then they are interchangeable (e.g. "A"=="A", but "A"!="a")
circle=False: Setting this to true will allow the code to start matching the guess with the word from any point, e.g. when this is true, a guess of "BCA" will match the word/phrase "ABC"
combination=False: Setting this to true will allow the code to match the guess with the word in any order, e.g. when this is true, a guess of "DACB" will match the word/phrase "ABCD".