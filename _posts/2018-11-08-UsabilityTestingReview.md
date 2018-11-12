---
layout: post
title: Usability Testing Review
---

# Reflecting on our Usability Tests

Over the past week, our group has conducted three usability tests, each with a different Williams College student. All the tests were held in a study room in Schow library, which we outfitted to simulate a gallery in a museum featuring our design. To implement the so-called ‘Sheep Gallery,’ we drew pictures of artwork on the chalkboards and mounted our interactive display on a wall. By doing so, we provide a scenario in which our design would be used, and place the user in realistic conditions while still having an uninterrupted, quiet environment. Further, the spatial relationship between the artworks and the display can be reproduced, so as to allow for evaluation of whether users can make sense of the relationship between the two.
	Our rationale for selecting participants was to sample not only the intended user base, art amateurs, but also the more experienced population normally found in museums. With this in mind, our first two usability tests were conducted with participants who self-identified as art amateurs, rating their care for art as 3/10 and 4/10, respectively. Our third participant was a person who cares about art, rating it a 6/10. With this selection, we get the bulk of our data from art amateurs --  the intended base -- allowing us to understand where our design does well and does poorly in terms of understandability, clarity and similar metrics with those for whom it’s designed. By evaluating an art non-amateur, we get a sense of how typical museum patrons would receive the feature and whether they’d be able to navigate it in an effective manner as well. 
Our protocol for the first test was as follows, as described in our usability testing check-in. We began the test by providing the individual with some context, so as to reduce the artificiality of the tasks and experience. We informed the user of their current situation: they are a person entering the “Sheep Gallery” who likes art, but does not visit art museums often and does not usually feel entirely comfortable in them. We omitted this part for the participant who cared about art. The user is then made aware that the museum has a feature that allows members to share their emotional responses to artworks and see them appear on a large interactive display in the corresponding exhibit. By looking around the mock museum we constructed in Schow, the participant can see various artworks, as well as the large interactive display. We designed our usability test such that at the start time, the participant has already opted-in to the program at the start of the test, and has the web-app open on their smartphone, which we provide. The user is then asked to explore the museum as they would, trying out the feature as they go. We explain to the user the following tasks, without describing how exactly to accomplish them.

Task 1: Sharing Emotions: Find a piece of art and share an emotional response. Figure out how many people felt the same way as you.

Task 2: Commenting: Leave a comment about an artwork and see how people who felt differently reacted.

In leaving the mechanisms of task completion unexplained, we under-specify the tasks so as to elicit the confusion and decision-making that might arise in real life use. We also asked the participants to narrate their thoughts out loud, especially any points of confusion.
	The roles of our group members in our usability tests were as follows: Will took notes, Anjali facilitated the interaction between user and interactive display, and Noah facilitated the interaction between user and mock phone. 
	After running this first test, we did not encounter any significant issues with our protocol, and it thus stayed largely the same for the subsequent two tests save for a couple important revisions. First, we made sure to explain in more detail the large interactive display and how it works. Our first participant, Stewart, did not realize that our paper mockup of the display was meant to be a touch screen with tap and swipe capability. These fundamental aspects of our paper prototype must be communicated so that our participants can navigate the simulation. So, we added swipe indicators on our smartboard and had no similar issues with the subsequent two tests, the first being with another art-amateur, Richart. 
	We made no significant revisions of our protocol for our third usability test. This participant, Christinart, is a art non-amateur, so we simply omitted the part of our context discussion that pertained identity as an art amateur. 
	Overall, our usability test protocol ran smoothly. The tests yielded valuable insight and prompted important revisions to our prototype, outlined below. 


