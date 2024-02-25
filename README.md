# What is this?

This is a repository with the source code for the first part of my friend's birthday gift - hosted [here](https://ahujaesh.github.io/birthday-surprise/) through GitHub Pages. If you see any errors or want to help, feel free to open an issue, fork this repository and start a pull request, or just email me here - [ahuja.eshaan0@gmail.com](mailto:ahuja.eshaan0@gmail.com)!

# An overview of this repository:

**Logic (How the website works):**

This website used a three dimenstional rendering software called "THREE.js". This software allows the user to add Javascript commands in their code to render different objects to your scene, and I have used this software to render the word that you move around in. You can read more about THREE.js [here](https://discoverthreejs.com/).

This website also uses some standard _HTML_ elements such as ```<p>``` and the ```<h4>``` elements to convey information to the user, and these elements are updated using the ```.innerHTML``` syntax to respond to user input, along with ```<button>``` elements and ```<a>``` elements to gain input and advance users to the next site.

On top of this, within all the ```.html``` files, I also include Internal _CSS_, that, in combination with some _Javascript_, allows for me to make elements appear and disappear using properties like the ```display: block``` property or ```display: flex```. I  also use _CSS_ to add backgrounds (```background-color:#87ceeb;```), and more.

Along with these, I also use many other code elements, and I am always looking to add more to improve the user experience.

**Files and Documentation:**

This repository contains 2 main ```.html``` files, that both use Internal CSS and Javascript for easy readability. It also contains some other files. I have outlined the purpose of each of these files below, along with a higherarchy of importance. If you have something to add, feel free to shoot me a PR or an Issue.

- File one ([index.html](https://github.com/ahujaesh/birthday-surprise/blob/main/index.html)):
    - This is the default landing page for the website and serves as the introduction page
    - Uses Internal CSS and Javascript
    - It contains a tutorial written using [THREE.js](https://en.m.wikipedia.org/wiki/Three.js), HTML, CSS and Javascript
      - Within this tutorial, you complete three quests  to learn how to move around in the three.js world
    - Upon competition, it leads you to the next page for the main quest
    - You can view this file [here](https://ahujaesh.github.io/birthday-surprise/)

- File two ([pt2.html](https://github.com/ahujaesh/birthday-surprise/blob/main/pt2.html))
  - This is the Main Quest and is only accessible by going to the link directly, or by completing the tutorial ([index.html](https://github.com/ahujaesh/birthday-surprise/blob/main/index.html))
  - Uses Internal CSS and Javascript
  - Within this main quest, your goal is to find all seven dragon eggs that are scattered around this world.
    - This is also written using [THREE.js](https://en.m.wikipedia.org/wiki/Three.js), and uses the same movement system as index.html
    - See the [todo list](https://github.com/ahujaesh/birthday-surprise/issues/17) to see all the improvements that are in progress
    - This needs to be done before **February 27, 2024** 
  - Upon completion, it says "Happy Birthday", and ends the game
  - You can view this file [here](https://ahujaesh.github.io/birthday-surprise/pt2.html)
  - I could use a lot of help completing this before **February 27, 2024**, so if you see something you think you can help with, I would be very grateful!

- Other files (not .HTML)
  - These files are used to help improve the content provided in the main files, or as GitHub files
    - For example, [CONTRIBUTING.md](https://github.com/ahujaesh/birthday-surprise/blob/main/CONTRIBUTING.md), tells GitHub what contributing guidelines I have included
    - Another example is [favicon.png](https://github.com/ahujaesh/birthday-surprise/blob/main/favicon.png), as it adds the favicon to both .html pages
  - Please ignore the files in .idea, my main editor, Android Studio for Windows, added them and I don't know why. If you know, feel free to shoot me an email.
- Other files (.HTML)
     - [eggsTesting.html](https://github.com/ahujaesh/birthday-surprise/blob/main/eggsTesting.html)
       - This is used to test the eggs placement, and will eventually be merged into [pt2.html](https://github.com/ahujaesh/birthday-surprise/blob/main/pt2.html)
           - UPDATE (Febuary 23, 2024): This was merged into pt2.html by [this](https://github.com/ahujaesh/birthday-surprise/commit/67f5d59f301ae8bc1d08e853359b1df430771611) commit on Febuary 22, 2024, and is now depreciated.
       - You can view the rendered result of this file [here](https://ahujaesh.github.io/birthday-surprise/eggsTesting.html).
    - [testing.html](https://github.com/ahujaesh/birthday-surprise/blob/main/.idea/testing.html)
      - Just holding some testing code.
    - [html.html](https://github.com/ahujaesh/birthday-surprise/blob/main/.idea/html.html)
      - Also Just holding some testing code.

**Credits:**

Credit to [Yugam Dhuriya (@pizza3)](https://github.com/pizza3) for inspo.
