---
layout: post
title: "Pythagorean Theorem App"
date: 2016-04-13
categories: 
keywords:
description: "Sinatra App Tutorial"
comments: true
categories:
- welcome
tags:
- welcome
- hello-world

---

How did you get your idea for this project?
I got the idea for this project because of some of the suggestions Ms. Pilgrim made during class about creating an app that a user can input information into and then have the program manipulate it. With the word manipulate, I thought math equation and then I thought about those websites that will solve different equations for you if you input certain values that can be plugged into the equation. I decided that I would do the Pythagorean theorem to start with and then move on to move if I had enough time, which I unfortunately did not.

What did your initial planning entail (wireframing)?
My initial planning for constructing this app involved creating a wireframe for how I wanted the program to look when I was finished. I decided to keep it relatively simple with spaces for users to input a triangle’s side length and text to instruct the user how to use the program. The second wireframe is the page that the user will be directed to once they get an answer. My final project ended up a bit differently because I decided to take out the option of imputing a hypotenuse to simplify it a bit more.

INSERT PHOTO

How did you build the application?
I focused on the back end first to make sure that the more technical part of the code was done and I then moved onto the front end of the project. The difference between the front end and the back end is what the user sees versus what the code it actually doing.

I started with looking at the basic layout of some of our previous projects and so I created three folders called models, public, and views, as well as a file called controller.rb.

INSERT PHOTO

I went to the controller.rb file first and used our previous projects to help guide how to set up my program. I put in the require pieces and also connected the controller to the models so that it would be able to use it. I then used post because I wanted users to be able to input something, more specifically the two sides that I then put variables for below. The next line has to do with the answer to the Pythagorean theorem with the imputed sides. To get the answer, I had to put the variables into the PythagoreanTheorem model that I created in the models folder.

INSERT PHOTO

Going into the PythagoreanTheorem file, I created the different variables I would need, and after, I made a function that would solve the Pythagorean theorem given the imputed sides. Back in the controller.rb file, the next line will take the user to a new page to display the answer. That is also what the get does underneath it. It will put the answer on that page and use the layout from the answer.erb file in the views folder, just like the initial page used the index.erb file.

INSERT PHOTO

In the index.erb file, I used previous projects to base my code on. First I had to connect the different stylesheets that I had made in the public folder. The normalize.css file is code that we used previously to make the layout run more smoothly. The style.css file is something that I made to change the fonts, background color, and text color. These files have more to do with what the user actually will see.

INSERT PHOTO

But, back to the index.erb file. After connecting the stylesheets, I then set it up so that the user would know that this was an app for solving the Pythagorean Theorem, included a picture of a right triangle, spaces for the user to input their side lengths, and a submit button to run the program and bring the user to their answer.

The next file in the views folder and the last one to discuss is answer.erb. This is what shows up on the page where the user receives their answer. I again connected the stylesheets and made sure the computer knew I was working with HTML, and then simply put text introducing the number, and then used Ruby in HTML to connect the answer variable so that the answer will print to the screen.

What was the most difficult part?
The most difficult part was trying to take what I had learned in previous classes and try to translate it into Ruby and figure out what part had to go in which file, which I’m not used to. I feel pretty comfortable with the way of thinking about coding, but I get a bit confused when trying to figure out different syntax and the way to use all the variables in Ruby and in going across different files.

Resources:
http://stackoverflow.com/questions/12340335/loading-stylesheets-in-sinatra
http://www.platinumgmat.com/global/images/study_guide/pythagorean_theorem1.gif?v=1
https://github.com/Giphy/GiphyAPI
