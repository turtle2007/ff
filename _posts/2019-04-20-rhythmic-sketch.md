---
layout: post
title: "Rhythmic sketch"
date:   2019-04-20
excerpt: "Keywords: Augmented feedback, Multimodal stimuli, Sensorimotor synchronization"
---

## Augmented Visuotactile Feedback Support Sensorimotor Synchronization Skill for Rehabilitation

<h5>Keywords</h5>
``Augmented feedback, multimodal stimuli, Sensorimotor synchronization``


<h5>Purposes</h5>

- Help minor stroke patients to recover lost motor function, particularly the sensorimotor synchronisation.
- Use an unobtrusive way to present feedback to the patient without disturbing surrounding people.
- Combine usability evaluation with the kinematic evaluation methods.

<figure>
<img src="{{site.baseurl}}/images/touchRhythms/cut_wall.png" width = "400"/>
</figure>

<h5> Study requirements </h5>

1. easy to pick up the practice
2. real-time feedback of motion
3. multimodal feedback

<h5> Practice task </h5>
Make rhythmic sketches following a rhythm

<h5> Stimuli for the trianing </h5>

- The rhythm timing: 
Auditory and vibrotactile signal onset

<figure>
<img src="{{site.baseurl}}/images/touchRhythms/AVtiming.png" width = "400"/>
</figure>


- Visual concomitant of the rhythm
Five-beats rhythm

<figure>
<img src="{{site.baseurl}}/images/touchRhythms/lrlrl.png" width = "400"/>
</figure>

<h5> Evaluation and results </h5>
- Usability evaluation
Performance with multimodal feedback have the correlation all above 0.5, as shown in the figure below, which indicates a good accuracy of sketched rhythm.

<figure>
<img src="{{site.baseurl}}/images/touchRhythms/correlation.png" width = "300"/>
</figure>

Limitation: This evaluation cannot tell the quality of the sketch movements, we need something that can reflect people’s motion features.


- Kinematic analysis of gestures (sketches)

We first plot out speed profiles of people's gestural movement during sketches as shown in the below figure.

<figure>
<img src="{{site.baseurl}}/images/touchRhythms/speed.png" width = "500"/>
</figure>


Based on these profiles, we analysied two motion features:
  1. Rhythmic motion precision - measured by dynamic time warping (DTW) distances.
  2. Sketch motion smoothness - measured by the number of velocity peaks. 

<figure>
<img src="{{site.baseurl}}/images/touchRhythms/kinematics.png" width = "400"/>
</figure>

<h5> Learning </h5>

We learned that VA (Visual-auditory) feedback support the best rhythmic motion precision, but worst motion smoothness, and that VH (Visual-haptic) feedback support the best motion smoothness.

To support Sensorimotor Synchronization skill recovery, providing VA and VH feedback could improve motion precision and movement smoothness. However, these results need to be verified with real patients in the future.

Providing vibrotactile feedback is indeed facilitate rhythmic motion performance in an unobtrusive way.

The remaining question is: 

Can augmening motion features (DTW distance or the level of motion smoothness ) as the real-time multimodal feedback further support motor skill recovery?

``(For more details of this study, please wait. The paper was submitted to the journal of human-computer studies, and is currently under review.)``

---

Highlighting does not affect the meaning of the text itself; it is intended only for human readers.[^1]

[^1]: <http://en.wikipedia.org/wiki/Syntax_highlighting>

### GFM Code Blocks

GitHub Flavored Markdown [fenced code blocks](https://help.github.com/articles/creating-and-highlighting-code-blocks/) are supported. To modify styling and highlight colors edit `/_sass/syntax.scss`.

```css
#container {
  float: left;
  margin: 0 -240px 0 0;
  width: 100%;
}
```

```html
{% raw %}<nav class="pagination" role="navigation">
  {% if page.previous %}
    <a href="{{ site.url }}{{ page.previous.url }}" class="btn" title="{{ page.previous.title }}">Previous article</a>
  {% endif %}
  {% if page.next %}
    <a href="{{ site.url }}{{ page.next.url }}" class="btn" title="{{ page.next.title }}">Next article</a>
  {% endif %}
</nav><!-- /.pagination -->{% endraw %}
```

```ruby
module Jekyll
  class TagIndex < Page
    def initialize(site, base, dir, tag)
      @site = site
      @base = base
      @dir = dir
      @name = 'index.html'
      self.process(@name)
      self.read_yaml(File.join(base, '_layouts'), 'tag_index.html')
      self.data['tag'] = tag
      tag_title_prefix = site.config['tag_title_prefix'] || 'Tagged: '
      tag_title_suffix = site.config['tag_title_suffix'] || '&#8211;'
      self.data['title'] = "#{tag_title_prefix}#{tag}"
      self.data['description'] = "An archive of posts tagged #{tag}."
    end
  end
end
```

### Code Blocks in Lists

Indentation matters. Be sure the indent of the code block aligns with the first non-space character after the list item marker (e.g., `1.`). Usually this will mean indenting 3 spaces instead of 4.

1. Do step 1.
2. Now do this:
   
   ```ruby
   def print_hi(name)
     puts "Hi, #{name}"
   end
   print_hi('Tom')
   #=> prints 'Hi, Tom' to STDOUT.
   ```
        
3. Now you can do this.

### GitHub Gist Embed

An example of a Gist embed below.

{% gist e813c2560b0f1ecc9f5d pacman.patch %}
