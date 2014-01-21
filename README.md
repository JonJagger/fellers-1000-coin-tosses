Fellers-1000-coin-tosses
========================

This is a simple active web-page to simulate lots of "Feller's walks".
Each walk is 1000 steps long, and at each step you flip a fair coin.
As you walk you keep a running total (starting at zero), 
  o) adding 1 to your total if you flip a head,
  o) subtracting 1 from your total if you flip a tail.

What will the cumulative total look like as the number of coin flips
progresses from 1 to 1000? 

Most people's intuition is that the total will hover around zero.
Does it?
Try it!
https://rawgithub.com/JonJagger/Fellers-1000-coin-tosses/master/fellers.html

How effective is feedback?
Every N steps (on average) intead of flipping the coin, you look at the total:
  o) if its negative (more tails than heads), pretend you 
     flipped a head, and add one to the total
  o) if its positive (more heads than tails), pretend you
     flipped a tail, and subtract one from the total.
To set a value of N click the re-run bottom at the bottom.


I discovered Feller's walk on page 77 of Don Reinersten's book
<a href="http://jonjagger.blogspot.co.uk/2012/06/principles-of-product-development-flow.html">
The Principles of Product Development FLOW</a>.
