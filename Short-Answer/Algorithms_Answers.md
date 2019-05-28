Add your answers to the Algorithms exercises here.
a) O(n) - must go through n operations to break out of the loop. say n = 2, loop requires a being higher than 8, adds 4 each time. 4x2 = 8, n = 3, loop requires 27 to break, adds 9 each time, 9x3 = 27.. etc.. this is linear
b) O(n^3) - 4 levels of nested loops all looping through the size of n except for the last only looping through a constant amount of times.
c) O(n) - recursive calls one at a time subtracting 1 from n with each call. only n calls can be made

i would conduct a binary search algorithm
i would pick a floor near the middle (or more closer to the bottom with the knowledge that eggs will probably not take many floors to break) and drop an egg. If the egg breaks, I only need to search the floors beneath that mark, if not only above. Then I can go to the midpoint of the section i know answer is in and drop another egg, repeat the process.
