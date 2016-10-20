#Chaining Array Methods Exercise

##Instructions

Using the array below, perform the following operations:
`var integers = [13, 25, 6, 3, 11, 2, 18, 7, 21, 1, 29, 20, 12, 8];`

1. Sort the numbers in descending order (10, 9, 8, 7, etc).
  *I used the `.sort` method on the initial array. _Important to note here that this method requires a function in order to work on numbers_
2. Remove any integers greater than 19.
  *I used the `.filter` method with a function set to `return num <= 19`.
3. Multiply each remaining number by 1.5 and then subtract 1.
  *Again, because this is a number array and the order of the instructions, I had to use the `.map` method vice the `.forEach` method.
4. Then output (either in the DOM or the console) the sum of all the resulting numbers.
  * Here I used the `.reduce` method and declared a new variable equal to the id of the `<div>` in my HTML document where I wanted to write the number. I then used `.innerHTML` on that new variable to write the result to the DOM.
  
  
