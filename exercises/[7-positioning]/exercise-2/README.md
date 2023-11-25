# Positioning - exercise 2

This is meant to be solved after reading through the **Positioning** chapter of the book.

## Goal/s
1. Using positioning, make the header provided stick to the top of the page as the user scrolls.

## Starting indications 
All properties needed to solve this exercise can be found within the **Positioning** chapter of the book. 

For this exercise, you can see that some CSS code has already been provided for you.

There are some interesting things that you can keep in mind out of the scope of this exercise, so it is well worth it to pay attention at this section as well:

First of all, using the universal selector at the top of the page, you can see a quite interesting structure. It is used in many codespaces, and it is all connected to things we have already learned about. It is used so that no element on the page has already-defined padding or margin, and the padding and border are included in the calculation of the total height and width. For many web browsers, there are already defined style sheets, that at times may put pre-defined margin on elements like the body. This is a great way to reverse that without writing too much code. 

Secondly, we select the body and give it a height of 400vh. vh means 'viewport height', so we basically just give the body a height of 4 times our device height.

Thirdly, the header has an interesting color, using a bit of opacity. ( in this case, the opacity is set to 80% or 0.8 ). We also set the width and height, because, since it has no content, it would be invisible otherwise.


## Solution
If, at any point during this exercise, you get stuck and want to see the correct solution, you can access the 'solution' folder, where you will notice:
1. The same files, only modified to reveal the correct solution.


