---
layout: post
title:  "Good Code Reviews"
date:   2014-01-16 22:06:46
categories: code-reviews
---

###What makes a good code review?

* Code change is narrow in scope
* Code for review should be fewer than 200-400 loc
* Code should be reasonable tested and should work before submitted for review.

###How to conduct an effective code review?

* Review structure.
  * Are the classes/methods named properly for the job being accomplished.
  * Are the methods simple and easy to understand. Are they small
  * Are classes cohesive to what they are doing?
* Does the code accomplish the task at hand in a simple manor
* Review for general bugs or possible gotchas
  * null reference issues
  * missed assumptions
  * ways to improve code if any
* Code under review is assumed to work and be tested/compiled by the submitter.

###Resources

[IBM proven practices for peer review](https://www.ibm.com/developerworks/rational/library/11-proven-practices-for-peer-review/)
