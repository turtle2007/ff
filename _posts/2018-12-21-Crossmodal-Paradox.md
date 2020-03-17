---
layout: post
title: "Crossmodal Paradox"
date:   2018-12-21
excerpt: "Paradoxical perception between sensory modalities."
image: "https://storage.googleapis.com/hoopla/production/image/37828/Kandinsky_Comp_VIII.jpg"
<!-- tags: 
  - sample post
  - images
  - test -->
---

## Motivation

An interactive system which supports multisensory communication channels shows advantages in improving people's response time and accuracy. With proper design, it could also reduce cognitive load under heavy task, such as cockpit operation or decision making in command chamber.

To improve the system's usability, information should be presented in a way that is consistent with perceptual regularities. One way of doing that is to follow `Crossmodal Correspondences (CCs)`.

- `Crossmodal Correspondence`: Perceptual association between sensory modalities. For example, high pitch (audition) is associated with high position (vision). This regularity is pervasively applied in various situations, such as music player tuning, data sonification, water level monitoring, facilitating motor skill learning etc.

- Interestingly, many artists have advanced sensory acuity which enable them to capture CCs and reflect in their art works (either intentionally or subconsciously). See how many CCs can you pick out from Kandinsky's visual composition:

<!-- <figure>
	<img src="https://www.museothyssen.org/en/collection/artists/kandinsky-wassily/delicate-tension-no-85">
	<figcaption>Wassily Kandinsky, Delicate tension, NO. 85, 1923, Watercolor and ink on paper..</figcaption>
</figure> -->

<figure>
	<img src="{{site.baseurl}}/images/paradox/K_tension" width = "700"/>
</figure>

## Question

The phenomenom of CCs has been extensively investigated in the field of cognitive study. With a well-controlled experimental paradigm (conventionally the speeded classificiation paradigm), We discovered more and more associations not only between visual and auditory modality, but also between visual and haptic, as well as autitory and haptic modality. 

However, the real-world situation is not as clean as the well-controlled experimental environment. Complex sensorial noise usually accompanies user(s) intermettently over the course of interactive tasks. Under such a circumstance, conflict crossmodal correspondences may happen. To our knowledge, we don't know how people react to such a situation, not to mention a set of design guidlines to overcome or circumvent perceptual pitfalls.

## Aims

- Investigate human's perceptual regularities in a less ideal situation, specifically, under the condition where has many CCs, as well as the condition when CCs are mutually exclusive.

- Propose design recommendations for multi-sensory systems.
 
## Method

We created webapp games which display two CCs at the same time: `Pitch-brightness` and `Pitch-elevition` correspondences. We use cognitive priming technique to prime people the intended CC that will help their task.

The task is to listen and watch a crossmodal sequence, either following `Pitch-brightness` or `Pitch-elevition` correspondence. Then reproduce the sequence as quickly and accurately as possible.

The visual and auditory stimuli are controlled as shown in the figure below:

<figure>
	<img src="{{site.baseurl}}/images/paradox/Fig1.eps" width = "700"/>
</figure>

#### Experiment 1

In the [easy] level, the two CCs are isolated and not affecting each other.

[easy]: https://github.com/turtle2007/Study2

#### Experiment 2

In a harder level, the two CCs are co-existed and mutually exclusive. (Code waiting to be uploaded)

### Data collection

- time intervals between each input (mouse click)

- error rate of repeating the crossmodal sequences

- subjective interpretation of priming materials

- perceptual alinement about CCs


## Results

#### Three Up

And you'll get something that looks like this:

<figure class="third">
	<img src="http://placehold.it/600x300.jpg">
	<img src="http://placehold.it/600x300.jpg">
	<img src="http://placehold.it/600x300.jpg">
	<figcaption>Three images.</figcaption>
</figure>