Fellers-1000-coin-tosses
========================

This is a simple html file which simulates lots "Feller's walks".
where each Feller's walk is a 1000 step walk as described in
Don Reinersten's book The Principles of Product Development FLOW
on page 77,78...

Image you have a fair coin, and you toss it 1000 times. Each time
if you get a head you add 1 to a total, if you get a tail you
subtract 1 from a total. What will the total look like as the
number of tosses progresses from 1 to 1000?

Most people's intuition is that the total will hover around zero.
However, as Don explains, this is not true.
This is the Diffusion Principle: Over time, queues will randomly
spin out of control and will remain in this state for long periods.
Or, to put it another way, you cannot rely on randomness to
correct a random queue.

The top graph shows the total at each step of a single 1000 step walk.
For example, a plotted point of [x=411,y=-53] means that in
that walk, after 411 coin tosses the total was -53.

The bottom-left graph shows cumulative frequency of the total
(at the end of the 1000 steps) for lots of walks.
For example, a plotted point a [x=-3, y=2903] this means that
after lots of walks (see legend in top graph) 2903 of them finished
with a total of -3.

The bottom right graph shows the cumulative frequency of the total
equalling zero at each step of the 1000 step walk.
For example, a plotted point of [x=45,y=611] means that on 611
occasions (of all the walks, see legend in top graph) the total
was zero at step 45. 
