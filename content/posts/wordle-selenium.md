+++
title = "Solving Wordle with Selenium 4 & Java 17"
description = "Applying some automation to solving the daily Wordle problem..."
author = "Chris Ryan"
date = ""
tags = ["Selenium","Test-Automation","Wordle", "Java"]
categories = ["Selenium"]
comments = true
removeBlur = false
[[images]]
  src = "img/wordle-selenium.png"
  alt = "Solving Wordle with Selenium"
  stretch = "horizontal"
+++

## Wordle Solver with Selenium 4

As a comparison, based upon my Wordle automation solution using Cypress, this time I've used Selenium 4 and Java 17 to solve the puzzle.

I'm not going to get into a full Selenium versus Cypress comparison here but I'd say both solutions work very well. Selenium has been around for many years but with version 4, the webdriver has been much improved with W3C compliance, integration with CDP (as Cypress uses) and relative locators for more stable scripts. Clearly, Cypress is gaining lots of traction which is understandable particularly with version 10 now available.

I've used created two classes, a Solver class which deals with word selection and a PageActions class which handle UI interaction. Here's it in action:

{{< youtube pmR0nBxRGHU >}}

Check my code here on GitHub.

[GitHub chrisrryan/wordle-selenium-java](https://github.com/chrisrryan/wordle-java)

_Article by Chris Ryan_