![Imgur](https://i.imgur.com/Dyjralh.jpg)



# Usability Testing Incidents


## Incidents: Stewart

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

![Imgur](https://camo.githubusercontent.com/70cca5459a0b385dd39cde296925f9f5a756ecf4/68747470733a2f2f692e696d6775722e636f6d2f643451434167362e6a7067)

We added arrows to the sides of the homepage of the large screen to indicate scrolling ability.

![Imgur](https://i.imgur.com/sJaTpPN.jpg)

### Incident 5

The user was confused by the display of blank, unhighlighted people on the “Filter by Feeling” screen, and could not tell if any emotion or group of people were supposed to already be selected. We rate this issue as 2 on the severity scale.


![Imgur](https://i.imgur.com/cPpef6I.jpg)

We decided that in the actual display, an emotion will always be highlighted and the corresponding group of people will always be highlighted. This will make it clearer to the user that they can select an emotion to filter the crowd of people by that emotion. We also wrote a blurb on the side of this page to indicate that the visualization represents all of the people who reacted to the feeling.

![Imgur](https://i.imgur.com/YNMOC8i.jpg)


### Incident 6


The user was confused by the button depicting a pencil on the large screen’s reply page, which is meant to indicate the option to write a comment versus typing a comment. We rate this issue as 2 on the severity scale.

![Imgur](https://i.imgur.com/VrD0Tus.jpg)


We’ve added two larger buttons on the side of the large screen’s comment box that say “TYPE” and “WRITE” (with WRITE in more of a handwritten font). If you touch “TYPE”, a keyboard will pop up. If you touch “WRITE”, a pop-up says “Write your comment with one of the styluses located next to the screen!”

![Imgur](https://i.imgur.com/zScBIyC.jpg)


We implemented all of these changes before conducting the next two usability tests.


## Incidents: Richart and Christinart

### Incident 1

Richart did not know what it meant to “See more at the nearest display” or that this was supposed to be a button. He said that “display” was vague. Christinart also had difficulty telling that “See more at the nearest display” was supposed to be a button and wasn't sure what the purpose of the display was before going to it. We rate this issue 2 for severity.

![Imgur](https://i.imgur.com/HYT4vqj.jpg)

We changed the button to have a little arrow icon in a circle within it, a common indicator of a clickable button in online applications. We also added a blurb that the user can use the display to "see everyone's responses to the artworks in the gallery".

[Imgur](https://i.imgur.com/YUImZEK.jpg)

![Imgur](https://i.imgur.com/PXwV2uo.jpg)


### Incident 2

Richart mentioned that he had no context for the "65 people" number that was shown into the app: What percentage of responders is that? We rate this issue 1 for severity. Christinart also mentioned that she would be interested in seeing the distribution of how other people felt.

![Imgur](https://i.imgur.com/YMGF1Er.jpg)


While we think having the app only show raw numbers of people is the best way for people to feel like they belong to a group (low percentages may be demoralizing), we agree that a combination of statistics and raw numbers would be good to provide to the curious user. We've added this functionality to the large display rather than the phone so that people who want to "explore" other responses can see this information, but phone users are not immediately told that they are part of an extremely small group. We think this is the best balance between interesting information and promoting social belonging. A raw number and a percentage of the total appears reactions appears when the user selects a reaction on the board. The user can also press a button that says "View Total Statistics" to highlight every group at once and show numbers and percentages for all of them.


![Imgur](https://i.imgur.com/5wSX7VN.jpg)


### Incident 3

Christinart assessed that the type icon would bring up a keyboard and the write icon would let her draw on the screen. This is an encouraging positive incident, since we made this change after our Usability Testing Checkin.

![Imgur](https://i.imgur.com/zScBIyC.jpg)

## Iris Feedback

Iris mentioned that we should have our "filter by feeling" screen animated to make it clear to the user that it is not a static screen. This was actually an intended feature and was accidentally left out of the Usability Testing Checkin.

![Imgur](https://i.imgur.com/5wSX7VN.jpg)

Iris pointed out that the message telling people to tap a piece of art would not be usable for children and non-english speakers. We give this issue a severity of 2. 

![Image] https://i.imgur.com/nBvcG6n.jpg

As Iris suggested, we added a hand icon which would be animated in a real electronic design to show the user that they can tap a piece of art.

![Imgur](https://i.imgur.com/BDhuH5a.jpg)

Iris encouraged us to pursue more forms of data visualization. Combined with Richart's request for more statistics, we added a visualization to the large display available when clicking a "TAP" button to see exhibit-wide statistics. The visualization shows the total proportions of emotional responses for the entire exhibit, so users can see how people responded to the exhibit as a whole rather than just a specific piece of art. The visualization shows a face paritioned like a pie chart into colors and portions of a facial expression representing how people reacted.

![Imgur](https://i.imgur.com/Haiz3CA.jpg)


## Overview of Revised Prototype

![Imgur](https://i.imgur.com/nZzw1zi.jpg)

## Task Walkthroughs

### Task 1: Sharing Emotions: Find a piece of art and share an emotional response. Figure out how many people felt the same way as you.

The user begins on their phone's camera screen. A QR code at the front desk of the museum brings the user to the Amarteurs webpage.


![Imgur](https://i.imgur.com/Gzw1pIp.jpg)


The user arrives at the Amarteurs webpage where they are asked for permission to run the webapp. If they hit Decline, the prototype is over. If they hit Accept, they will be brought to the app's idle screen.


![Imgur](https://i.imgur.com/CxbzQbG.jpg)


Here is the idle screen of the webapp, waiting for the user to approach a piece of art.


![Imgur](https://i.imgur.com/CxccdS1.jpg)



The user approaches a piece of art and is prompted to select how they feel. They can tap to select an emotion from the different emojis below the piece of art. 


![Imgur](https://i.imgur.com/7kO6Cjz.jpg)


The user has chosen their reaction emoji. They are shown a screen with the reaction they've chosen, with the option to go back or submit their reaction. If they go back, they return to the previous screen with the possible emotions and the photo of the piece of art. If they choose to submit, they are brought to the next screen.


![Imgur](https://i.imgur.com/bu2jcta.jpg)


The user has chosen to share their reaction emoji. They are told the number of people who felt the same way (chose similar reactions) and are shown that number of faces with the same expression as the one they chose. The user sees that other people reacted the same way they did (the numbers are slightly fudged so that some minimum number of people are always shown to have reacted similarly).

![Imgur](https://i.imgur.com/YMGF1Er.jpg)



### Task 2: Commenting: Leave a comment about an artwork and see how people who felt differently reacted. 


Beginning where they left off, the user can tap the "Comment" button to progress to the next screen.


![Imgur](https://i.imgur.com/YMGF1Er.jpg)


This screen asks the user to type a comment. They can tap the send button to submit their comment. The comment is pre-prepared in the paper prototype.


![Imgur](https://i.imgur.com/uE8BqZi.jpg)


The user has submitted their comment and is taken to a screen with comments in speech bubbles. These comments were deemed "similar" to the user's comment, and the words that triggered the similarity algorithm are **bolded**. If other people had similar thoughts, the user is shown that other people had similar thoughts and is thus validated. Otherwise, the user is still shown a list of comments that are deemed closest. They are prompted to go to the large screen if they want to see more comments, and can click the button over this text to go to a map showing the location of the screen.


![Imgur](https://i.imgur.com/YUImZEK.jpg)


The user has gone to the board. In its initial state, it has a visualization of the exhibit with paintings surrounded by hues representing peoples' reactions to that art piece. The user is prompted to select an art piece by tapping. In the prototype they should choose "One Sheep, Two Sheep".


![Imgur](https://i.imgur.com/BDhuH5a.jpg)


The user has selcted a painting by tapping on it. There are a bunch of silhouettes congregated at the painting and a list of emojis at the bottom to choose from to see how many people chose that specific emotion and what they commented. These selections rotate automatically waiting for the user to press one.


![Imgur](https://i.imgur.com/5wSX7VN.jpg)


The user has tapped an emotion (_Angry_ in this prototype) and now sees the highlighted silhouettes of people who reacted with this emotion. They are also shown comment bubbles coming from the highlighted silhouettes. Tapping the comment bubbles takes the user to a thread of comments from that group


![Imgur](https://i.imgur.com/5wSX7VN.jpg)


The user has pressed the comment bubbles and sees all of the comments associated with that reaction lain out. The user can tap "See Thread" next to a comment if there are existing replies and can directly tap the reply button to move to the replying screen.


![Imgur](https://i.imgur.com/FBLfHLZ.jpg)


The user tapped the "See Replies" button and now sees all of the replies to that comment uncollapsed. The user can reply to any of these comments using the keyboard.


![Imgur](https://i.imgur.com/SyT92Kr.jpg)

![Imgur](https://i.imgur.com/j7WXGb4.jpg)


## Our Most Important Revisions

### Revision 1 - Finding the Virtual Display 

The first critical revision we made was modifying the final screen of our web app so that the relationship between the web app and the interactive display was more clear. We modified the screen so that there was a button that said “see more at nearest display”. By pressing this button, users would be redirected to a map that directs them to the nearest screen. This feature was added after feedback from our first usability test, and we discovered that it helped alleviate some of the confusion around the relationship between the web app and the board. Clarifying this connection is important for our design because the interaction between the web app and the interactive display is critical to the process of cultivating community and acceptance for the user. It would also be ineffective to have the interactive display if users were unaware of it or did not understand its purpose.

### Revision 2- Adding general statistics

The participants of our final two usability tests (Christinart and Richart) both expressed a desire for more general statistics. Richart brought up the key point that simply validating the user constantly without providing other interesting statistics such as percentages or “emotion” breakdowns of all museum-goers may have diminishing returns over time. To improve this, we have added a button to both the home screen of the visualization and the artwork-specific screen with the silhouette people. The former button allows the user to see exhibit-wide statistics, including breakdowns of different emotions across the exhibit. The latter allows the user to see a similar set of statistics for the selected painting. One of the primary statistics visualizations we designed is an emoji-style face that is also a pie chart of different emotions. We believe that adding such a feature is critical to enhancing the experience for the user and keeping them interested in using our design. It also adds another element to the “community-building” aspect of our design.

### Revision 3 - Clarifying the silhouette visualization on the interactive display.

One of the most valuable pieces of feedback we received from our first usability test was that the participant was confused by the group of silhouetted people that appeared when she chose a painting on the interactive display. We had intentionally left the group of people silhouetted because they represented the entire group of viewers of that painting. When the user selected a feeling to filter by, a certain portion of the group would glow in a specific color. This logic was not, however, immediately obvious to our participant. In response to her confusion, we added two features. The first is a simple explanation on the size of the visualization that says “This is the group of all the people who viewed this painting”. The purpose of this line is to clarify explicitly, what the group is meant to represent. It also provides a good context for the “filter by feeling” component. The second feature we added is that  in its idle state, different portions of the silhouetted group will light up in different colors as the emotions corresponding to those colors light up as well. This is a visual representation of the idea that the large group we display represent the group of all viewers and is effectively a conglomeration of groups of viewers who expressed different emotions. These are critical features because in order to effectively interact with the board, it is imperative that our visualization be clear and that their intention be obvious to the museum-goer. We want them to spend no time being confused and more time exploring our design.

### Revision 4 - Keyboard/Pen options on the comment box

In our initial design, when the user chose to reply to someone’s comment on the interactive display, they were shown a reply box with options to type their reply or write it using a stylus. We discovered through our usability tests that those options were too small and not obvious at all to the user. To clarify this, we added large buttons to the side of the reply box. Clicking the “Type” button pops up an on-screen keyboard. Clicking the Write button pops up directions to “Write your comment using one of the styluses near the board”. With these added instructions, these two options become more accessible to the user. The reason we care about this, is because we feel that allowing the option to hand-write your reply adds to the “amateur” aspect of the community we are construction, and creates a more personal feel to interactions.

