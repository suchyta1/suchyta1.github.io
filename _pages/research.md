---
layout: single
author_profile: true
permalink: /research/
read_time: false
title: "Research and Development"
---

{%capture balrog %}<span style="font-variant:small-caps;">Balrog</span>{% endcapture %}


I contribute to several research/development projects throughout my work. 
I won't include an exhaustive list, as my group at ORNL is involved with a very large number,
so I'll focus on some of the ones that I tend to work on most directly.


## Fusion Whole Device Modeling ##

[Tokamaks](https://en.wikipedia.org/wiki/Tokamak) are experimental devices for studying fusion reactions.
[ITER](https://www.iter.org/) will be the largest such device ever constructed, whose goal is to demonstrate 
a tenfold net power yield -- i.e. to demonstrate useful energy capture from nuclear fusion.
To better understand devices such as ITER, scientists must run large-scale simulations
to investigate phenomena that occur under conditions that are not currently achievable
and to better inform future experimental design.
I am a member of team within the [Exascale Computing Project (ECP)](https://www.exascaleproject.org/) working on cutting-edge simulations.
I won't go into complicated details about the simulations, but I've included a video that gives some idea of how they progress, if you're interested.

These simulations are very computationally demanding, and require huge supercomputers to provide ample resources for the largest runs.
Compounding the problem, it is difficult to directly simulate the entire tokamak, 
because different physics needs to be resolved in different regions of the reactor -- attempting to simulate everything with enough accuracy 
using only one of the available code bases would take too long.
I am developing a framework that enables us to couple different simulation applications,
each optimized for a limited domain of the tokamak (in particular, one for the core and one for the edge),
to build a whole device model.

<div id="video" style="max-width:500px; width:95%">
<iframe id="ytplayer" type="text/html" width="640" height="360" src="https://www.youtube.com/embed/fhZN0io1KiM" frameborder="0" allowfullscreen></iframe>
</div>


## Efficient I/O with ADIOS ##

I am part of the computer science team responsible for the [ADIOS (Adaptable I/O System)](https://github.com/ornladios/ADIOS) software.
One of the biggest challenges in high performance computing is I/O (input/output). 
Large-scale simulations and experiments generate huge datasets, and saving them or reading back the data is time consuming.
ADIOS is an I/O framework that enables scientists to use a variety best-practice I/O strategies in their applications,
using a common interface that does not require users to implement the performance-minded optimizations themselves.

ADIOS has helped to speed up a variety of different application, across many domains.
I've been involved with application outreach, especially in the fusion community.
I've also taken part in ADIOS' data reduction capability development, 
and am exploring using ADIOS in new ways to facilitate access to data at multiple precision levels.

<img src="/assets/images/adios-speedup.png" style="max-width:400px; width:95%">



## Cosmology with DES ##

Since graduate school, I've been involved with the [Dark Energy Survey (DES)](https://www.darkenergysurvey.org/).
DES is an astronomy project attempting to better understand the properties of the expansion of the Universe,
in particular we would like to better measure how the acceleration of the expansion is changing with time.
Over those years, I've worked on a number things, but they've always seemed to end up involving the more technical software work.
Among other things, I was part of the team that designed the camera control system mentioned in the video (SISPI),
and also developed a new simulation package to understand systematic contaminants in the data (called [{{balrog}}](https://github.com/emhuff/Balrog))

<div id="video" style="max-width:500px; width:95%">
<iframe id="ytplayer" type="text/html" width="640" height="360" src="https://www.youtube.com/embed/qxx7UjFC93M" frameborder="0" allowfullscreen></iframe>
</div>
