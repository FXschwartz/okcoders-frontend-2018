# Week 4 Saturday 11/17 - Final Project

Because we covered so many different topics with Javascript, I opted against trying to come up with one assignment that incorporates them all. Instead there are 10 assignments each counting as a tenth of the total grade. This way completing the final project will require use of everything we have learned in this module.

1. We are going to start with an array of numbers, the numbers are up to you just make sure there are at least 10 of them. Write a function that loops through the array and adds each number together, then display the number total to the user with an alert.

2. For this one the goal is to build a very simple bank app, where you will prompt the user for their account number, and then find that user in an array of objects and alert their bank account balance. You will start with an array containing at least two objects with two properties. Once you have the users account number, loop through the array and find the correct object and then display its account balance.

{
	accountNum: 11982744818231574,
	accountBal: -243.00
}

3. Next we will start with an array containing information about the worlds cutest kitten. The goal is to write a function that takes the contents of the array and turns them into an object.
For this one we know in what order the array values are so we will know what property to create based on the index we are currently at in the array.

[tuna,12,orange,grumpy] = {name:tuna,age:12,color:orange,personality:grumpy}

4. We start with an array of both numbers and strings. The goal is to write a function that given an array can filter out all of the string values and push them to their own array. Then sort the array with only number in descending, and the array with letters in ascending. In the end output both arrays with console.log to confirm its worked correctly.

5. For the final one we will begin with an array of numbers 1 - 10. The goal is to loop through and remove all of the odd numbers. Do this without using the .filter method!
