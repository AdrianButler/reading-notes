# Reading 3

## HTML

1. When should you use an unordered list in your HTML document?
   - Whenever you have a list that has no order/numbering to it
2. How do you change the bullet style of unordered list items?
   - `list-style: none;` 
3. When should you use an ordered list vs an unordered list in your HTML document?
   - Anytime you need things ordered in a certain way use ordered. For example saying who got first, second, and third place in a race.
4. Describe two ways you can change the numbers on list items provided by an ordered list?
   - `type: a;` or `type: i;`

## CSS

1. Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?
   - Padding is thickness of a wall for a house, margin is like the yard surrounding the house.
2. List and describe the four parts of an HTML elements box as referred to by the box model.
   - inline-size, block, width, height.

## JS

1. What data types can you store inside an Array?
   - Whatever data type you want.
2. Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?
>  const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
   - Yes it is a valid array. You can select data like this `people[arrayToPick][indexInsideSaidArray]` the statement `people[0][1]` would pick 32.
4. List five shorthand operators for assignment in javascript and describe what they do.
   - x++ adds 1, x-- subtracts 1, x+=5 adds five to x, x*=5 multiplies x by 5, x/=5 divides x by 5.
5. Read the code below and evaluate the last expression and explain what the result would be and why.
> let a = 10;  
> let b = 'dog';  
> let c = false;  
> (a + c) + b;

- "10dog" a + c = 10 and added a string to a number turns the number into a string thats added onto the original string.

5. Describe a real world example of when a conditional statement should be used in a JavaScript program.
- If user inputs incorrect answer tell them they got it wrong
7. Give an example of when a Loop is useful in JavaScript.
- anytime you need to loop through data or perform the same task multiple times


