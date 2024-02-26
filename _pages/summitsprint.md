---
layout: single
permalink: /summitsprint/
author_profile: true
classes: wide
intro:
  - image_path: /assets/images/Summit_Sprint_Logo.png
    excerpt: "Summit Sprint is an original touch input climbing game developed in Unity as part of a large, interdisciplinary project completed at Futuregames in conjunction with [Turborilla](https://www.turborilla.com/ ), who supplied a request for proposal."
feature_row0:
  - image_path: /assets/images/summitsprint0.jpg
    title: "<b>Systems Design</b>"
    excerpt: "<p align=justify>My main role on the project was that of system designer, a role I had yet to play. After the design team had decided upon the mechanics we wanted to include in the game, I began designing the underlying systems that would support those mechanics. The main system I will highlight here is the \"stamina\" system, which eventually would come to be called the Chalk system.</p>"
gallery0:
  - url: /assets/images/Summit_Sprint_Icon.png
    image_path: /assets/images/Summit_Sprint_Icon.png
  - url: /assets/images/Summit_Sprint_Icon.png
    image_path: /assets/images/Summit_Sprint_Icon.png
  - url: /assets/images/Summit_Sprint_Icon.png
    image_path: /assets/images/Summit_Sprint_Icon.png
feature_row2:
  - image_path: /assets/images/summitsprint2.png
    excerpt: "lorem ipsum"
---
{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row0" type="left" %}

<h2 align=center>Climbing = Stamina Bar</h2>

<p align=justify>Climbing equals stamina bar. Games have done this for years, unquestioning. And so we too landed on stamina as a means to prevent them from invalidating our core gameplay—balancing manipulation of the character's hands and ability to jump to achieve the fastest time.<br/><br/>The initial iteration was simplistic: stamina steadily drains, jumps consume a chunk of stamina, and stamina 0 = loss. I wasn't happy with this because I felt it would encourage players to simply input moves as quickly as possible without thinking, and it could discourage them from ever using the jump. I took similar issue with the second iteration, in which stamina decreased at a fixed rate while either hand was searching for a handhold. This also forced players to input moves quickly in the name of stamina efficiency, and ran the risk of punishing skilled players for split-second innovations in play. I also felt it would be difficult to onboard players in this approach.<br/><br/>In the third iteration, stamina would decrease at a fixed cost with each successful hand move. We decided this would be the easiest to teach and the easiest to manage, striking a balance between "extreme sport", as was necessary for the RFP, and puzzle, rewarding the player for efficiency and knowledge of a level when replaying for a faster completion time. However, with player skill standing as one of our core pillars, the idea of 0 stamina resulting in an immediate loss still had one glaring issue: at a certain point, a loss becomes a foregone conclusion.</p>

{% include gallery id="gallery0" caption="Placeholder gallery of 3 images with placeholder caption." %}

<h2 align=center>Chalking Up the Stamina System</h2>
<p align=justify>One morning, I awoke at 05:45, fifteen minutes before my alarm went off. I had watched the documentary "[Free Solo](https://films.nationalgeographic.com/free-solo )" and, while I didn't particularly enjoy my time spent watching it, I found myself thinking about the tools free solo climbers take with them on a climb—their climbing shoes and climbing chalk. I mused to myself how nice the stamina system would be if we reimagined it as Chalk, a resource to manage that didn't mean instantly losing when you ran out of it, a way to address my gripe and bring it closer to the source inspiration. "Ah, well... It's just a dream..."<br/><br/>No! I grabbed my phone and wrote my thoughts down so I wouldn't forget. A few hours later, I pitched the idea to the other designers, certain that my bewildered dream thoughts couldn't actually be a good idea. But everyone I talked to about it was excited. I pitched once again to the full team, informing them of the new scope of the proposal and the impact it would have on each department.<br/><br/>With the team's approval, the new Chalk system was born.<br/><dt>lorem ipsum</dt><dd>stuffstuffstuff</dd></p>
{% include feature_row id="feature_row2" type="left" %}