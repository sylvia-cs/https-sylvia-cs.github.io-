---
layout: post
title: 'Virus Modelling: Simulating an Infectious Process'
---

<ul>
  <li><a href="https://github.com/sylvia-cs/Virus-Simulator">Github Repo</a></li>
  <li>Tools: OCaml (functional programming), OCaml Graphics</li>
</ul> 

In this project, I developed a simulator that models an infectious process within a population. The config file defines a set of customizable parameters that create a variety of scenarios, including the mobility and size of the population, initial portion of infected individuals, the level of infectiousness, quarantined individuals, and recovery time. In my implementation, I developed “hubs,” or areas of high traffic such as grocery stores. These variables allow the simulator to adjust its model to the effects of social measures, such as social distancing, as well as the nature of the virus.

The simulator also attempts to model the importance of “flattening the curve” of viral outbreaks by setting hospital capacity and the corresponding higher mortality once a certain threshold of infected individuals is met.

This project was developed using functional programming in OCaml. I developed mathematical functions to randomize the step sizes of moving persons, calculate probabilities, find the distance between persons, determine the gaussian mean, and keep a counter of total states in the population. This project also involved object-oriented programming and inherited classes, with a broad “Person” class and more specific classes for people in various states.

<img src="{{ site.baseurl }}/assets/animation/simulation.gif">