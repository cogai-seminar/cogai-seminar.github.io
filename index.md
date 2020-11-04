---
layout: page
title: "The CogAI Seminar"
description: "When Cognitive Sciences Meet Artificial Intelligence"
header-img: "img/ens_spring.png"
---

Welcome to the Cognitive Science / Artificial Intelligence Seminar!



Goal
============================

Inspired by the creation of new algorithms, increased computing power and the development of deep learning techniques, Artificial Intelligence has developed ever more powerful technical systems, including robots, conversational agents and brain-computer interfaces. At the same time, inspired by those same advances in Machine Learning and AI, the field of Cognitive Science has made leaps and bounds in understanding and modeling human behavior, including human motion, human language, and the human brain.
It is too rare today it that the fields of AI and CogSci join in a dialogue to together develop better methodologies and produce better results, both in understanding human behavior, and in building systems that interact with humans.
Example of potential synergies:
- How can we use AI systems to better understand Human behavior through automatic and reliable measurements?
- Can we take inspiration from Children and construct universal artificial learner of language, physics, morale?
- What are the next steps to solve for Artificial Intelligence systems?


This seminar aims to open that dialogue between the fields of Cognitive Science and Artificial Intelligence. Speakers may come from one field or the other, but all will use this opportunity to reflect on how a pairing between the two fields can be stronger than the sum of the parts. We hope you will join us in building a common language, and a common understanding of the grand societal challenges we face today, and that together we can conquer.


Next seminars
===========================


{% for oneitem in site.data.next %}
<p>
  {{ oneitem.date }}, {{ oneitem.time }}, room {{ oneitem.room }}.<br/>
  <a href="{{ oneitem.url }}">{{ oneitem.speaker }}</a>  ({{ oneitem.affiliation }})<br/>
  <b>Title:</b> <i>{{ oneitem.title }}</i><br/>
  <b>Abstract:</b> {{ oneitem.abstract }}
  </p>
{% endfor %}


Scientific Committee
============================

- [Justine Cassell](http://www.justinecassell.com/)
- [Emmanuel Dupoux](http://www.lscp.net/persons/dupoux/indexfr.html)
- [Jean-Remi King](https://kingjr.github.io/)
- [Srdjan Ostojic](https://lnc2.dec.ens.fr/en/member/655/srdjan-ostojic)
- [Rachid Riad](https://rachine.github.io/)


Supported by
===========================


<p align="center">

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="http://www.ens.fr">
<img height="80" src="img/logo-ens.jpg"/></a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://prairie-institute.fr">
<img height="60" src="img/logo-prairie.png"/></a>



</p>
