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

## Research background

In the field of human-automation interaction, the question of how to improve operational efficiency and safety, especially in the time-sensitive and/or safety-critical settings, has always been in the central discussion.

Many system designs, such as monitoring system in factories, power plants, and/or semi-automated driving, requires careful consideration on the display of multi-sensory information. 

One strategy of improving the system's usability is to present multisensory information in a way that is consistent with everyday perceptual regularities. One of the multisensory regularities is called `Crossmodal Correspondences (CCs)`.

- `Crossmodal Correspondence`: Perceptual association between sensory modalities. For example, high pitch (auditory perception) is associated with a high position (visual perception). This regularity is pervasively applied in various situations, such as music player tuning, data sonification, water level monitoring, facilitating motor skill learning etc.

- Interestingly, many artists have advanced sensory acuity which enables them to capture CCs and reflect in their artworks (either intentionally or subconsciously). See how many CCs can you pick out from Kandinsky's visual composition:

<figure>
	<img src="{{site.baseurl}}/images/paradox/K_tension.jpg" width = "700"/>
	<figcaption>Wassily Kandinsky, Delicate tension, NO. 85, 1923, Watercolor and ink on paper.</figcaption>
</figure>

and from Zhu Da's spiritual reflection:

<figure>
	<img src="{{site.baseurl}}/images/paradox/bdsr.jpg" width = "700"/>
	<figcaption>Zhu Da, Hua Niao Series, 1626-1705, Calligraphy and ink on paper.</figcaption>
</figure>

## Question

The phenomenom of CCs has been extensively investigated in the field of cognitive study. With a well-controlled experimental paradigm (conventionally the speeded classificiation paradigm), We discovered more and more associations not only between visual and auditory modality, but also between visual and haptic, as well as autitory and haptic modality. 

However, CC implementations with an effort from Human-computer interaction (HCI) have certain limi- tations due to the following reasons:

* the real-world situation is not as clean as the well-controlled experimental environment. Streams of interactive information unavoidably mingle with physical and attentional background noise, which may act as visual, auditory or multisensory distractors.

* many cases of crossmodal interaction, such as spatial localisation, graph sonification, and motor skill learning, involve consistent sensory-motor responses with continuous, and graded crossmodal feedback. We lack empirical knowledge on how such crossmodal stimuli influence interaction that requires consistent sensory-motor engagement.

* Complex sensorial noise usually occures intermettently over the course of interactive tasks. Under such a circumstance, mutrally exclusive CCs may happen. To our knowledge, we don't know how people react to such a situation, not to mention a set of design guidlines to overcome or circumvent perceptual pitfalls.

In this project, we are `aiming` to tackle following two questions:

* RQ1: Whether people's crossmodal perception can be enhanced by cognitive priming, and if it can be, to what extent it modulates small and fast sensory-motor responses in an interactive task?

* RQ2: How do people integrate crossmodal information in which two CCs are mutually exclusive? Furthermore, how, if at all,  does the integration of such information change in the presence or absence of cognitive priming? 

 
## Method, results and implications for design

The published results of this project can be found [here](https://scholar.google.com/citations?authuser=1\&user=IHMO\_z0AAAAJ):

Title: Exploring crossmodal perceptual enhancement and integration in a sequence reproducing task with cognitive priming

DOI: 10.1007/s12193-020-00326-y


<!-- #### Three Up

And you'll get something that looks like this:

<figure class="third">
	<img src="http://placehold.it/600x300.jpg">
	<img src="http://placehold.it/600x300.jpg">
	<img src="http://placehold.it/600x300.jpg">
	<figcaption>Three images.</figcaption>
</figure> -->