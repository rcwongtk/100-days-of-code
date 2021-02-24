# 100 Days Of Code - Log (Second Attempt) - 2021

### Day 1: 2020-02-01

**Today's Progress**: Revisited the Java Programming Masterclass on Udemy (Tim Buchalka). Rewatched video lessons and redid assignments on the course.

**Thoughts** Wanted to revisit concepts like Inheritance, Encapsulation, Polymorphism, Composition. Have not really been using in my coding practice, hope to implement in the future.

**Link(s) to work**
1. [Link to Course](https://www.udemy.com/course/java-the-complete-java-developer-course/)

### Day 2: 2021-02-02

**Today's Progress**: Decided on a project to build, going to work on a gamified training app for dancers. Gearing towards street dance, will just make it a fun app to give to friends

**Thoughts** Meeting with Victor today to discuss the initial plans for the app, going to cater based on his suggestions. As he is a professional, modelling it after his training should provide good results.

**Link(s) to work**
1. [Git Repository for this project](https://github.com/rcwongtk/GamifiedPD)

### Day 3: 2021-02-03

**Today's Progress**: Working on implementing a "Training Entry" section of the app, created the UI buttons. Creating a script to change variables depending on options selected.

**Thoughts** Creating a central button script that signals the button pressed and sorts type of button depending on Tag type.

**Link(s) to work**
1. [Git Repository for this project](https://github.com/rcwongtk/GamifiedPD)

### Day 4: 2021-02-04

**Today's Progress**: Created a script for the buttons in the training entry sction. Now highlights the button pressed, stores data in a central area.

**Thoughts** Will be working on a system of competing an entry, then storing in a central area. Still planning best way forward for this.

**Link(s) to work**
1. [Git Repository for this project](https://github.com/rcwongtk/GamifiedPD)

### Day 5: 2021-02-05

**Today's Progress**: Can now create an entry, saves an entry object into a list in Player.

**Thoughts** Will work on a system of updating the experience points when an entry is made next.

**Link(s) to work**
1. [Git Repository for this project](https://github.com/rcwongtk/GamifiedPD)

### Day 6: 2021-02-06

**Today's Progress**: Updated the LocalPlayer script, so that stats now update with a training entry. Experience bar moves and levels change.

**Thoughts** Keeping simple, 1 hour = 1 stat depending on tag, and 100 exp per level with req experience curve.

**Link(s) to work**
1. [Git Repository for this project](https://github.com/rcwongtk/GamifiedPD)

### Day 7: 2021-02-07

**Today's Progress**: Finished the first rough draft of the Training Entry Section, now updates Focus and Status depending on frequency and type of entries

**Thoughts** This is a good time to show to Victor, get an opinion on the entry process. Will clean things up (like make the back button work) later on, but want to create a rough system for each button first. Will be working on the Notebook next.

**Link(s) to work**
1. [Git Repository for this project](https://github.com/rcwongtk/GamifiedPD)

### Day 8: 2021-02-08

**Today's Progress**: Added a script to create achievements when they occur. After a certain stat point they will be unlocked.

**Thoughts** Used a relatively simple method of setting active state depending on stat point, means the app has to be updated if new achievements are added. Works for now tho

**Link(s) to work**
1. [Git Repository for this project](https://github.com/rcwongtk/GamifiedPD)

### Day 9: 2021-02-09

**Today's Progress**: Minor changes to Notebook, working on design of UI to get it going

**Thoughts** Spoke with Victor about some ideas for the notebook, he liked the training entry so far, suggested adding an "Intensity" feature which was a good idea.

**Link(s) to work**
1. [Git Repository for this project](https://github.com/rcwongtk/GamifiedPD)

### Day 10: 2021-02-10

**Today's Progress**: Issue with computer, took a break for the day to fix it.

**Thoughts** Continuing for the 11th.

**Link(s) to work**
N/A

### Day 11: 2021-02-11

**Today's Progress**: Working on connecting the user to a database, so that the information can be stored. Will also have to create a sign-in screen in that case.

**Thoughts** Going to use firebase for now, seems to be a good solution for this.

**Link(s) to work**
1. [Git Repository for this project](https://github.com/rcwongtk/GamifiedPD)

### Day 12: 2021-02-18

**Today's Progress**: Took a break to focus on a course, back into action. Successfully created a connection between the application and firebase.

**Thoughts** Working on the sign-in screen next.

**Link(s) to work**
1. [Git Repository for this project](https://github.com/rcwongtk/GamifiedPD)

### Day 13: 2021-02-19

**Today's Progress**: Getting back into the 2D Platformer, spent some time cleaning up some code and play testing.

**Thoughts** Will work on some more rooms next.

**Link(s) to work**
1. [Git Repository for this project](https://github.com/rcwongtk/BasicPlatformer)

### Day 14: 2021-02-20

**Today's Progress**: Remodelled 2D Game, scripted different way of changing rooms. Makes things much easier and cleaner.

**Thoughts** Previous method was to move character to next room when gate touched, but now it teleports to a checkpoint which is much more versatile

**Link(s) to work**
1. [Git Repository for this project](https://github.com/rcwongtk/BasicPlatformer)

### Day 15: 2021-02-21

**Today's Progress**: Completely redid the layout of the game, now more organized and easier to create or modify rooms

**Thoughts** Spaced out every room a set width, and improved placement of gates to remove jank.

**Link(s) to work**
1. [Git Repository for this project](https://github.com/rcwongtk/BasicPlatformer)

### Day 16: 2021-02-22

**Today's Progress**: Worked on the GamifiedPD all day, created a sign-in section to test connection and it worked perfectly. 

**Thoughts** Now that it works, going to try and implement Firebase.Auth to make sign-in more legitimate.

**Link(s) to work**
1. [Git Repository for this project](https://github.com/rcwongtk/GamifiedPD)

### Day 17: 2021-02-23

**Today's Progress**: Hit a roadblock, for some reason Firebase.Auth does not work with my current GamifiedPD build. Going to have to rebuild the app in a different version

**Thoughts** Tested using Unity 2020, and it is working great, not sure why there is this incompatibility going on got CreateUserWithEmailAndPasswordAsync encountered an error: System.AggregateException.

**Link(s) to work**
1. [Git Repository for this project](https://github.com/rcwongtk/GamifiedPD)
