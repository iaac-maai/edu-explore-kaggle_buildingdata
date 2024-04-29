# Comments

## 1st

__31/01/2024__

Some points from the discussions of the students' projects, for us to be aligned when we give them feedback @canale (shared with Oana as well):
Project about detecting defects in the wood and suggesting what to do with the pieces
        I don't think it's doable to extract the measurements from whichever photos they get and I told them that the doable part would be to concentrate on a simpler           project first and make defect detection and wood detection in a good way, assuming they have LIDAR data to extract the measurements of the wood elements themselves
Slum urban quality project
I suggested formulating how they should measure the quality of the area based on the parameters they defined, in a mathematical way based on the contours they get from the satellite images. Fot that they would need to look into the existing research (how different researchers measure these parameters) and define their score values for the areas, in the range from 0 to 1, as well as one metric that combines all the different metrics for the area. As for the contour extraction, they can get them from satellite images and then run a script in QGIS or python calculating the score values for different areas they defined (and changed values when a new house or square is being built)
Arctic project
Defining what a "good block" is for a certain area based on different parameters. They would probably need to simulate it in grasshopper to get the values for their blocks in order to predict it for the new blocks.
Plastic bottle house
Using simple shapes (cubes and parallelepipeds) instead of bottles first, as the technical part of the project is quite challenging. Concentrate on understanding the reinforcement learning packages, simulation in unity and the programming language.
:avviso:   What I would generally suggest for all the groups is to make a project timeline, separating it in different steps. Point 0 is the input data, last point is the IDEAL DREAM PROJECT that will never be built. Steps in between are from the simplest POC possible to more and more complicated version of the project (adding more features as they go). We did this exercise with Angelos with the students in May and it worked much better to finalize the projects and to keep them concentrated on the goal. It would be great if you could do this exercise with them (or I could take it next week as well)

__Feedback from class:__
* Interaction (w Stasya) was very useful - need more interaction
* An 'A4' cheatsheet - a map of what model does what?
* They want to do the datacamp BEFORE the class and know which one they do before they come to do the notebook
* There was no follow up email about the datacamp - they're struggling a bit with structure!
* Order is important

## 2nd

__19/02/2024__

Monday:
* We did Time series and up to kaggle submission, that was interactive
* we did a quick image transformations module, understood what image features were and how to use pretrained models for object detection, classification, segmentation. They saw the code, how to find the code, how to run the code. We were all pretty tired after 3.5 hours so probably it was not the most efficient part
* 4 hours and 2 big topics works once per semester, but the best split is 2 hours lecture 1 hour consultation
* Students' [preferences](https://docs.google.com/forms/d/e/1FAIpQLScKWJkXZeZRsZswT6Tf7kbh0MaCV89jpy6PoJj-lA2JC2aVeQ/viewform?usp=sharing) for the next semester
* Most of them would like to have relatively small projects, one per session (like, detecting patterns of people's movement on a square) - which I think makes more sense than one project per term (then they start going wild with RL, own datasets and there is nothing finished in the end). At the same time it could give them some base for their own architectural / urban project / thesis
* we also got the topics they are most interested in, which could be used for smaller projects. Students that want to do their own project and have a clear idea on it can have this option, but I would opt to keep these two: one-class exercises (projects) AND / OR consultations if a person knows exactly what he/she wants to do

Wednesday:
* we did time series today (everyone was too tired to go deep into images) and checked how to train our model and submit predictions on kaggle
* I shared the notebook with working-with-images and explained how to use the code on their own images (without going into detail on how it works)
* Explained that the main packages to work with are opencv and torch - and how to search what they need to do
in general they seem to understand the code pretty well, some students are struggling but it's okay, we all do
* :avviso:   Datacamp: everyone understood what we need to do, but they were short on time and couldn't complete it. We made a deal that they will have a late deadline (around 11th of March, so that they have 1 week after the finals to do the datacamp and the exercises I gave)
* Datacamp: Sevahn came up with a good suggestion to have courses relevant to their studio projects. So the students who want to go deeper into a specific topic told me that and they will be learning that specific topic :faccia_leggermente_sorridente:
* :simbolo_addizione_in_grassetto:   the part that worked best in both the groups was the interactive exercise: I mixed students from different groups to form groups of 3 people and gave them a task to find patterns in data. Like that they did some coding together, brainstorming on which patterns these could be and why these patterns were there in the data and did some coding together!

## 3rd

__10/04/2024__

Monday:
:dna:  Summary:
* One-class exercises seem to work well;
* Some students from both the studio and the seminar understood how to use what we learnt during the exercises in their projects - we discussed it during the consultations
* It's more effective and engaging to start the exercise straight away, skipping talking about the theory, code, packages etc. The only two things that should be mentioned before starting hands-on are the end goal of the exercise and the starting point (e.g. where to get the data or which zone to analyze).

I actually have a suggestion on the next exercises. We could take the actual problems students are coming to us with during the consultations and make exercises out of them.
I noticed that there are many people who might benefit from an exercise on optimization, so if I manage to find a way to make a quickstart that is understandable in one session, I would like to do it with them next time.
We covered during these two sessions:
object detection and tracking with Yolo
osmnx, street network analysis and geometrical operations with shapely (seminar)
The second one seems to be useful for many thesis projects