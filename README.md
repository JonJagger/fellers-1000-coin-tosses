Fellers-1000-coin-tosses
========================

This is a simple html file using javascript to simulate lots
of "Feller's walks" where each Feller's walk is a 1000 step walk
as described on pages 77,78 of Don Reinersten's book
<a href="http://jonjagger.blogspot.co.uk/2012/06/principles-of-product-development-flow.html">
The Principles of Product Development FLOW</a>.

Image you have a fair coin, and you flip it 1000 times.
These 1000 coin flips comprise one walk.
For each walk, you start with a total of zero, and, each time
you flip the coin, you add 1 to your total if you get a head,
and you subtract 1 from your total if you get a tail.

What will the cumulative total look like as the number of coin flips
progresses from 1 to 1000? Most people's intuition
is that the total will hover around zero. However, as Don explains,
this is not true. 

How effective are occasional nudges back towards zero during the walk?

Try it!
https://rawgithub.com/JonJagger/Fellers-1000-coin-tosses/master/fellers.html
