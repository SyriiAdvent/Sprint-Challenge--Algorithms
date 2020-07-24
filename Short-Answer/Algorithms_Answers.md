#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) This function is O(n) Big-O doesn't care about O(3n) or O(n + n)
 Its just in plain terms O(n) No matter what the input is, it will be a loop of how big n is.


b) O(nlogn) if n is 10, the function while loop will run 4 times then break. then the for loop still has to run 9 more times (without the while loop activating)
Two loops with j being altered based on n times. (n log n)


c) Im not sure if this was a trick question? anything bigger then a 0 would be a infinite loop. Still O(n) technically though
## Exercise II

# use a while loop to determine if current floor n/2 egg toss doesnt break egg
# if it does I would divide that number in half again to a lower floor to see if it breaks again.
# Repeat until I find a safe floor then increment up floors divided by the previous non safe floor.
# With this method I reduce the amount of eggs tossed and broken by 
# O(Log n)