+++
title = "Solving Wordle with Cypress"
description = "Applying some automation to solving the daily Wordle problem..."
author = "Chris Ryan"
date = ""
tags = ["Cypress","Test-Automation","Wordle"]
categories = ["Cypress"]
comments = true
removeBlur = false
[[images]]
  src = "img/wordle-cypress.png"
  alt = "Solving Wordle with Cypress"
  stretch = "horizontal"
+++

## Wordle Solver with Cypress

**Wordle was taking so much time! Applying some automation to solving the daily puzzle...** _So, I've written some test automation to play it for me with Cypress, JavaScript and a list of 2,309 words. Check out my approach, code and video of it in action..._

Yes, the world is playing it so I've succumbed. I've been playing Wordle. It's irresistible and you only get one word a day, all part of the magic.

But it's also an irritating distraction, so the solution is automation. As Abraham Maslow said, 'when all you have is a hammer, everything looks like a nail'. Well said, and it does indeed look like a nail.

So, I've fired up VS Code; together with some Javascript, Cypress and the list of 2,309 words Wordle uses for its answers. Here's the result.

{{< youtube AOB2J4gZEOA >}}

### The Approach

Cypress is a great tool with good documentation, and I wanted to experiment with it. I structured the code into two classes:

**_PageActions class_**
This handles the page interaction; button clicks, reads and records the response from Wordle. The shadow DOM on the Wordle page allows extraction of the score for each attempt: Green (correct), Yellow (present) and Grey (absent).

**_Solver class_**
The Solver class uses the word list used for its answers. It loads these into an array and as the responses come back it eliminates words from this array to narrow down to the correct solution. As starting point, it uses _STARE_ as its first word, a reasonable first guess I feel. I've read some analysis that other words might be better, _ADIEU_ for example but I'll perhaps experiment with others later. Using the feedback from PageActions these word array is pruned; when a letter is correct then eliminate all words that letter(s) aren't in that position, where is present remove all word that don't contain it and that have that leter in that position and where a letter is absent then remove all words containing it. When making a guess if possible use a word with no repeat letters as that maximises our elimination or confirmation of letters.

This approach works well enough usually solving with four attempts which I feel is par for the puzzle. It could be improved using Information Theory as explained in the excellent [Solving Wordle using information theory](https://youtu.be/v68zYyaEmEA) video but that's for another day!

### The Code

Check my code here on GitHub.

[GitHub chrisrryan/wordle-cypress](https://github.com/chrisrryan/wordle-cypress.git)

_Article by Chris Ryan_
