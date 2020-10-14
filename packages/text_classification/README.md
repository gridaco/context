# UI Text Classification
classifiies the class of text content by just looking in to it's content. (base language en-US)

> For example, Button detection will use text classicifation for calculating the score of button probability, So that NLP side should work as stand-alone. To recap, It should not have any other context than the Text UI Element it self, Such as text content, length, size(px), color (bg & front) . Such thing like position, transform must not be a property to be featured.





## Properties

- pos
- lenght
- size
- color
  - text color
  - bg color of text (back layer of it)



## Input

* text content
* visual



## Classes

* button
* title
* subtitle
* caption
* paragraph