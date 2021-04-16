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

#### Inspiration
The game was inspired by Janine's love of Pokemon and the game Magikarp Jump. Magikarp Jump is a game where trainers
raise their Magikarps to jump as high as possible. We wanted to replicate this experience using the club mascot, 
"Petey" the anteater as our main characters and community service situations as the in-game scenarios.

Janine created the art for the entire game with Winnie's assistance. It was humbling to have an opportunity to help 
her make her game a reality.

<iframe width="100%" height="315" src="https://www.youtube-nocookie.com/embed/1tId62YbfCw" title="YouTube video player"
 frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

#### Challenges
One of the challenges was creating a game that would be able to use save states. Prior to "Petey Jump", no game on the
Circle K website used save states for the player since the game experiences were short. We decided to use the GameMaker: Studio
engine's local storage functionality to save the game state in cache. This saves the need to use a server to store game state
information. The only downside was that players could not play the game on multiple computers, but this was a move we had
to make given the server back-end was reserved for other data. 

There were certain features that had a leaderboard, and to do this we introduced an internal API to link the member accounts 
to the game. This way, users can submit their high scores to a server-side leaderboard using an account system. This was challenging
since a few years later, this feature was broken due to changes to the account system that we were using at the time. However,
thanks to our earlier decision to use local save data, the game is still playable to this day.

Another challenge that wasn't able to be solved in this game is scaling. The game works great on desktop browsers, but it 
was also meant to be used on mobile devices via a mobile web browser. The scaling was a bit off, and it's something I appreciate in
other game engines like Unity which would have accounted for this better.

<iframe width="100%" height="315" src="https://www.youtube-nocookie.com/embed/rV7tJ4qKep8" title="YouTube video player" 
frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

#### Accomplishments
This was the first game that I completed where the game was meant to be played over multiple days. It fell short in its
feasibility, but it was still a game to be very proud of. 

Janine was personally very proud of this game, and later on she would work on other art projects on a larger scale. I think
I could come up with a better write-up about how much it meant for me to work with her on this project, but I suppose I 
don't have the words at the moment. Thank you, Janine.

#### What's next
There is a possibility that I try to remake this game in Unity as an exercise one day. Perhaps, only time will tell.

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