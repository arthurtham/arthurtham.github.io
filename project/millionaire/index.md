---
title: Cash Mountain - Who Wants to be a Millionaire
description: Project Description
published: true
layout: projectabout
projects:
    millionaire:
        id : "mil"
        thumbnail : "Millionaire"
        title : "Cash Mountain - Who Wants to be a Millionaire"
        shorttitle: "Millionaire"
        date: February 2025/June 2020/October 2016
        playurl : "https://sandbox.arttham.com/Millionaire/index.php"
        infourl : "https://sandbox.arttham.com/Millionaire/index.php"
        description : "Do you have what it takes to win 1 Million dollars?
        Just answer 15 questions! Previously known as Millionaire: UCI Circle K Edition."
        tags:
            - "GameMaker:Studio"
            - Audacity
            - "PHP"
            - "mySQL"
        hackathon: false
        demoed: false
        awards:
        team: See "Info"
        context: Personal/UCI Circle K
        role: Director, Lead Programmer, Graphic Animator
        roledescription: 'Configured mySQL backend with PHPMyAdmin and Ubuntu.
        Developed random question picker and question bank system flow.
        Re-created some music and sound effects for an authentic game show experience.
        <br/><br/> Previously known as <a href="http://nexus.ucicirclek.com/Millionaire/" target="_blank">
        Millionaire: UCI Circle K Edition in 2016</a>'
        videourl: 3o-cTZfk9ss
---

# About Cash Mountain - Who Wants to be a Millionaire

#### Inspiration
The game idea was conceived from my love of the game show "Who Wants to be a Millionaire".
In "Millionaire", contestants answer a series of questions to earn more money, with the risk
of losing it all if they get a question wrong.

A simulation version of Millionaire was created by me in early 2016 for Circle K International at UC Irvine.
It used this program to hold a game show activity, shown below. 
It was a huge success, as the contestants utilized the iconic Millionaire lifelines to reach
the final question, only to fall short on the last question. 

Since that show, it was decided that Millionaire will be converted into a game that can be played
by members of Circle K at UCI. Over a 6 month period, I was the game director and programmer
and developed the game in GameMaker: Studio with a group of UCI students, releasing on time in 
October 2016 for PC and Mac, and January 2017 for web browsers under the name 
"Who Wants to be a Millionaire: CKI Edition"


#### What it does
"Who Wants to be a Millionaire" is a take on the popular trivia game show of the same name. 
First created in GameMaker: Studio in 2016, it featured the classic three lifelines and a 
custom set of questions. It was one of the first GameMaker games I ever made for a target, 
public group of people in a collegiate club.

The rules of the game are simple: answer 15 questions, and you will win 1 Million Virtual Dollars.
 The more questions you get right, the more virtual money you will win. You have three lifelines 
 to help you, so use them wisely.
 
 <iframe width="100%" height="315" src="https://www.youtube.com/embed/3WOVmzOL9oE" 
 title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; 
 gyroscope; picture-in-picture" allowfullscreen></iframe>

---

# Development Process

#### Development
Development of "Millionaire: CKI Edition" started in March 2016. It is based off the project I worked on in Summer 2015, 
a simulated game-show controller where users can load question packs and simulate producing the game show
with their friends as contestants. 

Both projects were created in **GameMaker: Studio.** Early on, the plan was to develop the game for PC and Mac. It would
be the first game to be developed to run on computers without a web browser. Later on, the decision was made to 
publish the game for web using GameMaker: Studio's HTML5 engine. (See challenges)

The user interface builds on the game show's question graphics, using similar fonts and style. For reference, 
our team analyzed previous Millionaire games for mobile devices, consoles, and arcade machines. We found that 
it was the most intuitive to click on the answers and lifelines directly, without asking for the catchphrase
"Is that your final answer?" This led to a faster user workflow and gameplay.

The questions were based off of Circle K at UCI's history, though the 2020 version used questions from 
Season 1 of the U.S. Primetime Revival on ABC. To load the questions, we obfuscated them in question "packs" 
based on the perceived difficulty of the questions. The game would then load the questions on demand depending on 
the question difficulty level. Various formats were used: in the original release, we based it off
the 2009 U.S. Primetime Special rules for the money tree and clock. It was later changed to the original money
tree in the 2020 release. 

The soundtrack was remixed in Garageband by me using existing midi scores for an original feel to the game. 
Graphic artists Eric Vu and Vincent Tang worked on adapting the graphics for a modern audience, especially
the lifeline art and game logo.

Upon its release, other than some challenges, it was a huge success. It released for PC and Mac and many of 
the club members enjoyed the trivia. It later released for web browsers and continues to be playable on the
Circle K at UCI website today.

<iframe width="100%" height="315" src="https://www.youtube.com/embed/SVXdFOtjgtE" title="YouTube video player" 
frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
allowfullscreen></iframe>

#### Challenges
One of the biggest challenges was the change of approach in developing the game for Circle K.
Before "Millionaire: CKI Edition", the features games made were forked from existing games.
Thus, creating a game from scratch was no easy task and sometimes made collaboration difficult due to 
the nature of GameMaker: Studio and its use of Github. The development time for "Millionaire: CKI Edition"
was 6 months, way longer than 2 weeks; but we made it through, a huge accomplishment for the team.

This was also the first game to use an online leaderboard. However, the implementation of it was difficult.
We tried to use mysql, but because the "Millionaire" was so popular, others eventually found the game and 
easily hijacked the mysql code. Unfortunately, the online leaderboard had to be removed from the game.

The PC and Mac release, although successful, had some struggles since we did not have an official developers
license to publish on both platforms. Thus, with the rise of security initiatives in modern operating system,
the games would sometimes not open. This was eventually rectified in the online, HTML5 version which is 
still available now.


#### Accomplishments
Millionaire: CKI Edition was the first game that I published for an organization. 
It contributed towards winning an award for best club website within the Kiwanis
Cal-Nev-Ha division. It was also the first HTML5 game I even published.


#### What's next
"Millionaire: CKI Edition" was widely successful among club members as a trivia game promoting
knowledge of Kiwanis history, and it was the first of many games developed by me for Circle K
at UCI.

After patching the game in 2020 for demonstration purposes (ie. replacing all the questions
with general knowledge questions), the game will probably not be updated in the near future.
In any case, Millionaire is the game that truly got me into game development. I am proud
of it and it will continue to be a highlight of my young game development career.

---
# Some Additional Information

{% for projectItem in page.projects %}
{% for info in projectItem offset:1 %}
<p><a href="{{info.infourl}}">itch.io Description</a></p>
{% endfor %}
{% endfor %}

<p><a href="https://v6p9d9t4.ssl.hwcdn.net/html/2419355/html5export/patch.html">Patch Notes</a></p>

> This project is a fork/continuation of version 1.1h of the game also known as Millionaire: UCI Circle K Edition. The game may not work on the old website.

> See "Info" for more information and credits.
  
  > Original: 2016 Arthur Tham. Updated in 2020 and 2025.
  
  > Original Game created for UCI Circle K. 
  >© 2016-17 CIRCLE K INTERNATIONAL AT UNIVERSITY OF CALIFORNIA, IRVINE - ALL RIGHTS RESERVED
  YOU MAY NOT DISTRIBUTE, COPY, NOR SELL THIS CONTENT WITHOUT EXPLICIT PERMISSION FROM ITS OWNER.