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


#### Inspiration
"UCICKI Remix" is a game collection inspired by the show "Genius Junior" and 
the related video game "WarioWare". Towards the end of my time with Circle K at
UC Irvine, I was compelled to celebrate the success of interactive features on 
the club website by creating a game that encompasses all games currently featured
on it. Personally, I also thought it would also be a great coding challenge to 
adapt existing games into a mini-game format. 

#### What it does
UCICKI Remix is the ultimate game collection combining every game from the 
[UCI Circle K website](https://www.ucicirclek.com) into one game. Players play from a selection
 of 18 minigames in rapid-fire succession for the highest score to be the
 ultimate UCICKI gaming champion. 
 
Players set the length of the session and the minigames they want to play, and 
then they play through the minigames at random. Each game has a win condition
that rewards points the faster they are completed. It is currently the most 
recent game posted on the Circle K at UCI website.

---

# Development Process

This is still a work in progress! Check back soon!

#### Concept
This game takes inspiration from Genius Junior and WarioWare. 
It was decided that the game would adapt Genius Junior's
rapid-fire questions and time mechanic in the Cortex while 
introducting mini-games as the puzzles the player would solve.

In total, there were 8 games on the UCICKI website that needed to 
be ported to this game using the **GameMaker: Studio** engine. The reason
why this engine was used is because most of the games to be ported
were made in GM:S and it also allows for touch-screen interactions
for mobile devices. The game would then be playable on any device
that supports a web browser.

The remaining 10 games are original games, some inspired from the Cortex
and some inspired by other aspects related to the Circle K at UCI activities.


 <iframe width="100%" height="315" 
 src="https://www.youtube-nocookie.com/embed/xzq_-RmhEow" 
 title="YouTube video player" frameborder="0" allow="accelerometer;
  autoplay; clipboard-write; encrypted-media; gyroscope;
   picture-in-picture" allowfullscreen></iframe>

#### Porting The Games to the GM:S Engine
8 games needed to be ported. Some were easy to port (since they used the same
game engine), while others had to be 
reconstructed from scratch or forked from other open-source projects.

- **Colleen Clicker**: This game is a simple clicking game where players click
on the cookies with Colleen's face on it. It is a direct port of the same game
that used to be on the Circle K website, except the game ends when you click 
on enough Colleen cookies or on Colleen's meme.

- **Petey Jump**: This game references a "Magikarp Jump" clone created for 
the club where the player must raise their "Petey" plushie to be the best
jumper in the world. The minigame featured here is based off a WarioWare game
"Skating Board" where the player jumps over obstacles. To win,
the player needs to survive until they gain 500 points. The longer they survive,
the more points they gain. To avoid losing, they must jump over emblems representing
the sub-groups in the club. 

- **Induction Night**: This game involves the player looking for their mentors 
based on a given clue. It is a port of the same game on the Circle K website,
except the map is shrunk such that all the options are available. The clue and 
the figures on the screen have a correlation. Once the player figures out this 
correlation, they tap and hold on the desired option and wait for the player 
figure to walk there. Then, they press "Interact" to see if they're right or not.

- **Byron Clicker**: This game references the cookie clicker game on the Circle
K website that is a fork of the popular Cookie Clicker web game. The player simply
needs to click the cookie a shown number of times to win this game.

- **"Flappy Board"**: This game is a forked port of a template created in GameMaker: Studio
 by OvernightGamemaker, replacing the bird with a significant figure in Circle K. Thanks to the 
 template, the only modifications I had to make was add a win condition: varying the amount of points
 needed to win, and expanding the viewport such that it is widescreen. The reason 
 why a template was used is because the "Flappy Baord" game on the Circle K website was not
 created in GameMaker: Studio; thus, I had to make a decision whether to remake this game
 from scratch or not.
 
- **"CKI Invaders"**: This game is based off the same game on the Circle K website,
which is based off the retro game Space Invaders. To win, the player simply needs to 
destroy the enemy "ships", represented as emblems. The player ship itself is a reference
to another significant figure in the club. 

- **Millionaire**: This game refers to "Millionaire: CKI Edition" which is talked about
 [here](/project/millionaire/). Players are given a trivia question and must answer
 it correctly to gain points. To help them, there are three lifelines: Ask the Audience,
 Phone-a-friend, and Jump the Question. The lifelines do not regenerate for the entire play
 session, so players should be wary if they use all their lifelines!

- **8192**: This game refers to the UCICKI game "4096", which was based off the popular puzzle
  game "2048". Because the swiping motion could not be easily replicated in the GM:S engine,
  I decided to only keep the powers of 2 theme and create this minigame on that theme, where
   the player must solve for x in the formula "2 to the power of x equals a number".  
  
 
#### Original Games
In addition to the 8 ported games, 10 additional games were created, some original and some
based on other games.

- **Unscramble**: This game asks players to unscramble a board member's name. They
gain points if they're correct.

- **Math Flash**: Two numbers flash on the screen, alongside a "+" or "-" operator.
The players gain points if they answer the math question correctly.

- **Memorize The Icons**: A set of four emblems appear on the screen. When they 
disappear, the player must figure out which icon the prompt is referring to by
typing the name of the emblem. They gain points by answering correctly.

- **Chair-an-Event**: A simulation of the Circle K website appears, and players
gain points if they follow the process of chairing an event by clicking on the
corresponding buttons.

- **Super Smash Anglers**: This game is based off a project I made for a class
featuring members of the Angler family. Players click in a direction from the 
player's anglerfish to flop towards that direction, and they gain points if they
knock off the opposing anglerfish. 

- **Grid Search**: This game shows two grids that look similar, but one of the
emblems are different. The player gains points by picking the emblem that is different
across both grids.

- **Spirit Social Says**: This game is a simple recreation of a flag raising game
where the player simply needs to copy the sequence of flags being raised by the
spirit social leader to gain points.

- **Dancing Banana**: This is literally a dancing banana, and the win condition of 
waiting out the banana gif gives the player no points.

- **HOE on the Go**: The cooking event of the same name has an IRL food delivery service.
This theme was realized into this game, where the player needs to select the correct
location to deliver the food. 

- **The Attack**: This is based off of "Jack Attack", a popular segment of the game
"You Don't Know Jack" where the player taps on the screen if the hint and the answer
are related in some way. In this case, the player gains points if the hint, a name 
of a person in the sub-group, matches the name of the sub-group. The player loses
points otherwise but the game does not end, meaning the player could lose many points
for guessing.

<iframe width="100%" height="315" 
src="https://www.youtube-nocookie.com/embed/cZxIDfNXDm4" 
title="YouTube video player" frameborder="0" allow="accelerometer;
 autoplay; clipboard-write; encrypted-media; gyroscope; 
 picture-in-picture" allowfullscreen></iframe>

#### Accomplishments
I think the biggest accomplishment of this project was that I was able to combine
so many games into one package. It really brought closure to all the projects I made
for this organization, and it was also a pivotable point for me as the game engine
I was using became obsolete during development. It started my transition to Unity
soon after. 

#### What's next
"UCICKI Remix" was the swan song for me creating games for the Circle K at UCI organization.
It remains to be seen if I will make another game for them, but this was a great way to 
go out with a bang: a combination of all the games on the website, most which I had worked
on in some capacity.

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
