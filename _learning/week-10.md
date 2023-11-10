---
title: "Week 10"
collection: learning
type: "Pre-university course"
permalink: /learning/week-10
venue: "Breda University of Applied Sciences"
date: 2023-11-13
location: "Breda, The Netherlands"
---

This is a description of your learning experiences. You can use markdown like any other post.

## Plan

<!---
NOTE: Fill this section in at the beginning of the week!

What do you plan to do this week? What new knowledge do you want to acquire? Do you want to follow any of the learning units for the course? Do you want to work on the assignment for the course? How much time do you estimate you will spend on these tasks?
-->

This week I hope to add another enemy, fix all collisions & AABBs, finish my level backgrounds and add more sprite animations for player & hulkazoid. 

## Do

<!---
NOTE: Fill this in during the week.

What were you actually able to accomplish? Was it more or less than what you planned? Was the amount of time you thought you would spend on it accurate? If not, what took longer than you thought it would?

Provide as much context as possible. Use code snippets or take screenshots of what you were able to accomplish. Please provide references to any additional sources of information that helped you.
-->

First off I fully fixed and implemented Entity collisions with level AABBs. I then worked on more & better sprite animations for my characters. And added collision between player & enemies. I moved all entities into one vector/list to make collisions easier to check. I also renamed Background to Level as it handles and/or stores Background, Assets and Level specific values such as level collisions/AABBs. I also added a derived class Hulkazoid from Enemy to contain Hulkazoid specific things and to be able to define the difference between this one and the other enemy I want to add. I also added Vorc, a new enemy which stays in place (is not affected by gravity) and then moves towards the player with a high velocity once the player is in its direct line of sight (only moves across one axis)

## Check

<!--- 
Note: Fill this in at the end of the week.

What went well? What didn't go so well? What was the most important thing you learned this week?

Did you receive any feedback from the lecturer or your peers? If so, what was that feedback? Were you able to incorporate that feedback?

Did you give anyone else feedback? Who did you give feedback to? How did they respond to your feedback?

NOTE: Any source of feedback is feedback!
-->

## Act

<!---
Note: Fill this in at the end of the week.

What action points can you identify from this week? What would you like to improve? What would you like to continue to strengthen?

If your planned time estimates were not accurate, what would you do to improve them?
-->