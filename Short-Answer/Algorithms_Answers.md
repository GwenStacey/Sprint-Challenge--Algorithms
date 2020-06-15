#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)O(log(n)) We're adding a significant portion of the limiter each time, should take nearly as many as n steps


b)O(log(n)) We're doubling our potential answer every time, cutting the distance very potentially in half and growing exponentially closer to our target.


c)O(n) Should never need to recurse more times than there are bunnies

## Exercise II

Start at the first floor, drop an egg, does it break? If we're on the first floor and we can say yes, F is 1. Other wise, we'd want to move up two floors at a time, dropping an egg every time we stopped. Once we got our first break, we'd want to go back one floor and drop again to be sure F wasn't the previous floor. If the egg doesn't break on the previous floor, current floor value is F otherwise previous floor value is F.

I think this would be O(n) because it would be O(n/2) but we don't care about that.
