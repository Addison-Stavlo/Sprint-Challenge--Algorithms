Add your answers to the Algorithms exercises here.
a) O(n^3) - must go through n*n*n operations according to the loop
b) O(n^4) - 4 levels of nested loops. even though most dont start at zero and start at (previous index + 1), it is very close to n^4, and as n -> infinity, O(solution) -> n^4
c) O(n) - recursive calls one at a time subtracting 1 from n with each call. only n calls can be made

i would conduct a binary search algorithm
i would pick a floor near the middle (or more closer to the bottom with the knowledge that eggs will probably not take many floors to break) and drop an egg. If the egg breaks, I only need to search the floors beneath that mark, if not only above. Then I can go to the midpoint of the section i know answer is in and drop another egg, repeat the process.
