Add your answers to the Algorithms exercises here.

Exercise 1:

a:
If n is a negative number or is = 0, the while loop will evaluate to false and will not run.
If n is greater than 0 the while loop will run n times.
O(n)

b: O(n^3)

C: O(n) it will always run (bunnies) times

Exercise 2:

The first thing I would do is drop on egg from n/2 stories.
    
    If the egg breaks I would then drop on egg from (current floor)/2 stories. 

    If the egg doesn't break I would then drop an egg from its (current floor + (current floor * .5) stories. 
    (everytime the egg doesnt break height f will set to that current floor)

 I would keep re-using this same logic until the egg does not break.
    So each time the egg breaks, the current story it is being dropped from
    gets divided by two

    Each time the egg does not break, the current story gets multiplied by .5.