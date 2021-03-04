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

1. Start off by writing a straightfoward story. A few sentences is fine. If you need inspiration, write about what you did on your way to class this morning, or what you did this weekend. You needn't get hung up on the details.

2. Now remove some of the key words, but remember what part of speech each was. Aim for five or so blanks.

3. Next, for each blank in your story, create a variable at the top of madlibs.js. Since you don't want to give away how they fit into the story, consider naming them based on their part of speech (such as `verb1` or `nounPlural2)`. You should assign to each of these a sutable word (`"scream"`, `"penguins"`, etc.).

4. Now create your story in code using a series of  `console.log()` statements. Each of these should contain a single sentence from your story as a string with some number of blanks, corresponding to the variables you just created. Use concatenation to insert each variable's value into your sentences.

5. Run your code to see if everything works. If it does, change the variable assignments at the top of your code so each variable holds the empty string `""`. Then add a bunch of empty lines between the variable assignments and the `console.log`s, so you can't see both on screen simultaneously. Now check with the students sitting next to you: When they're done as well, give each other your code and see what silly stories they create.
