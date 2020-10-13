#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) There is only one loop with a variable for a number. Therefore, it should be O(n)


b) There are two loops in this one each taking a number so, O(n) * O(n) should be O(n^2)


c) There is a recursive loop taking going through each bunny. So it should be O(n)

## Exercise II

I think binary search could be good hear because you can either go up or down basically. I also assume that doesn't just break on the first floor. 

I would find the middle floor first and drop the egg. If it breaks, we can through out the top floors from that point and move half way down the remaining floors. If the egg survives, you can throw away the bottom floors from that point and move half way up the top floors. Repeat the instructions above until only one floor remains. 
