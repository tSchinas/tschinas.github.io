---
layout: single
permalink: /summitsprint/
author_profile: true
classes: wide
intro:
  - video:
      id: "EijwO7ZWtZg"
      provider: youtube
    excerpt: "Summit Sprint is an original touch input climbing game developed by a 16-person team in Unity as part of an interdisciplinary project completed at Futuregames in conjunction with [Turborilla](https://www.turborilla.com/ ), who supplied a request for proposal."
feature_row0:
  - image_path: /assets/images/summitsprint0.jpg
    title: "<b>System Design</b>"
    excerpt: "<p align=justify>My main role on the project was that of system designer, a role I had yet to play. After the design team had decided upon the mechanics we wanted to include in the game, I began designing the underlying systems that would support those mechanics. The main system I will highlight here is the \"stamina\" system, which eventually would come to be called the Chalk system.</p>"
gallery0:
  - url: /assets/images/Summit_Sprint_Icon.png
    image_path: /assets/images/Summit_Sprint_Icon.png
  - url: /assets/images/Summit_Sprint_Icon.png
    image_path: /assets/images/Summit_Sprint_Icon.png
  - url: /assets/images/Summit_Sprint_Icon.png
    image_path: /assets/images/Summit_Sprint_Icon.png
gallery1:
  - url: /assets/images/Summit_Sprint_Icon.png
    image_path: /assets/images/Summit_Sprint_Icon.png
  - url: /assets/images/Summit_Sprint_Icon.png
    image_path: /assets/images/Summit_Sprint_Icon.png
  - url: /assets/images/Summit_Sprint_Icon.png
    image_path: /assets/images/Summit_Sprint_Icon.png
gallery2:
  - url: /assets/images/summitsprint2.png
    image_path: /assets/images/summitsprint2.png
---
{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row0" type="left" %}

<h2 align=center>Climbing = Stamina Bar</h2>

<p align=justify>Climbing equals stamina bar. Games have done this for years, unquestioning. And so we too landed on stamina as a means to prevent them from invalidating our core gameplay—balancing manipulation of the character's hands and ability to jump to achieve the fastest time.<br/><br/>The initial iteration was simplistic: stamina steadily drains, jumps consume a chunk of stamina, and stamina 0 = loss. I wasn't happy with this because I felt it would encourage players to simply input moves as quickly as possible without thinking, and it could discourage them from ever using the jump. I took similar issue with the second iteration, in which stamina decreased at a fixed rate while either hand was searching for a handhold. This also forced players to input moves quickly in the name of stamina efficiency, and ran the risk of punishing skilled players for split-second innovations in play. I also felt it would be difficult to onboard players in this approach.<br/><br/>In the third iteration, stamina would decrease at a fixed cost with each successful hand move. We decided this would be the easiest to teach and the easiest to manage, striking a balance between "extreme sport", as was necessary for the RFP, and puzzle, rewarding the player for efficiency and knowledge of a level when replaying for a faster completion time. However, with player skill standing as one of our core pillars, the idea of 0 stamina resulting in an immediate loss still had one glaring issue: at a certain point, a loss becomes a foregone conclusion.</p>

{% include gallery id="gallery0" caption="Placeholder gallery of 3 images with placeholder caption." %}

<h2 align=center>Chalking Up the Stamina System</h2>
<p align=justify>One morning, I awoke at 05:45, fifteen minutes before my alarm went off. I had watched the documentary <a href="https://films.nationalgeographic.com/free-solo">Free Solo</a> and, while I didn't particularly enjoy my time spent watching it, I found myself thinking about the tools free solo climbers take with them on a climb—their climbing shoes and climbing chalk. I mused to myself how nice the stamina system would be if we reimagined it as Chalk, a resource to manage that didn't mean instantly losing when you ran out of it, a way to address my gripe and bring it closer to the source inspiration. "Ah, well... It's just a dream..."<br/><br/>No! I grabbed my phone and wrote my thoughts down so I wouldn't forget. A few hours later, I pitched the idea to the other designers, certain that my bewildered dream thoughts couldn't actually be a good idea. But everyone I talked to about it was thrilled with the concept. I pitched once again to the full team, informing them of the new scope of the proposal and the impact it would have on each department.<br/><br/>With the team's approval, the Chalk system was born. Now, instead of causing an immediate loss, the player is still able to make moves. Hanging on for too, however, long causes them to fall and lose. This allows them to continue playing, potentially picking up more chalk in the level to save themselves. I like to think of this as, for example, when in combat a player drops to 1 HP after receiving a massive attack, giving them the opportunity to overcome adversity and express their skill.</p>
{% include gallery id="gallery1" caption="Placeholder gallery of 3 images with placeholder caption." %}

<h2 align=center>Additional Systems & Communicating Scope</h2>
<p align=justify>We decided to include a handful of other systems, such as a ghost for the player to race against, sub objectives to unlock the option for said ghost, and a high-score leaderboard. Rather than dive deep into each of these, I'll focus on the communication taken when introducing them to other departments. I had observed some breakdowns in communication between other designers on the team and the departments they were working with, and wanted to be sure that the vision for these systems were well-explained from the start in order to set expectations about the scope and effort required to implement each feature.<br/><br/>This led me to employ MoSCoW lists, an Agile device normally used to define deliverables for an entire project. Here I used them on a micro scale, instructing the other departments of the Musts, Shoulds, Coulds, and Won'ts of each feature. In this way, my colleagues were able to immediately understand the minimum requirements to work towards, as well as any dependencies or stretch goals. It also informed them of what to discard from consideration, freeing up valuable development time.<br/><br/>While possibly an unconventional use of MoSCoW, I found this way of communicating scope and priorities to be essential to the success of the project, on which we received extremely positive feedback from the jury panel.</p>
{% include figure image_path="/assets/images/summitsprint2.png" caption="A screenshot of MoSCoW lists on Miro." %}
<p align=justify>Summit Sprint will be available soon on itch.io. Please feel free to reach out to me with any questions regarding Summit Sprint.</p>