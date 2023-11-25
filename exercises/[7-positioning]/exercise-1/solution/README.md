# Questions & Answers
1. Your only goal here is to align the .child element to the bottom right of the .parent element. 

In order to do that, we have learned that we need to set the positioning to absolute and define the bottom and right properties to 0, so that there is 0 space between those directions and the child element.

However, something a bit more inconspciuous was the fact that the .parent element has the positioning **static** by default. At one point in the text, it was mentioned that the .child element would only stick to elements whose positioning was anything **other** than static. So, if you happened to miss this property, it is very likely that your .child element stuck to the bottom right of the body, rather than the bottom right of the .parent element.
