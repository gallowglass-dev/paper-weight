+++
author = "JSON Alexander"
title = "Game Dev Case Study: Visual Language in Directed Exploration"
date = "2026-05-13"
description = "Game Dev Case Study of the first 3 minutes in the remote village from Outlast 2"
tags = [
    "horror",
    "unreal-engine",
    "level-design",
    "game-dev",
    "visual-language",
    "outlast-2",
]
categories = [
    "Case Study",
    "Game Development",
]
+++

## Outlast 2: Visual Language in Directed Exploration
### [WARNING] Contains a gameplay image of a mutilated cow

---

I just had some ideas on visual language in horror game dev and they led me to analyze a section of Outlast 2, but first here is the thought I had:

> <div align="center">
>
> In my game, the house is a playable area and it's both pretty and useful narratively inside, while being a necessary component of the viewport from the outside – but not the focal point.
>
> In other words, it becomes environment art when no longer in the players path, and should visually communicate as much.
>
> </div>

---

## The Analysis:

In this early section, you as the character are tasked with finding your wife and escaping (as in the earlier section you find the pilot from the intro helicrash let's just say… tied up, indicating that you should not stay here).

With that in mind, you're not looking to be in a house. 

As the player, you are looking to progress through this village while observing the art and people in the bushes, and learning basic mechanics and controls (open window, peak through door, pick up battery, read note). 

To go through the houses is an emergent, feel-it-out option where testing doors can actually lead to a new little area (big dopamine drip for this type of game) potentially providing more exposition, resources, or in most cases, a place to hide.

---

#### It's The Journey, Not The Destination

From a level design pov, the houses almost never have outside lights at this stage, and when they do it's either to showcase environment art (which I never thought of as a sole purpose for light), indicate the path forward, or to introduce a new mechanic.

---

#### Sprinting Terrified in the Moonlight

![Outlast 2 moonlit landscape](/img/outlast_2-1.jpg)

The first light I observed is from the moon and it is exceptional. The moon is the only light at this point and leads down to darkness under the trees of the lower valley. 

---

#### Don't Halve a Cow

![Outlast 2 mutilated cow](/img/outlast_2-3.png)

The second light gives a momentary reprieve (but only from afar) and is directly on the path before a turn into the deeper village. It sits baked above a recently mutilated cow that lies in a shack of sorts and as you look up from the unlucky cattle, your eyes meet those of a man watching you from the bushes, knife in hand.

---

#### Window Pain

The third light is from inside a house through a half open window with a curtain tessellating from inside – indicating a new mechanic. Upon opening it a bird flies up, jumpscaring you and turning what would have been a normal part of a game’s tutorial section into an opportunity to get a third utility out of a single area of interaction.

---

## Final Thought

The design intentionality behind the first 3 minutes in this village gives me new questions and ideas about level design and a whole new outlook on my implementation process (see prep doc). It especially changed the way I think of path width, as a photon barrier creates a whole new way of manipulating sightlines and applying visual language. Multifaceted design principles make these small spaces feel massive in experience, and this all comes before even considering sound design (arguably the strongest part of the series).

---

## Clanker's Corner

There are a few other things I learned by giving the above text to a dirty clanker. Here are some concise ideas and good words to know that it spit back at me (minus the annoying attaboys it’s intent on giving the general user for asking simple questions):

```txt
Light is:
guidance
temptation
threat framing
pacing
psychological signaling

The player THINKS:
“I’m exploring a village.”

But the designer is actually doing:
lane control
eye control
tension modulation
resource conditioning
psychological baiting

“Light the ambiguity, not the answer.”

The houses are:
pacing chambers
curiosity rewards
ambiguity generators
temporary safety hypotheses

the player starts internally roleplaying exploration.

That opening of Outlast 2 is basically a directed psychological onboarding pipeline disguised as exploration.

Look at what’s actually happening structurally:

Establish navigation language
Establish fear language
Establish interaction language
Establish uncertainty
Establish progression trust
Establish vulnerability

all simultaneously.