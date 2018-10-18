**This is an exercise to work with branches.

(Hint: In order to copy just one branch use git clone -b <branch> <url>)

First of all you will be given permission to work in this repository.
This repository contains:
	-index.html
	-style.css
	-style2.css
	-main.js
	-images directory

You will have to clone this repository so you can work with it.

Once this is done you will create a new branch to work on the file you get assigned
- HTMLfeature for the person working on html
- STYLEfeature for the person working on css
- JSfeature for the person working on the js

Every member of the team will work on different files.

-The person working in the HTML will add a <p> with a small description about Porgs and another <p> element with a small description about ewoks.

-The person working in the CSS will add some background colour and text-align and font-family to the text.

-The person working in the JS will create a function to animate the the element with id="animation", on hover the font-size of this text will change to 50px.

Once you are happy with the changes you made, you will have to  merge your branch to the "develop" branch in the original repo.
(You will have to do a Pull request in the github repo in order to achieve this. The mentor will review this pull request)




Now we will create a conflict! Don't panic, conflicts can be solved.

You will want first to integrate the changes done by your team in your local repo.
You will have to pull the changes done in the develop branch in order to do this.

Now two people will work on the same file (2 in the html, and 2 in the css) each will make the changes.

-Person 1 working in the HTML will change the title to "Porgs are cuter" and will delete the ewoks.jpg picture.
-Person 2 working in the HTML will change the title to "Ewoks are cuter" and will delete de porgs.png picture.

-Person 1 working in the CSS will change the background color to black, and font-family to arial.
-Person 2 working in the CSS will change the background color to white, and font-family to monospace.

-Person 1 working in the JS will change the animation to work on click instead of on hover.
-Person 2 working in the JS will change the animation to work on double click instead of on hover.

In order to solve the conflict, someone will have to decided which changes are we going to keep in our file, and the add and push to the branch of the feature and then make a pull request to merge it to develop branch.


Nice resources:
https://medium.com/designing-atlassian/learn-to-love-git-part-three-collaboration-a778157d3a1c
https://medium.freecodecamp.org/follow-these-simple-rules-and-youll-become-a-git-and-github-master-e1045057468f



