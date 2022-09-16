---
layout: project
type: project
image: img/icspark_p2_escape_doorWall_square.png
title: "Using the Powers of File Paths to Create Doors to New Universes! Open the Doors if You Dare.."
date: 2022-02-12
published: true
labels:
  - HTML
  - CSS
summary: "I made a very basic project with HTML and CSS to demonstrate the basics of file paths as a solution to one of ICSpark's new projects."
---

<div class="text-center p-4">
  <img width="490px" src="https://user-images.githubusercontent.com/56208115/190551426-24897d2e-7d00-482d-9f7c-74eb55fb33d8.png" >
  <img width="490px" src="https://user-images.githubusercontent.com/56208115/190551884-ce2b53ff-73be-4262-81e7-124b028b0061.png" class="img-thumbnail" >
  </div>


I have been a member of the ICSpark student organization for around a couple years now, and here is one of the solutions I made for one of ICSpark's curriculum projects. What is ICSpark?  ICSpark is a university student-lead organization where student volunteers mentor middle and high school students to teach them basic web development with HTML, CSS, and Javascript.  Every week during this Spring semester program, we have students complete projects based on what they're currently learning.  Our mentor resources had project solutions for us mentors to refer back to in order to better help the students complete their projects for every project except one--"the escape" room project.  My task was to make a solution for this project for the mentors to refer back to since this was the only project missing a solution. 

Of all the computer science-related projects I have worked on, the "escape room" project was probably one of the most enjoyable ones even if it was very simple.  One aspect of "escape room" I liked in particular was that there was a little story to the project, even if it was very short.  The instructions state, "You were at the zoo and accidentally let the animals loose! You're on the run and come across a brick wall with three suspicious doors! Which door will you choose? Where will it lead?!"  Using file paths, the project-goer must create the doors that lead to different worlds when the user clicks on any one of the doors, like the dragon's lair or the future.  One must use the href attribute in html to specify paths to other html files that represent the different worlds (for example, the-future.html represents the future world). One must also access the gifs using file paths as shown below.  Here, I had to use a file path to access the future.gif in order to make the appropriate gif appear when one clicks on the door to the future world.


```css
#container{
  width:calc(100vw);
  height:calc(100vh);
  background-image: url("../assets/future.gif");
}

#text{
  background-color:white;
}

#home{
  background-color:white;
}
```

This project, with it's fun little story and easy-to-follow instructions, has inspired me to try to come up with my own creative and fun mini projects in the future that I can later add to a project portfolio.  Even though this was a relatively easy project, this was actually the first instance in which I learned about how to use file paths, so successfully making a solution for others to reference for a project with a concept that was new to me felt very rewarding.

Here is the link to the original project instructions: [escape-room](https://github.com/junior-devleague/escape-room).

