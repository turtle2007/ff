---
layout: post
title: "Rhythmic Sketch"
date:   2019-04-20
excerpt: "Keywords: Augmented feedback, Multimodal stimuli, Sensorimotor synchronization"
---

## Augmented Visuotactile Feedback Support Sensorimotor Synchronization

<h5>Keywords</h5>
``Augmented feedback, multisensory stimuli, Sensorimotor synchronization``


<h5>Purposes</h5>

- Get people engaged with motor training, particularly the skill of sensorimotor synchronisation.
- Use an unobtrusive way to display feedback without disturbing surrounding people.
- Analyse motion quality with a multi-layered computational framework.

<h5> Study requirements </h5>

1. easy to pick up the practice
2. real-time feedback of motion
3. multisensory feedback

<h5> Practice task </h5>
Sketch rhythmic patterns by hand or arm following a sample rhythm. Experiment setup is shown in the figure below.

<figure>
<img src="{{site.baseurl}}/images/touchRhythms/cut_wall.png" style = "width:400px"/>
</figure>

<h5> Stimuli for the trianing </h5>

The rhythm timing: 
Following figure explains auditory and vibrotactile signal onset

<figure>
<img src="{{site.baseurl}}/images/touchRhythms/AVtiming.png" style = "width:400px"/>
</figure>


Following figure explains visual concomitant of the auditory-vibrotactile rhythm

<figure>
<img src="{{site.baseurl}}/images/touchRhythms/lrlrl.png" style = "width:400px"/>
</figure>

<h5> Evaluation and results </h5>

<!-- Performance with multi-sensory feedback have the correlation all above 0.5, as shown in the figure below, which indicates a good accuracy of sketched rhythm. -->

<!-- <figure>
<img src="{{site.baseurl}}/images/touchRhythms/correlation.png" style = "width:250px"/>
</figure> -->

<!-- Limitation: This evaluation cannot tell the quality of the sketch movements, we need something that can reflect people’s motion features. -->

We follow the multi-layered conceptual framewrok proposed by Camurri et al, 2016, to analysis motion qualities. 

Multi-layered conceptual framewrok:

| LAYERS   |      PARAMETERS     | EXAMPLES  |
|----------|:-------------:|:------:|
| Layer 4 |  Qualities communication |  Emotions, social signals  |
| Layer 3 |  Mid-level features  |  Amodel features like smoothness  |
| Layer 2 |  Low-level features |  Speed, Accelerations  |
| Layer 1 |  Physical signals, virtual sensors |  Time-series data  |
{: .table .table-striped .table-hover}

- Layer 1: We first plot out speed profiles of people's gestural movement during sketches as shown in the below figure.

<figure>
<img src="{{site.baseurl}}/images/touchRhythms/speed.png" style = "width:400px"/>
</figure>


Based on the first layer of computing, we analysied motion features in layer 2 and 3:

- Layer 2: Rhythmic motion precision - measured by dynamic time warping (DTW) distances.

- Layer 3: 

``Sketch motion smoothness`` - measured by the number of velocity peaks.

``Rhythm accuracy`` - measured by calculating the correlations between the sketched rhythm and the sample rhythm. 

{% capture images %}
  {{ site.url }}/images/touchRhythms/kinematics.png
  {{ site.url }}/images/touchRhythms/correlation.png
{% endcapture %}
{% include gallery images=images caption="Motion precision, smoothness and accuracy" cols= 4 %}

<!-- <figure>
<img src="{{site.baseurl}}/images/touchRhythms/kinematics.png" style = "width:350px"/>
<img src="{{site.baseurl}}/images/touchRhythms/correlation.png" style = "width:200px"/>
</figure> -->

(Performance with multi-sensory feedback have the correlation all above 0.5, as shown in the figure above, which indicates a good accuracy of sketched rhythm.)

<h5> Discoveries </h5>

- We learned that VA (Visual-auditory) feedback support the best rhythmic motion precision, but worst motion smoothness, and that VH (Visual-haptic) feedback support the best motion smoothness.

- To support Sensorimotor Synchronization skill recovery, providing VA and VH feedback could improve motion precision and movement smoothness. However, these results need to be verified with real patients in the future.

- Providing vibrotactile feedback is indeed facilitate rhythmic motion performance in an unobtrusive way.

<h5>The remaining question</h5>

Can augmening motion features (DTW distance or the level of motion smoothness ) as the real-time multimodal feedback further support motor skill recovery?

``(For more details of this study, please wait. The paper was submitted to the journal of human-computer studies, and is currently under review.)``

