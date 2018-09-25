# CSS-lab drills

Objective<br>
Let's practice using the fundamentals of CSS!<br>

Setup<br>
Create a new project folder and connect it to a github repository. Copy the text from this README.md file into it.<br>
Create an index.html file and a styles.css file.<br>
Use the ! emmet shortcut to stub out the page.<br>
In the < head >, link the the CSS file to the HTML page.<br>
Build the HTML Structure<br>
In the body element, create a div with an id of "container"<br>
Add 4 div elements with a class name of "boxes" and a unique id (box1, box2, boxN) inside the container div. Each added div will be a child of the container div and a sibling to each other.<br>
Create an < h2 >, < p >, and < a > element inside of each of the 4 div's. Add the following content to the elements:<br>
h2: Add a story title in each header<br>
p: Add a story description within each paragraph<br>
a: Add a link that says "Read More"<br>
Now, Lets style!<br>
Assign a global font family<br>
Here is a list of some Web Safe Fonts: https://www.w3schools.com/cssref/css_websafe_fonts.asp<br>
You could also play around with Google Fonts: https://fonts.google.com/<br>
Hint: use the body selector.<br>
Change the background color for the body element to a light grey color.<br>
Use a multiple selector rule set to center the text for all h2, p, and a elements.<br>
Use an element selector to remove the default underline styles for anchor tags and change the font color:<br>
When you refresh your browser you'll notice that the link is not centered like the h2 and p elements. This is because text-align will center the element based on the width assigned to it. If you apply a border to the link tag, you'll see that the link is centered inside the anchor element. The best way to center the link, relative to its parent element, is to enclose it inside of a div element.<br>
Wrap the anchor element inside of a div and give the div a class name of "readme-wrapper":<br>
Replace the a in the multiple selector rule with .readme-wrapper<br>
Now refresh and you'll see the link is centered as we expected it<br>
Use a class selector to target the .boxes class:<br>
Change the display to inline-block<br>
add margin<br>
add padding<br>
add a solid border<br>
add a border radius to round the edges of the border<br>
Add a CSS :hover selector so that when the link is moused over the cursor changes to a pointer, the font is bold, and text color changes.<br>
Wrap a single word in each paragraph element inside of a span element and assign it a new font color and font weight.<br>
Change the display to block in the class selector named .boxes.<br>
When you refresh the page, you'll see each div now takes up the entire row.<br>
Add a width of 20% to each div with the class .boxes.<br>
Use an id selector to add a unique background color to each div.<br>
Change the position of the second div to be relative to its parent.<br>
Position the second div so that it is next to the first div.<br>
Change the position to absolute.<br>
Position the second div to the top right corner.<br>
Remove the position styles for the second div.<br>
The second div should now be returned to the normal flow.<br>
Add a new div element as a child inside each of the 4 div elements.<br>
We'll use this div to represent an image<br>
Give the new div a class name.<br>
Assign a width, height, and background color to the div.<br>
Position the div so its inline and to the left of the header.<br>
Styling Specificity<br>
Insert 3 h1 tags into the html document, give each text for your favorite TV shows.<br>
Apply styling so that all h1’s have a font color of your choice.<br>
Add 2 more h1’s with 2 other TV shows. What immediately happens to their font color when you refresh the html doc?<br>
Give the original 3 h1’s all the same class.<br>
Give the additional 2 h1’s the same class (make it be different than the other 3).<br>
Apply styling by class name, have the first 3 h1’s get a new font color (don’t delete or comment out the original styling). Once you apply a new font color by class, refresh the page and see what it does.<br>
Do the same thing for the added 2 h1’s, give them a different font color by class name.<br>
Take note at what styling applied to a class does to what was already applied to ALL of the elements before.<br>
Rank each TV show you have (so all 5 h1’s), a rank of show1 would be the best. Have the rank be the id of each h1. At this point every h1 should have a class AND an id attribute.<br>
Apply styling using the id of each h1, give each a different color. Refresh the document and see how this type of styling changes what was already applied. Create 3 unordered lists, each with 5 items, have the first list be 5 friend's names, have the next be 5 places you want to travel, and have the last list be your favorite restaurants.<br>
Apply the same steps covered in the directions to play with the specificity of styling on each of these lists.<br>
Wrap each list in a div, give the div a border that is 2 pixels thick, have it be solid and the color be black.<br>
Isn't styling fun? We know it can be tricky and tedious, but the more you practice, the better you'll get at it. After a while, you won't even think about it anymore :)<br>
