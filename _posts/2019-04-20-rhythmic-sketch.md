---
layout: post
title: "Rhythmic Sketch"
date:   2019-04-20
excerpt: "Keywords: Augmented feedback, Multimodal stimuli, Sensorimotor synchronization"
---

## Augmented Visuotactile Feedback Support Sensorimotor Synchronization Skill

<h5>Keywords</h5>
``Augmented feedback, multisensory stimuli, Sensorimotor synchronization``


<h5>Purposes</h5>

- Get people engaged with motor training, particularly the skill of sensorimotor synchronisation.
- Use an unobtrusive way to display feedback without disturbing surrounding people.
 - Analyse motion quality with a multi-layered computational framework.

<figure>
<img src="{{site.baseurl}}/images/touchRhythms/cut_wall.png" width = "70%"/>
</figure>

<h5> Study requirements </h5>

1. easy to pick up the practice
2. real-time feedback of motion
3. multisensory feedback

<h5> Practice task </h5>
Sketch rhythmic patterns by hand or arm following a sample rhythm.

<h5> Stimuli for the trianing </h5>

- The rhythm timing: 
Auditory and vibrotactile signal onset

<figure>
<img src="{{site.baseurl}}/images/touchRhythms/AVtiming.png" width = "200"/>
</figure>


- Visual concomitant of the rhythm
Five-beats rhythm

<figure>
<img src="{{site.baseurl}}/images/touchRhythms/lrlrl.png" width = "200"/>
</figure>

<h5> Evaluation and results </h5>
- Usability evaluation
Performance with multimodal feedback have the correlation all above 0.5, as shown in the figure below, which indicates a good accuracy of sketched rhythm.

<figure>
<img src="{{site.baseurl}}/images/touchRhythms/correlation.png" width = "200"/>
</figure>

Limitation: This evaluation cannot tell the quality of the sketch movements, we need something that can reflect people’s motion features.


- Kinematic analysis of gestures (sketches)

We first plot out speed profiles of people's gestural movement during sketches as shown in the below figure.

<figure>
<img src="{{site.baseurl}}/images/touchRhythms/speed.png" width = "200"/>
</figure>


Based on these profiles, we analysied two motion features:
  1. Rhythmic motion precision - measured by dynamic time warping (DTW) distances.
  2. Sketch motion smoothness - measured by the number of velocity peaks. 

<figure>
<img src="{{site.baseurl}}/images/touchRhythms/kinematics.png" width = "200"/>
</figure>

<h5> Learning </h5>

We learned that VA (Visual-auditory) feedback support the best rhythmic motion precision, but worst motion smoothness, and that VH (Visual-haptic) feedback support the best motion smoothness.

To support Sensorimotor Synchronization skill recovery, providing VA and VH feedback could improve motion precision and movement smoothness. However, these results need to be verified with real patients in the future.

Providing vibrotactile feedback is indeed facilitate rhythmic motion performance in an unobtrusive way.

<h5>The remaining question</h5>

Can augmening motion features (DTW distance or the level of motion smoothness ) as the real-time multimodal feedback further support motor skill recovery?

``(For more details of this study, please wait. The paper was submitted to the journal of human-computer studies, and is currently under review.)``

