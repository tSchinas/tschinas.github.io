---
title: Summit Sprint
layout: splash
permalink: /summitsprint/
intro:
  - image_path: /assets/images/Summit_Sprint_Logo.png
    excerpt: "Summit Sprint is an original touch input climbing game developed in Unity<br/>as part of a large, interdisciplinary project completed at Futuregames in conjunction with Turborilla, who supplied a request for proposal."
feature_row0:
  - image_path: /assets/images/summitsprint0.jpg
    title: "<b>Systems Design</b>"
    excerpt: "<p align=justify>My main role on the project was that of system designer, a role I had yet to play. After the design team had decided upon the mechanics we wanted to include in the game, I began designing the underlying systems that would support those mechanics. The main system I will highlight here is the \"stamina\" system, which eventually would come to be called the chalk system.</p>"
feature_row1:
  - title: "<b>Chalking Up the Stamina System</b>"
    image_path: /assets/images/summitsprint1.png
    excerpt: "Climbing equals stamina bar. Games have done this for years, unquestioning. And so we too landed on stamina as a means to prevent them from invalidating our core gameplay—balancing between manipulating the character's hands and ability to jump.<br/><br/>The <b>original</b> approach was simplistic: stamina steadily drains, jumps consume a chunk of stamina, and stamina 0 = loss. I wasn't happy with this because I felt it would encourage players to simply input moves as quickly as possible without thinking, and it could discourage them from ever using the jump. I took similar issue with the <b>second</b> approach, in which stamina decreased at a fixed rate while either hand was searching for a handhold. This also forced players to input moves quickly in the name of stamina efficiency, and ran the risk of punishing skilled players for split-second innovations in play. I also felt it would be difficult to onboard players in this approach.<br/><br/>In the third iteration, stamina would decrease at a fixed cost with each successful hand move. We decided this would be the easiest to teach and the easiest to manage, striking a balance between \"extreme sport\", as was necessary for the RFP, and puzzle, rewarding the player for efficiency and knowledge of a level when replaying for a faster completion time. However, with player skill standing as one of our core pillars, the idea of 0 stamina resulting in an immediate loss still had one glaring issue: at a certain point, a loss becomes a foregone conclusion. "
feature_row2:
  - image_path: /assets/images/summitsprint2.png
    title: "<b>Other Systems</b>"
    excerpt: "lorem ipsum"
---
{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row0" type="left" %}

{% include feature_row id="feature_row1" type="right" %}

{% include feature_row id="feature_row2" type="left" %}