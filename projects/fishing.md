---
layout: project
type: project
image: img/fishprof.jpg
title: "Fishing Game"
date: 2021
published: true
labels:
  - Java
  - GitHub
summary: "Dive into the thrilling virtual waters of my ICS 211 Final project, a collaborative fishing game, where players strategize, cast lines, and compete to build the ultimate fish stash and be crowned the fishing tournament champion."
---

<div class="text-center p-4"><img class="img-fluid" src="../img/bannerfish.jpg"></div>

### **Immersing in the Adventure of Aquatic Challenge** 
In my final project for my ICS 211 class, I collaborated with two teammates to create an engaging fishing game that aimed to simulate the excitement of a fishing tournament. The game was designed to be played by two alternating players on the same computer, with each player attempting to catch fish and build a "sack" of fish. The game followed a structured set of rules and mechanics to ensure an immersive and competitive experience.
The project encompassed three distinct phases: Loko i'a (Fish Pond) Setup, Lawai'a (Fishing), and Game Over.



<hr>

* **Game Phase 1** - Loko i'a (Fish Pond) Setup: 
 During the initial phase, our focus was on populating a virtual fish pond, represented by an ArrayList. We introduced baby fish from different fish families into the pond. Over a simulation period of approximately 2 years (24 months), the fish grew to attain legal sizes for fishing.

<img class="img-fluid" src="../img/fish.map.png">

* **Game Phase 2** - Lawa i'a (Fishing): 
The core gameplay revolved around the fishing phase. This stage spanned a "year" (12 months) and involved the alternating turns of the two players. Each player was given three attempts to catch fish during their turn. These attempts could yield three outcomes: no fish caught, successful capture of a fish (which could be chosen to keep or release), or the fish escaping.
If a player managed to successfully catch a fish, they were presented with the option to either keep or release it. Legal considerations, such as the fish's size and the current month, were important factors in deciding whether to keep the fish. Legal fish that met the size criteria were added to the player's sack, which was maintained as a sorted ArrayList based on fish length. In contrast, illegal fish resulted in the confiscation of the player's entire fish sack.
Players were also granted the option to view the contents of their fish sack and release specific fish back into the pond. This feature proved valuable as the fish population within the pond gradually declined over time.

---
<pre>
  
### EXAMPLE OF GAMEPLAY:
Player 1, it is your turn! 
* Choose:
  1. Cast out for a fish
  2. View sack of fish
  3. Throw back a fish in the sack.
  
  Choice: 1
   You have hooked a fish!
   You have caught a fish!
     Name: Uhu
     English name: Parrotfish
     Scientific name: Scarus Psittacus
     Length: 12.487740994862454
     Weight: 24.97548198972491
     Body color: blue-green
     Fin color: blue
     Sex: supermale
     
 * Do you want to keep this fish y/n? y
  You have kept your fish
  Your fish is legal and has been added to your sack

Other outcomes would be:
  You have kept your fish
   You kept an illegal fish!
   You got a ticket and all of your fish were confiscated!

or
 Your fish got away!

</pre>
---

* **Game Phase 3** - Game Over:  
Upon completion of 12 months of turns, the game transitioned to its final phase. In this phase, the fish sacks of both players were evaluated, focusing on the three largest fish by length. The player with the greatest cumulative length of their top three fish was declared the winner of the fishing tournament.
Throughout the project, we implemented different fish families (Pua_ama, Ohua/Uhu, Oama/Weke) as parent classes. These families had unique characteristics, such as legal sizes, seasons, and valid catch methods. Concepts such as inheritance, abstract classes, and interfaces in Java were employed to model these diverse fish families accurately.


This project was not only an exercise in technical implementation but also a lesson in collaborative teamwork. It provided valuable insights into Java programming concepts, including inheritance, interfaces, and abstract classes. Additionally, the project underscored the importance of effective group communication and coordination in the context of coding collaboration.

Source: <a href="https://github.com/ICSatKCC/assignment-8---final-project-fishing-game---s22-assignment-8-group-3">final-project-fishing-game</a>
