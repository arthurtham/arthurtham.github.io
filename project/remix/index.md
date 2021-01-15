---
title: UCICKI Remix
description: Project Description
published: true
layout: projectabout
projects:
    remix:
        id : "remix"
        thumbnail : "Remix"
        title: "UCICKI Remix"
        shorttitle: "UCICKI Remix"
        date: March 2019
        playurl: http://nexus.ucicirclek.com/Remix/
        infourl: https://devpost.com/software/ucicki-remix
        description : The Biggest Crossover Game in UCICKI History!
        tags:
            - "GameMaker:Studio"
            - PHP
        hackathon: false
        demoed: false
        awards:
        team: Solo
        context: UCI Circle K
        role: Sole Programmer/Graphic Designer
        roledescription: "Translated 15 games from their original
        sources to GameMaker: Studio language. Compiled a selection of
        music to accompany the celebration of 6 years of games on the
        UCI Circle K website. Developed PHP back-end to handle leaderboard.
        Conceived algorithm to generate random puzzles per play."
        videourl: xzq_-RmhEow
---

# About UCICKI Remix
UCICKI Remix is the ultimate game combining every game from the 
!()[UCI Circle K website] into one game! Players play from a selection
of 18 minigames in rapid-fire succession for the highest score to be the
ultimate UCICKI gaming champion. The game format was inspired by 
the show "Genius Junior" and "WarioWare".

---

# Development Process

This is still a work in progress! Check back soon!

#### Concept
This game takes inspiration from Genius Junior and WarioWare. 
It was decided that the game would adapt Genius Junior's
rapid-fire questions and time mechanic in the Cortex while 
introducting mini-games as the puzzles the player would solve.

In total, there were 8 games on the UCICKI website that needed to 
be ported to this game using the GameMaker: Studio engine. The reason
why this engine was used is because most of the games to be ported
were made in GM:S and it also allows for touch-screen interactions
for mobile devices. The game would then be playable on any device
that supports a web browser.

The remaining 10 games are original games, some inspired from the Cortex
and some inspired by other aspects related to the UCICKI club activities.

#### Porting The Games to the GM:S Engine
8 games needed to be ported. Some were easy to port, while others had to be 
reconstructed from scratch or forked from other open-source projects.

- "8192" referred to the UCICKI game "4096", which was based off the popular puzzle
game "2048". Because the swiping motion could not be easily replicated in the GM:S engine,
it was decided that the game would be represented with 000.

- (Writing more soon!)

---
# Some Additional Information

{% for projectItem in page.projects %}
{% for info in projectItem offset:1 %}
<p><a href="{{info.infourl}}">Devpost Description</a></p>
{% endfor %}
{% endfor %}

> Games (c) 2014-19 Circle K International at UC Irvine, (c) 2015-16 Just the TIP,
(c) 2016-17 TIP Donuts, (c) 2017-18 RamenTIP, (c) 2017-19 BrowntulStar
> 
> More in "About" page in-game.
