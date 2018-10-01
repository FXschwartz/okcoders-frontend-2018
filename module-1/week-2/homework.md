# Week 2 - Homework

We're going to build on top of our adoption-website project and make it visually more appealing using bootstrap with some css and new components as well as making sure it is mobile friendly.

Each assignment will be graded with 50% going toward it being completed and the other 50% from coding style (Code correctly spaced and indented, good naming conventions that make sense etc...)


## Day 1 - Monday 10/1

### Layout
Our table listing our adoptable animals our has been great so far, but we want something a little more modern. Instead of the table lets use our new `row` and `col` to create a new layout. For each animal we want an image and a description all on one row alternating sides with each animal. Now if you click on the image or the description it should take you to the animal detail page for that animal.

For our animal detail page we want to add a jumbotron just like we have on the home page except with the image being the image of the animal you clicked on from the previous list.

Here's an idea of what it should look like:

![Home Page Layout Example 1](https://github.com/FXschwartz/okcoders-frontend-2018/blob/master/module-1/week-2/Worldwide-Animal-Adoption.png)

![Home Page Layout Example 2](https://github.com/FXschwartz/okcoders-frontend-2018/blob/master/module-1/week-2/Sam.png)

We also want this to be mobile friendly which means our image and the description should collapse with viewing on a smaller device.

![Home Page Layout Example 1](https://github.com/FXschwartz/okcoders-frontend-2018/blob/master/module-1/week-2/Worldwide-Animal-Adoption-mobile.png)

The last thing we want is a contact page called `contact.html`. Lets add a dropdown to our nav bar at the top and add a selection in it called `Contact Us` that when clicked will navigat the user to the contact page. The look of this page is up to you but the basic components needed are an input field for name, email, subject, and body. And then a button to send the contact request. This will also need to be mobile friendly!

### Hint
- Remember you can specify how row elements will be aligned on different devices by chaining `col` (col-lg-6, col-sm-3).

### Once You Are Done
Until I figure out the best way to have you upload the homework continue sending me the whole project folder through slack.
