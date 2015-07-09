A simple web-page to simulate lots of Feller's walks.
Each Feller's walk is 1000 steps long. At each step you flip a fair coin
and keep a running total (starting at zero), 
  o) adding one to the total if you flip a head,
  o) subtracting one from the total if you flip a tail.
How will the total behave as the walk proceeds?
Most people's intuition is that the total will hover around zero.
Does it? Find out!
https://rawgithub.com/JonJagger/Fellers-1000-coin-tosses/master/fellers.html

Every N steps (on average) intead of flipping the coin, you look at the total:
  o) if its negative (more tails than heads), pretend you 
     flipped a head, and add one to the total
  o) if its positive (more heads than tails), pretend you
     flipped a tail, and subtract one from the total.
This increases the likelihood of the total staying nearer zero.
How effective is this feedback? Find out!

I discovered Feller's walk on page 77 of Don Reinersten's excellent book The Principles of Product Development FLOW.
Here's <a href="http://jonjagger.blogspot.co.uk/2012/06/principles-of-product-development-flow.html">a blog entry</a> with some snippets from his book.
Here's <a href="http://jonjagger.blogspot.co.uk/2013/01/fellers-walk.html">another blog entry</a> on Feller's walk.
Here's <a href="http://jonjagger.blogspot.co.uk/2013/11/fun-with-feedback-frequency.html">yet another blog entry</a> detailing how to use this simulation and revealing how effective the feedback is.
