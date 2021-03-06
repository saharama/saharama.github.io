---
layout: project
type: project
image: images/cpp/cpp-gameWin.png
title: Just Another Love Story
permalink: projects/cpp-game
# All dates must be YYYY-MM-DD format!
date: 2019-05-12
labels:
  - EE205
  - C++
  - Object Oriented Programming
  - GitHub
summary: My EE205 group developed an RPG using C++ and SFML graphics. We used the event-based library of SFML and object-oriented progamming techniques to make a fun game with various states and levels.
---
<hr>

My group of three used C++ and object-oriented techniques to make a Role-Playing Game (RPG). We implemented the SFML library for simple game graphics and audio.

<img class="ui image" src="{{ site.baseurl }}/images/cpp/cpp-title.png">

<hr>

The game begins with a boy named Nick. Nick's girlfriend leaves him for her evil, and more muscular ex-boyfriend, Chad. Nick departs on a quest to raise his abilities and win the girl of his dreams back!

After navigating through the maze, Nick must collect the items and help strangers in need out. He also needs to defeat a mini-boss on every level. On the last level, Nick must face a final, epic battle with Chad!

Here is a video of normal gameplay:
<div class="ui embed" data-source="youtube" data-id="re_hiU2Ni3E" >
</div>
(Note: Audio is omitted in the above video.)

<hr>

Our game is one big state-machine. Different game states are linked together and the game machine will change states depending on whether or not certain conditions are fulfilled. There are map states where you walk around to solve puzzles, and there are battle states that resemble that of the game "Pokemon".

We used a sprite machine on Github to produce 8-bit style characters. The backgrounds were hand-drawn because of the limitations of the graphics library; however the different maps and collision files were coded and connected via inheritance.

We did a lot of "hard-coding" and definitely should have implemented more object-oriented techniques to make our journey easier. We learned the benefits of classes and inheritance the hard way. While we implemented some of those techniques, more in-depth planning at the beginning of the project could have saved us a lot of time. We retraced our steps to implement more of these object-oriented techinques, but some of the code was much too redudnant and was easier to just leave be.

It was a great learning experience, and it was very fun to work together on a creative project!

<img class="ui image" src="{{ site.baseurl }}/images/cpp/cpp-gameover.png">

Sprite Machine Source: <a href="https://sanderfrenken.github.io/Universal-LPC-Spritesheet-Character-Generator/"><i class="large github icon "></i>sanderfrenken Sprite_Generator</a>

Clean Project Repo: <a href="https://github.com/saharama/EE205_FinalProject"><i class="large github icon "></i>saharama/EE205_FinalProject/</a>
