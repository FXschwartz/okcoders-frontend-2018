# Week 1 - Homework

We're going to do a very simple home page for an animal adoption website for this week's homework.  Every day (Monday, Wednesday, Friday) will build on the previous. For a general guideline I will be displaying an image of what the page layout should look like. It will be up to you to figure out how to mimic the layout as well as adding in your own ideas, designs and making it your own.

Each assignment will be graded with 50% going toward it being completed and the other 50% from coding style (Code correctly spaced and indented, good naming conventions that make sense etc...)

- Day 1: Setup, layout, table of animals
- Day 2: Animal info page
- Day 3: css and visual improvements

## Day 1 - Monday 9/24

### Setup
Create a new folder called `adoption-website`, this is where this weeks homework will live.
Create a new file inside of `adoption-website` called `home-page.html`

### Layout

We want our home page to have a 3 panel layout:
- A top area for our Website's title and future links
- A main area to display the list of animals available for adoption in a table format
- A bottom area to display the contact email address.

Here's an idea of what it should look like:

![Home Page Layout Example](https://github.com/FXschwartz/okcoders-frontend-2018/blob/master/module-1/week-1/week-1-homework.png)

### Bonus
- Make the email address in the footer a clickable link that opens up your computer's default email client when clicked on.

#### Hints
- Your home page doesn't have to look like mine at all, it just has to have the general layout.
- Remember that block elements like a `<div></div>` are great for headers and footers because they take up the full width of the page.
- Don't be afraid to play around with some css and experiment with new html tags.
- Finally, if you need help, reach out to me!  That's why I'm here.

## Day 2 - Wednesday 9/25

We are going to be building at least 1 page for a user to get more information about an animal. You should link one of the animals in your list to go to this page to display more info about him/her

### Setup
Create a new folder called `adoptable-animals`, this is where this weeks homework will live.
Create a new file inside of `adoptable-animals` called `animal-detail.html`

### Layout

The overall layout of this page is up to you. Only things that are required are that you display the animals name, age, adoption cost, birthdate, and a list of shots/vaccines given.

All of these (except shots/vaccines) should be displayed using input fields with a specific input type.
- name: text
- age: number
- adoption cost: number
- birthdate: date

The shots/vaccines list can be shown just as a normal list

### Bonus
- Make the 'age' and 'adoption cost' number fields so they cannot go below 1

## Day 3 - Wednesday 9/27

This last assignment is going to be a light one since the entire weeks homework is do at the end of today. What i'd like you to do is dive into css and use it to make your new website more visually appealing. Add some background images, or some images of the animals. Play around with transitions and some very light animations. Once you have a good amount of css in your html files we are going to want to seperate out the css into its own file and import that file into the html file we want it to be applied too. We are doing this because starting tomorrow we are going to go more in depth into css and bootstrap and our list of css is going to grow, its more efficient and just much cleaner to take out that css and put it into its own file.

### Setup
For each html file you have, create a css file and name it the same except with a `.css` extension at the end. For example, your `home-page.html` should now have all of its css moved into a `home-page.css`

### Bonus
- Make it where if a user moves their mouse (hovers) over a row in your table, the background of the entire row will change to a different color.

### Once You Are Done
Next week I will have a better way for you to send me your completed assignments but for now after you are done with each one send the `adoption-website` folder to me in a private slack message.
