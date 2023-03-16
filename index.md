---
title: Home
---

{% include link.html type="email" icon="" text="Feel free to reach out!" tooltip="" link="petras.swissler@njit.edu" style="button"%}
{:.center}
  
# Making cool robots to solve real-world problems

This is an academic lab based at NJIT that focusses on developing real, novel robotic systems.
Key to developing these robots is the question of "so what." Why develop robots that are able to build bridges out of their own bodies? Why look at ways that robots can adapt their configuration based on unexpected environments? 
What it always comes back to is the fact that we want to apply these robots in real life: we want these robots to be useful.
Like much of academic research, the work we do often reaches beyond what current technology makes practical so that when other technologies catch up we will have a blueprint ready to address these real-world issues.

If this sounds interesting to you and you'd like to work in this lab, email petras.swissler@njit.edu or click the button above. The New Jersey Institute of Technology is an R1 public research university that's located in about 30 minutes by train from Manhattan and provides ample opportunities for students to apply themselves and explore robotics.

{%
  include link.html
  type="github"
  icon=""
  text="See our lab's GitHub"
  link="innovative-robotics/"
  style="button"
%}
{%
  include link.html
  type="docs"
  icon=""
  text="Learn about NJIT"
  link="https://mie.njit.edu/"
  style="button"
%}
{:.center}

{% include section.html full=true %}

{% include section.html %}

# Examples of what we work on

<iframe width="560" height="315" src="https://www.youtube.com/embed/GKR5wpANZkU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/Ln4GuFyTY0k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# Highlights

{% capture text %}
A big focus of our lab's work is the full-stack development of robotic systems. This includes everything from conceptualizing new robot mechanisms, to the building and design of robotic systems, to the development of algorithms that these new robots can use.

{%
  include link.html
  link="research"
  text="See what we've published"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/wrench.png"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}
The lab has access to state-of-the-art manufacturing equipment thanks to the expansive NJIT maker space. We are also in the process of building up our own lab space, which we expect to have up and running by summer 2023.

{%
  include link.html
  link="tools"
  text="Our Lab Space"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/tools.png"
  link="resources"
  title="Our Resources"
  flip=true
  text=text
%}

{% capture text %}

This is a brand-new lab, so we are actively looking to grow the team!

{%
  include link.html
  link="team"
  text="Meet our team"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/team.png"
  link="team"
  title="Our Team"
  text=text
%}
