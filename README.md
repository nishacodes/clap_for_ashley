Codename: Corgi
=================================
This is a private repo, for only BK-000 students. Only contributors can see it and only students in our class will be contributors. Please keep it a secret from Ashley until we launch it! Just let me know if you want to contribute. This will be our gift to her. :)

The idea of the site is that it will have a stream of her tweets, and each time a new tweet comes in the sound of applause will play, and we'll randomize an image of students clapping.

Let me know if you have any other ideas for the site! Let's make this awesome!

NOTES FOR COLLABORATORS
=======================
The whole class will have access, but please keep this a secret from our instructors. Use the codename when referring to it if they may be within earshot. (Keep your monitors out of sight, and no discussing on Piazza or Twitter!) If you want to work on the project, please note the following:

If you want to work on a feature, please let Sara and Nisha know! This is to avoid having multiple people work on the same section and minimize merge conflicts. We'll keep running lists in this Readme of what people are working on. And if you have your own idea, you can claim a route! Again, just let us know.

To start, clone this repo in your main projects directory. (Make sure this is not inside another directory with a git file! We want to avoid submodules!) No need for git init or adding a remote, clone will do this for you.

Please be descriptive in your commit messages! This is extra important with a collaboration project like this so that we can all know what changes are happening.

Also, we haven't worked on a collaborator project in Git since week 1. If you have ANY questions about using Git, please ask us! I'm almost always on gtalk at sgorecki@gmail.com. Whenever you try to push a change, remember to "git commit", "git pull", and then "git push", fixing any merge errors if they come up. Commit and push early and often to keep all our files consistent! Again, if you run into problems or concerns ask us (and not an instrucutor) before pushing.

Hurrah BK-000! Let's do this!

MAIN PAGE (Clap when Ashley Tweets)
----------------
(Please be specific and include a status: Not started, In process, or Completed). <br/>

Nikki - detect when ashley tweets and clap (Status: Complete) <br/>
Nikki (Sunday 12/1/14):
- Change so that only claps when Ashley tweets or when others tweet #clapforashley
- Add jquery to fade the gifs in and out when event is triggered

Nisha - style the layout (In process - others can join me on this)<br>
Kate - tallying daily tweets (Status: In Progress) <br>
Sarah - collect random gifs of clapping, and a clapping sound (Status: In Progress, not on site) https://docs.google.com/document/d/1zRdqpJ9al5qukRJ96ZqMnHvxzi2QxCSiK7IKTmd-QuY/edit <br>
Sara - use jQuery to trigger image/gif change when tweets are received (Status: completed see above) <br>


*** TO DOs ***
- style the layout (nisha)
- style the tweet and tweeter section
- detect when #clapforashley is trending (i.e. when someone not in our class tweets it)
- find and include gifs for random selection
- add logic to randomly select gifs to show 


SIDE PROJECTS
-----------------
If you are working on a new route, describe it here.


PROGRESS
=======================
Nikki implemented tweetstream and websockets to ensure that as soon as a new tweet comes in from Ashley, the tweet comes up on the screen and we hear applause + a picture of people clapping.

We can change the applause and image later.

If you wanna change how it works, just let me know and we will work together.
