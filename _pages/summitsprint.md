---
layout: single
permalink: /summitsprint/
author_profile: true
intro:
  - excerpt: "Summit Sprint is an original, touch-input climbing game developed by a 16-person team in Unity as part of an interdisciplinary project completed at Futuregames in conjunction with [Turborilla](https://www.turborilla.com/ ), who supplied a request for proposal. Our goal was to create a game that would fit with Turborilla's existing catalogue of extreme sports titles."
feature_row0:
  - image_path: /assets/images/summitsprint0.jpg
    title: "<b>System Design</b>"
    excerpt: "<p>I took on the role of system designer on this project. After the team had decided which mechanics to include in the game, I began designing the underlying systems that would support those mechanics. The main system I will highlight here is the \"stamina\" system, which eventually would come to be called the chalk system.</p>"
gallery0:
  - url: /assets/images/SummitSprint_Chalkbags.png
    image_path: /assets/images/SummitSprint_Chalkbags.png
gallery1:
  - url: /assets/images/summitsprint_iteration1.png
    image_path: /assets/images/summitsprint_iteration1.png
  - url: /assets/images/summitsprint_iteration2.png
    image_path: /assets/images/summitsprint_iteration2.png
  - url: /assets/images/summitsprint_iteration3.png
    image_path: /assets/images/summitsprint_iteration3.png
gallery2:
  - url: /assets/images/summitsprint_iterationFinal.png
    image_path: /assets/images/summitsprint_iterationFinal.png
---
{% include video id="EijwO7ZWtZg" provider="youtube" %}
{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row0" type="left" image_size=20% %}

<h2 align=center>Stamina</h2>
<p align=justify>The game had to be <b>easy to pick up</b> but <b>difficult to master</b>. This had to be reflected in stamina, our main win/loss mechanic.</p>

<h2 align=center>Iterating on Stamina</h2>
<p align=justify>We wanted to focus on player skill while The initial 3 versions of the stamina system, however, left much to be desired. The most glaring issue I wanted to solve was that after a certain point, a loss became a foregone conclusion. This undermined our desire to emphasize skill.</p>

{% include gallery id="gallery1" caption="Initial iterations of the stamina system." %}

<h2 align=center>Chalking Up the Stamina System</h2>
<p align=justify>Inspired by the documentary <a href="https://films.nationalgeographic.com/free-solo">Free Solo</a>, I considered the tools free solo climbers take with them on a climb, specifically their climbing chalk. For climbers, chalk is a resource that helps to grip the rock, and they risk falling without it. I decided that this was the perfect way to represent the system. Now, instead of causing an immediate loss, the player is still able to make moves for a short time, losing their grip after a few seconds. They can continue playing, potentially picking up more chalk in the level to save themselves. I like to think of this as, for example, when in combat a player drops to 1 HP after receiving a massive attack, giving them the opportunity to overcome adversity and express their skill.</p>
{% include gallery id="gallery2" caption="Final version of the chalk (stamina) system." %}

<h2 align=center>Additional Systems & Communicating Scope</h2>
<p align=justify>We decided to include a handful of other systems, such as a ghost for the player to race against, sub objectives to unlock the option for said ghost, and a high-score leaderboard. Rather than dive deep into each of these, I'll focus on the communication taken when introducing them to other departments. I had observed some breakdowns in communication between other designers on the team and the departments they were working with, and wanted to be sure that the vision for these systems were well-explained from the start in order to set expectations about the scope and effort required to implement each feature.<br/><br/>This led me to employ MoSCoW lists, an Agile device normally used to define deliverables for an entire project. Here I used them on a micro scale, instructing the other departments of the Musts, Shoulds, Coulds, and Won'ts of each feature. In this way, my colleagues were able to immediately understand the minimum requirements to work towards, as well as any dependencies or stretch goals. It also informed them of what to discard from consideration, freeing up valuable development time.<br/><br/>While possibly an unconventional use of MoSCoW, I found this way of communicating scope and priorities to be essential to the success of the project, on which we received extremely positive feedback from the jury panel.</p>
{% include figure image_path="/assets/images/summitsprint2.png" caption="A screenshot of MoSCoW lists on Miro." %}
<p align=justify>Summit Sprint is available now on itch.io. https://futuregames.itch.io/summit-sprint</p>