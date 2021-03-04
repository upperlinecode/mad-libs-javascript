# Mad Libs

[![Run on Repl.it](https://repl.it/badge/github/upperlinecode/mad-libs-javascript)](https://repl.it/github/upperlinecode/mad-libs-javascript)

## TL;DR

This lab will give you practice with variables, console.log, and concatenation. Open up madlibs.js and fill in the code as described under each comment. Run your code often to make sure it's working.

## Contents

1. [Intro](#intro)
2. [The Lab](#the-lab)

## Intro

We've just seen how variables can be concatendated with strings to make custom messages. In this lab, create a Mad Libs game to get more comfortable with concatenation and have some fun.

<details>
<summary> If you've never played Mad Libs before, here's how it generally works.</summary>
One person holds a story that contains blanks, each with a suitable part of speech written under it. They ask a friend to supply them with words that match each parts of speech, without letting that friend see the story, writing the words onto the blanks as they go. When they get to the end, they read they're ridiculous creation aloud.
</details>

## The Lab

The javascript function `console.log` allows us to easily display prewritten messages. But by adding variables, we're able alter parts of those messages without changing the core of our code.

By going through the steps outlined below, you'll create a Mad Libs game that you can unleash on your classmates. Write your code in `madlibs.js`.

0. Run the script and see how the example works.
1. Start off by writing a straightfoward story - use at least 3 different `console.log()` statements. If you need inspiration, write about what you did this morning, or what you did this weekend. You needn't get hung up on the details. You can also use the standard "Once upon a time..." intro if you'd rather.
2. Now remove one the key words, but remember what part of speech it was.
3. Next, create a variable at the top of madlibs.js. Since you don't want to give away how they fit into the story, consider naming them based on their part of speech (such as `verb1` or `nounPlural2)`. Set each one equal to a prompt that the user can answer.
4. Now go back and add in the variables to the strings in your `console.log()` statements. Use concatenation or string formatting to insert each variable's value into your sentences.
5. Run your code to see if everything works.
6. Repeat until your story requires at least five words provided by your user. You can add sentences to your story as necessary.
7. Send a link to your running code to someone else to test out. 
