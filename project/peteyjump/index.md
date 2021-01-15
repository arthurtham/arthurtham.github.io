---
title: Petey Jump
description: Project Description
published: true
layout: projectabout
projects:
    petey jump:
        id : "petey"
        thumbnail : "Petey"
        title: "Petey Jump"
        shorttitle: "Petey Jump"
        date: "November 2017"
        playurl: "http://nexus.ucicirclek.com/PeteyJump/"
        infourl: http://www.devpost.com/software/petey-jump/
        description : "In a world full of Peteys, who will train them all?
        It's up to you to mentor the Peteys and win the Spirit award at DCON!"
        tags:
            - "GameMaker:Studio"
            - "PHP"
        hackathon: false
        demoed: false
        awards:
        team: <a href="https://www.janinecarpena.com/" target="_blank">Janine Carpena</a>, <a href="https://www.linkedin.com/in/winnie-lam-138118164/">Winnie Lam</a>
        context: UCI Circle K
        role: Lead Programmer
        roledescription: "Project lead. Developed back-end system to manage save states and leveling system.
        As the sole programmer, programmed the interactivity of the GUI as designed by the two artists on the team.
        Assisted with marketing and promotion of game."
        videourl: cZg92s0v0uE
---

# About Petey Jump

#### Petey, Jump!
In a world full of Peteys, who will train them all? It's up to you to mentor the Peteys and win the Spirit award at DCON!

#### Meet the Trainers

| - | - | - |
|:---:|:---:|:---:|
| ![PeteyArthur](/img/peteyArthur.png) | ![PeteyJanine](/img/peteyJanine.png) | ![PeteyArthur](/img/peteyWinnie.png) | 
| **Arthur** | **Janine** | **Winnie** |
| Computer Science | Computer Game Science | Biological Sciences |
| *I'm from UCI Circle K.* | *I'm not a big, but I'm<br>3 letters short of a little.* | *I'm always doing things.* |

#### Features
- **Collect them all!** There are multiple Peteys to train! Will you train them all?
- **Unlock Achievements!** Unlock badges and achievements as you progress through the game! Can you collect them all?
- **Special Appearances!** Meet special familiar faces in random game events!
- **Secrets to the Game!** Can you figure out the secrets to this game?

---
# Development Process
Writing this up, coming soon!

---

# Some Additional Information

{% for projectItem in page.projects %}
{% for info in projectItem offset:1 %}
<p><a href="{{info.infourl}}">Devpost Description</a></p>
{% endfor %}
{% endfor %}



> Game created for UCI Circle K. © 2017 CIRCLE K INTERNATIONAL AT UNIVERSITY OF CALIFORNIA, IRVINE - ALL RIGHTS RESERVED
YOU MAY NOT DISTRIBUTE, COPY, NOR SELL THIS CONTENT WITHOUT EXPLICIT PERMISSION FROM ITS OWNER.

> Art by Janine Carpena.