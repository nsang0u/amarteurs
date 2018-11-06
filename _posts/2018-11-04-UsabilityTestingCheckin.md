---
layout: post
title: Usability Testing Check-in
---

# Reflecting on Usability Test #1

We conducted our first usability test in what we call ‘The Sheep Gallery:’ a schow study room set up to simulate a museum exhibit. For our participant, we selected a Williams student who described herself as being an art amateur who does not frequent museums and does not care very much about art. These choices of location and individual were made based on the following rationale. The primary audience for our design is people who feel uncomfortable in art museums because they think their opinions and thoughts about art are unusual or don’t belong. Although our design would be usable by anyone, we want to ensure that it is especially usable (and valuable) for an art amateur. As such, we have chosen an art amateur as the subject of our Usability Test. In our simulated gallery, we drew pieces of artwork on the chalkboards, and mounted our interactive display on a wall. The purpose of simulating an art gallery is to provide a realistic scenario in which our design would be used, and place the user in realistic conditions while still having an uninterrupted, quiet environment. 
	We began the test by providing the individual with some context, so as to reduce the artificiality of the tasks and experience. We informed the user of their current situation: they are a person entering WCMA who likes art, but does not visit art museums often and does not usually feel entirely comfortable in them. The user was then made aware that the museum has a feature that allows members to share their emotional responses to artworks and see them appear on a large interactive display in the corresponding exhibit. By looking around the mock museum we constructed in Schow, the participant can see various artworks, as well as the large interactive display. We have designed this usability test such that the participant has already opted-in to the program at the start of the test, and has the web-app open on their smartphone, which we provide. The user is then asked to explore the museum as they would, trying out the feature as they go. We explain to the user the following tasks, without describing how exactly to accomplish them.

T*ask 1:* Sharing Emotions: Find a piece of art and share an emotional response. Figure out how many people felt the same way as you.
*Task 2:* Commenting: Leave a comment about an artwork and see how people who felt differently reacted. 

In leaving the mechanisms of task completion unexplained, we under-specify the tasks so as to elicit the confusion and decision-making that might arise in real life use. 

Reflecting on our first usability test, it is clear that our protocol worked quite well. We experienced few issues with the actual procedure of the test. Our test affirmed the virtues of task underspecification and participant narration, as our participant verbally communicated her thought process as she figured out our prototype, which allowed us to understand design issues we could not see ourselves. One revision to our protocol we plan to make for our next usability tests is to explain in more detail the large interactive display and how it works. Our participant, Stewart had no idea that our paper mockup of the display was meant to be a touch screen with tap and swipe capability. These fundamental aspects of our paper prototype must be communicated so that our participants can navigate the simulation. Overall, however, our first usability test went smoothly. 


# Cognitive Walkthrough Results and Revisions

### Issue 1
The button to share an emotional response simply says “Share”, which has online / social network connotations. This violates walk-through question 3: “Will user recognize actions as the correct one?” with a severity of 2.


![Github](https://camo.githubusercontent.com/9f26dfbb736aa908a989aa9e73b7f86fd93e58e1/68747470733a2f2f692e696d6775722e636f6d2f6c4931555742492e6a7067)


We have revised the share button to say “submit” instead, with an additional descriptive blurb to make it clear that the user will be brought to a screen showing how other people reacted.


![Imgur](https://i.imgur.com/vd3rCoL.jpg)

### Issue 2

There is no indicator in the early stages of the phone webapp that the user will actually be able to submit their responses and see what other people felt. This violates walk-through question 3, “Will user recognize actions as the correct one?” with a severity of 2.

![Github](https://camo.githubusercontent.com/f2b1fd0d7dc1bf0f8eb395089b0e5e433e3006fc/68747470733a2f2f692e696d6775722e636f6d2f765149644365642e6a7067)

We have added a “?” button to the homepage of the webapp (the sensing for artwork page) that directs the user to a blurb about the basic functionality of the app. We also slightly changed the wording on the homepage to make it clear that the user should approach a piece of art.

![Imgur](https://i.imgur.com/cTsuf4o.jpg)

![Imgur](https://i.imgur.com/HVljHD7.jpg)



# Usability Testing


## Incidents

### Incident 1

The user found the purpose of many different buttons in the prototype, such as the submit button and the question mark that we added in the cognitive walkthrough, to be clear.


![Imgur](https://i.imgur.com/vd3rCoL.jpg)


![Imgur](https://i.imgur.com/cTsuf4o.jpg)


### Incident 2

The user was told on the phone comments page to check out the large interactive display for more results, but was confused because the phone could also be considered a large-ish interactive display. We rate this issue as 2 on the severity scale.

![Imgur](https://i.imgur.com/lX4Pwug.jpg)


We added a hyperlink to the comments page that says “See more at the nearest display”. When tapped, this link takes the user to a map of the exhibit they are in with a highlighted location of the interactive display and an icon indicating the user’s current location.

![Imgur](https://i.imgur.com/HYT4vqj.jpg)

### Incident 3

The user approached the large screen, and was confused about whether they were able / supposed to select a painting. We rate this issue as 1 on the severity scale.

![Imgur](https://camo.githubusercontent.com/70cca5459a0b385dd39cde296925f9f5a756ecf4/68747470733a2f2f692e696d6775722e636f6d2f643451434167362e6a7067)

We added a sentence “Tap an artwork to explore!” to the homepage of the large screen to make the purpose of this page more clear.

![Imgur](https://i.imgur.com/nBvcG6n.jpg)

### Incident 4

The user could not tell that they were able to scroll through the visualization of paintings on the main page of the large screen. We rate this issue as 2 on the severity scale.


We added arrows to the sides of the homepage of the large screen to indicate scrolling ability.

### Incident 5

The user was confused by the display of blank, unhighlighted people on the “Filter by Feeling” screen, and could not tell if any emotion or group of people were supposed to already be selected. We rate this issue as 2 on the severity scale.


We decided that in the actual display, an emotion will always be highlighted and the corresponding group of people will always be highlighted. This will make it clearer to the user that they can select an emotion to filter the crowd of people by that emotion. We also wrote a blurb on the side of this page to indicate that the visualization represents all of the people who reacted to the feeling.


### Incident 6


The user was confused by the button depicting a pencil on the large screen’s reply page, which is meant to indicate the option to write a comment versus typing a comment. We rate this issue as 2 on the severity scale.


We’ve added two larger buttons on the side of the large screen’s comment box that say “TYPE” and “WRITE” (with WRITE in more of a handwritten font). If you touch “TYPE”, a keyboard will pop up. If you touch “WRITE”, a pop-up says “Write your comment with one of the styluses located next to the screen!”

