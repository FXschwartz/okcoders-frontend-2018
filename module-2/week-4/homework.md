# Week 4 Saturday 11/17 - Final Project

Because we covered so many different topics with Javascript, I opted against trying to come up with one assignment that incorporates them all. Instead there are 8 assignments. This way completing the final project will require use of everything we have learned in this module.

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

6. Next we will create a little number guessing game against the user and the computer. Write a function that firsts gets a random number between 1 and 10 from the computer. Then prompt the user to guess that number. If their correct alert a message to the user showing they one. If not alert the user that they lost. Either way ask the user if they would like to play again.

7. Next we will write a text format app. The goal is to write a function that prompts the user for any string of text. The function should then take that string and make it proper case. Then alert the user the proper cased version of their text.

wElCoMe = Welcome

8. For this one we will be building a user editing app. You will start with an array of user objects each containing a 'name','email', and 'password' property. You should prompt the user and ask if they would like to add a new user or remove an existing one. If the user replies with 'add' you should then prompt asking for the 'name','email', and 'password' of the new user. Then push the new user to the array of user objects. If the user replies with 'remove', you will then prompt and ask for the email of the user they are wanting to remove. Then find the user and remove it from the array of user objects.
