+++
title = "The Test Automation Pyramid"
description = "The Test Automation Pyramid concept that guides teams when it comes to prioritising the different kinds of testing in a test strategy."
author = "Chris Ryan"
date = ""
tags = ["Agile", "CI/CD", "Test Strategy"]
categories = ["Test Automation"]
comments = true
removeBlur = false
[[images]]
  src = "/img/the-test-automation-pyramid.jpg"
  alt = "The Test Automation Pyramid"
  stretch = "horizontal"
+++

### WHAT IS THE TEST AUTOMATION PYRAMID?

The **Test Automation Pyramid**, differentiates test types to maximise the benefits of each to deliver the optimal test strategy and return on investment. It's an essential framework in the development of an effective test strategy.

### Selection Criteria to Maximise ROI

The benefits of test automation may lead to a desire to automate everything. However, there's a smarter way to approach this, to recognise the different types of tests and use each most effectively.

- Clear-cut test objective
- Repeatable & adds value
- Meaningful
- Robust & Reliable

With Agile and it's accelerated product release cycles requires accelerated testing. With the focus on shorter release cycles, test automation can be hugely beneficial, if not essential.

With Continuous Integration/Continuous Deployment (CI/CD) methods, these benefits are amplified, automation allows test cases to be run each time code is pushed to the repository, ensuring bugs are found early and fixes made quickly. The process automates delivery of high quality code from development through to production.

### What Is the Test Automation Pyramid?

> The **Test Automation Pyramid**, guides teams in designing the optimal proportion of test approaches for the most effective automated test strategy.

The pyramid represents the three types of software tests:

{{< image-right img="/img/split-pyramid.jpg"  >}}

#### Base layer: Unit Tests

Unit tests form the foundation, they test the smallest, most independent, they're quick to write and run fast. These should be the largest element with your automated test suite and are the base of the pyramid.

#### Middle layer: Service Tests

Service tests are the next layer of the pyramid. Service tests that bypass an application’s UI and talk directly to the API underneath it.

Service tests are usually slower and offer less precise feedback than unit tests. They might also be harder to write since they’d typically require access to the external dependencies. Despite their complexities, they have the benefit of painting a more realistic picture, by verifying the app’s behavior in a way that’s closer to how the user interacts with it than unit tests.

#### The Top of the Pyramid: UI Tests

The top of the pyramid features what are called UI tests in Martin Fowler’s article, even though, in my definition, they’re more like end-to-end tests.

These are tests that drive the application the way a user would. These tests tend to be slow to run and very brittle since they might break due to the smallest change to the application’s UI. On the other hand, despite their problems, they do offer benefits. They mimic the way users interact with the application with much more realism than the other kinds of tests. Their results offer feedback that’s less precise. But at the same time, they might catch defects that the other types of testing would not.

To balance this, the testing pyramid says you should leverage this type of testing. Just make sure to have as few of them as you can get away with.

#### Consider the Test Automation Pyramid for Getting the Best Out of Your Testing Approach

Software testing is an essential activity. And what’s more, leveraging test automation is essential for tech organizations that want to deliver code as fast as possible while keeping quality high.

However, resources aren’t infinite. You have to use some strategy to decide how to allocate your resources when working on testing. The test automation pyramid is a metaphor that guides you on how to make those decisions.

_Article by Chris Ryan_
