---
layout: project
type: project
image: img/icspark_p2_escape_doorWall_square.png
title: "Project Escape Room!"
date: 2022-02-12
published: true
labels:
  - HTML
  - CSS
summary: "I made a very basic project with HTML and CSS to demonstrate the basics of file paths as a solution to one of ICSpark's new projects."
---

<div class="text-center p-4">
  <img width="200px" src="../img/micromouse/micromouse-robot.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
</div>

I have been a member of the ICSpark student organization for around a couple years now, and here is one of the solutions I made for one of ICSpark's curriculum projects. What is ICSpark?  ICSpark is a university student-lead organization where student volunteers mentor middle and high school students to teach them basic web development with HTML, CSS, and Javascript.  Every week during this Spring semester program, we have students complete projects based on what they're currently learning.  Our mentor resources had project solutions for us mentors to refer back to in order to better help the students complete their projects for every project except one--the escape room project.  My task was to make a solution for this project for the mentors to refer back to since this was the only project missing a solution. 

For this project, I was the lead programmer who was responsible for programming the various capabilities of the mouse.  I started by programming the basics, such as sensor polling and motor actuation using interrupts.  From there, I then programmed the basic PD controls for the motors of the mouse.  The PD control the drive so that the mouse would stay centered while traversing the maze and keep the mouse driving straight.  I also programmed basic algorithms used to solve the maze such as a right wall hugger and a left wall hugger algorithm.  From there I worked on a flood-fill algorithm to help the mouse track where it is in the maze, and to map the route it takes.  We finished with the fastest mouse who finished the maze within our college.

Here is some code that illustrates how we read values from the line sensors:

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

You can learn more at the [UH Micromouse News Announcement](https://manoa.hawaii.edu/news/article.php?aId=2857).

