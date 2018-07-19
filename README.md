# Survey Says: JavaScript Edition!

## The Goal

The information in the database file attached here has results from a survey Jeff took of some of his friends. He's going to use that information to learn some things about the friends who answered the survey. For example:
* What percent of his friends are programmers?
* Do they like similar or dissimilar music?
* How many of them live in each state?

One warning: these are real people, and real people don't always provide the easiest data to work with. Get ready for typos, unexpected blanks, and outright silliness (Max, for example, isn't 100 years old).

In the challenge.rb file, Jeff has written some questions he has. Use your knowledge of arrays and objects to get at the information asked for in each of the 9 challenges.

## Getting Started

If you already have a good idea of how to start this based on previous labs, go for it!


<details>
  <summary> If you're struggling to get started, click here for some tips </summary>

  #### Try to get a feel for the shape of the data by adding the three puts statements below to the challenge.js file:

  ```javascript
  // All the survey responses are stored in an array called "people".
  console.log(people)
  console.log("THE FIRST PERSON IS:")
  console.log(people[0])
  
  // 1. Print out the name of the first person who responded to the survey
  ```

  Then preview the data in the console when you preview the index.html.

  You'll notice that the real trouble is that it's providing WAY more than that person's name. It's providing their entire object.

  That means the answer to challenge 1 will look something like this:

  ```javascript
  // 1. Print out the name of the first person who responded to the survey
  console.log(people[0]["some_string_here"])
  ```

</details>
<br>
