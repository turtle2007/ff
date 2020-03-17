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

- `Crossmodal Correspondence`: Perceptual association between sensory modalities. For example, high pitch (audition) is associated with high position (vision). This regularity is pervasively applied in various situations, from music player tuning to data sonification and to water level monitoring.

## Question

The phenomenom of CCs has been extensively investigated in the field of cognitive study. With a well-controlled experimental paradigm (conventionally the speeded classificiation paradigm), We discovered more and more associations not only between visual and auditory modality, but also between visual and haptic, as well as autitory and haptic modality. 

However, the real-world situation is not as clean as the well-controlled experimental environment. Complex sensorial noise usually accompanies user(s) intermettently over the course of interactive tasks. Under such a circumstance, conflict crossmodal correspondences may happen. To our knowledge, we don't know how people react to such a situation, not to mention a set of design guidlines to overcome or circumvent perceptual pitfalls.

## Aims

- Investigate human's perceptual regularities in a less ideal situation, specifically, under the condition where has many CCs, as well as the condition when CCs are mutually exclusive.

- Propose design recommendations for multi-sensory systems.
 
## Method

We created webapp games which display two CCs at the same time: `Pitch-brightness` and `Pitch-elevition` correspondences. 

<figure>
	<img src="{{site.baseurl}}/images/paradox/Fig1.eps" width = "400"/>
</figure>

In the [easy] level, the two CCs are isolated and not affecting each other:

[easy]: https://github.com/turtle2007/Study2

In a harder level, the two CCs are co-existed and mutually exclusive. (Code waiting to be uploaded)



#### Two Up

Apply the `half` class like so to display two images side by side that share the same caption.

```html
<figure class="half">
    <a href="/images/image-filename-1-large.jpg"><img src="/images/image-filename-1.jpg"></a>
    <a href="/images/image-filename-2-large.jpg"><img src="/images/image-filename-2.jpg"></a>
    <figcaption>Caption describing these two images.</figcaption>
</figure>
```

And you'll get something that looks like this:

<figure class="half">
	<a href="http://placehold.it/1200x600.JPG"><img src="http://placehold.it/600x300.jpg"></a>
	<a href="http://placehold.it/1200x600.jpeg"><img src="http://placehold.it/600x300.jpg"></a>
	<figcaption>Two images.</figcaption>
</figure>

#### Three Up

Apply the `third` class like so to display three images side by side that share the same caption.

```html
<figure class="third">
	<img src="/images/image-filename-1.jpg">
	<img src="/images/image-filename-2.jpg">
	<img src="/images/image-filename-3.jpg">
	<figcaption>Caption describing these three images.</figcaption>
</figure>
```

And you'll get something that looks like this:

<figure class="third">
	<img src="http://placehold.it/600x300.jpg">
	<img src="http://placehold.it/600x300.jpg">
	<img src="http://placehold.it/600x300.jpg">
	<figcaption>Three images.</figcaption>
</figure>