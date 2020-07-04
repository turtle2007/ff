---
layout: post
title:  "Affective BK Robot"
date:   2020-03-01
excerpt: "Keywords: Affective robot, Shape-change skin, Touch"

---


<!-- <iframe src="https://ghbtns.com/github-btn.html?user=TaylanTatli&repo=Halve&type=star&count=true&size=large" frameborder="0" scrolling="0" width="160px" height="30px"></iframe>     -->

## Explore human's emotional states when they interact with a robot who has a shape-changing skin
 
### Research story
In nature, information is conveyed through not only language but a variety of channels such as postures, shapes, ultrasonics, swarm formations (of ants, birds, bees etc.).

Of all the possible information channels, I'm particularly interested in the modality of shape-change. Look at following pics. The shapes convey very clear messages that can be perceived by human and raise certain affective states.

<figure>
<img src="{{site.baseurl}}/images/bk_robot/in_nature.png" style = "width:350px"/>
</figure>

(The hedgehocs' pic are adoppted from [here](http://blog.critterconnection.cc/spine-language/)

Nowadays we have algorithms, intelligent agents or robots that are able to touch human's emotions by reading human's facial expressions, physiological signals, body language etc. However, there are limited communication channels for the robots to convey their richness underlying states. This problem has two folds. On the one hand, humans become increasingly transparent to the robots, while robots are increasingly opaque to humans (especially to non-expert users), which leads to information inequality. On the other hand, inadequate expressive channels limit interaction space between human and robots, and diminish good user experience (UX) in human-robot/computer interaction (as shown in figure below).


<!-- {% capture images %}
  {{ site.url }}/images/bk_robot/HRI_info_trans.png
{% endcapture %}
{% include gallery images=images caption="Human-robot/computer information channels" cols=3 %} -->

<figure>
<img src="{{site.baseurl}}/images/bk_robot/HRI_info_trans.png" style = "width:350px"/>
</figure>

### The question
What if a robot has a skin which conveys information through shape-change mechanism? How would human understand the robot's messages by perceiving the change of the skin? 

This project aims to understand how human understand robot's affective states which are expressed through shape-change on its skin.

As a first step, we control the shape-change of the robot skin by three parameters: change of the `size`, `speed` and the `frequency` of the change.

