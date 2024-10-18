---
title: "ASU RISE Lab - Research"
layout: textlay
excerpt: "ASU RISE Lab -- Research"
sitemap: false
permalink: /research/hri
---

<script>
function openCity(evt, cityName) {
  // Declare all variables
  var i, tabcontent, tablinks;

  // Get all elements with class="tabcontent" and hide them
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }

  // Get all elements with class="tablinks" and remove the class "active"
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }

  // Show the current tab, and add an "active" class to the button that opened the tab
  document.getElementById(cityName).style.display = "block";
  evt.currentTarget.className += " active";
}


</script>


## Template Robotics
Robots are increasingly employed in close proximity to humans. For the humans and robots to collaborate safely and efficiently, a robot needs to understand human intents, predict human actions, consider human factors, in order to optimize its own actions to complete a task with human safely, efficiently, and friendly. Here we will explore a game-theoretic framework to model the bilateral inference and decision making process between the human and robot. We are interested in both proximal and physical tasks that involve joint decision-making and joint-action between the human and robot. One major challenge is to model the human actions in highly dynamic tasks given the strong variability and uncertainty of humans. We will apply the developed algorithms in various human-robot collaboration scenarios, including autonomous vehicles, collaborative manufacturing, wearable robots, and assistive devices. For more details about how we apply the developed algorithms to autonomous vehicles, please check this page.

<table style="width:100%">
<tr>
<td style="width:70%">

<!-- Tab links -->
<div class="tab">
  <button class="tablinks" onclick="openCity(event, 'Publications')" id="defaultOpen">Publications</button>
  <button class="tablinks" onclick="openCity(event, 'Projects')">Projects</button>
  <button class="tablinks" onclick="openCity(event, 'Outreach')">Outreach</button>
</div>

<!-- Tab content -->
<div id="Publications" class="tabcontent" style="height:500px;">
  <h3>Publications</h3>
<table>
  <tr>
    <td><p><a href="https://ieeexplore.ieee.org/abstract/document/10065388">Learning Post-Stroke Gait Training Strategies by Modeling Patient-Therapist Interaction</a></p></td>
    <td><img src="/images/respic/hri/hri1.png" width="200px"></td>
  </tr>
  <tr>
    <td><a href="https://ieeexplore.ieee.org/abstract/document/9982108">Bounded Rational Game-theoretical Modeling of Human Joint Actions with Incomplete Information</a></td>
    <td><img src="/images/respic/hri/hri2.png" width="200px"></td>
  </tr>
  <tr>
    <td><a href="[https://ieeexplore.ieee.org/abstract/document/9982108](https://ieeexplore.ieee.org/abstract/document/9867155)">When Shall I Estimate Your Intent? Costs and Benefits of Intent Inference in Multi-Agent Interactions</a></td>
    <td>Francisco Chang</td>
  </tr>
</table>
<!--
  <p><a href="https://ieeexplore.ieee.org/abstract/document/10065388">Learning Post-Stroke Gait Training Strategies by Modeling Patient-Therapist Interaction</a></p> <img src="/images/respic/hri/hri1.png" width="200px">
  <p><a href="https://ieeexplore.ieee.org/abstract/document/9982108">Bounded Rational Game-theoretical Modeling of Human Joint Actions with Incomplete Information</a></p> <img src="/images/respic/hri/hri2.png" width="200px">
  <p><a href="[https://ieeexplore.ieee.org/abstract/document/9982108](https://ieeexplore.ieee.org/abstract/document/9867155)">When Shall I Estimate Your Intent? Costs and Benefits of Intent Inference in Multi-Agent Interactions</a></p>
  -->
	
</div>

<div id="Projects" class="tabcontent" markdown="1" style="height:500px;overflow:scroll">
  <h3>Projects</h3>
  <h4>Prospect-Theoretic Reinforcement Learning in Overcooked</h4>
  - Goal
    - Make AI better understand human preferences and decisions to make AI better able to assist
  - Project Description
    - Integrate risk-aware cognitive models (CPT) into interactive AI planning in an Overcooked environment
  - Looking for:
    - Set up Overcooked RL environment
    - Modify overcooked to induce risk
    - Train standard baseline policies
    - Train discrete prospect-theoretic models
    - Estimate latent human parameters online

 
  <h4>Game Theoretical Modeling of Physical Human-Robot Interactions </h4>
  - Goal
    - Developing a game theoretical-based controller for physical human-robot interaction scenarios such as controlling assistive wearable robots 

  - Project Description
    - Integrate risk-aware cognitive models (CPT) into interactive AI planning in an Overcooked environment
  - Looking for:
    - Developing a framework for solving incomplete information Multi-agent interactions.
    - Apply the developed framework to actual HRI scenarios and model the human learning process.
    - Applying the results on the control of assistive wearable robots to have a more compliant and robust controller
</div>

<div id="Outreach" class="tabcontent" style="height:500px;">
  <h3>Outreach</h3>
  <p>Tokyo is the capital of Japan.</p>
</div>

<script>
document.getElementById("defaultOpen").click();
</script>

</td>
<td style="width:30%;padding-left:1em" markdown="1">
#### Team Members
- <a href="{{ site.url }}{{ site.baseurl }}/team">Sunny Amatya</a>

- <a href="{{ site.url }}{{ site.baseurl }}/team">Jonathan Bush</a>

- <a href="{{ site.url }}{{ site.baseurl }}/team">Mason Smith</a>

- <a href="{{ site.url }}{{ site.baseurl }}/team">Yousef Soltanian</a>

</td>
</tr>
</table>
### Collaborators
 - ABRC
 - BNI
 - UIUC
 - Virginia Tech
 - SRP
<hr>
