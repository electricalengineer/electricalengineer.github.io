---
layout: page
permalink: /about/index.html
title: Hossain Mohd Faysal
tags: [Hossain, Mohd, Faysal, hmfaysal]
imagefeature: Hossain-Mohd-Faysal.jpg
chart: true
---
<figure>
  <img src="{{ site.url }}/images/hossain-faysal.jpg" alt="Hossain Mohammad Faysal">
  <figcaption>Hossain Mohammad Faysal</figcaption>
</figure>

My name is **Hossain Mohd. Faysal**, and this is my personal blog. This blog currently has {{ site.posts | size }} posts in {{ site.categories | size }} categories. 

<div id="myfirstchart" style="height: 250px;"></div>
<figcaption>Number of Posts Breakdown</figcaption>


I am an PhD candidate in *ESE* at the [SEAS](http://www.seas.upenn.edu/) at **UPENN**. I am licensed as a Professional Engineer (P.E) to practice in the states of Texas, Massachusetts and California. I double majored in EECS and Mathematics during my undergraduate life at [MIT](http://www.mit.edu/), and currently focusing on Electrical Engineering for my post-graduate studies.

*[ESE]: Electrical and Systems Engineering
*[SEAS]: School of Engineering and Applied Science
*[MIT]: Massachusetts Institute of Technology
*[EECS]: Electrical and Computer Engineering
*[UPENN]: University of Pennsylvania

![Hossain Mohammad Faysal]({{ site.url }}/images/Hossain-Mohd-Faysal.jpg "At Bates Linear Accelerator Center")
<figcaption>At <a href="http://web.mit.edu/lns/research/bates.html">Bates Linear Accelerator Center</a></figcaption>

I was born and brought up in Doha. Yes, its a desert peninsula, yes we have camels and falcons and all the other Middle Eastern traits/stereotypes you can think of.

At some point in the not-terribly-distant future, I hope to found a self-sustaining collective of clever people, for fun, profit(?), and the promotion of human life in the universe. This might wind up in Qatar, Bangladesh, Scandinavia, the Massachusetts Bay Area, the SF Bay Area, Japan, Germany, or the dustbin of overly idealistic plans. (Yes, I have a special bin for overly idealistic plans. In my district they can't be recycled with residential mixed paper.) The most challenging aspect of this concept is to curtail unproductive competition with other people who will inevitably have the same idea. (Some sort of cooperative federation...) I'm presently looking for people who might be interested in being a part of such an organization.

Anyways, for now I'm just working toward changing the face of Electrical Engineering forever. Not that I necessarily expect to succeed, but it's something to strive for, and it's a fun problem to work on.


Entrepreneur  
Designer  
***Engineer***  
Inventor  

I
make
stuff.


*Beautiful, practical, meaningful stuff.*


I make what I love.

*I love what I do.*


But over the years, I noticed that somehow, along the way, software designed to help us be creative, actually made us less creative. That's because we believe our best ideas emerge when we use pencils and paper.
So I set out to build tools that work the way I do.


Tools for the creative space — the 53 centimeters that magically link head, heart, and hand. Tools as simple as pencil and paper. Tools so essential, I  really can't imagine work without them.


For
the makers,  
the creators,  
the discoverers,  
the original thinkers,  
***This is the space to create.***

<script type="text/javascript">
Morris.Donut({
  element: 'myfirstchart',
  data: [
{% assign tags_list = site.categories %}  
  {% if tags_list.first[0] == null %}
    {% for tag in tags_list %} 
    {label: "{{ tag | capitalize }}", value: {{ site.tags[tag].size }}},
    {% endfor %}
  {% else %}
    {% for tag in tags_list %} 
    {label: "{{ tag[0] | capitalize }}", value: {{ tag[1].size }}},
    {% endfor %}
  {% endif %}
{% assign tags_list = nil %}
  ],
  colors: [
    '#8A9B0F',
    '#F8CA00',
    '#E97F02',
    '#BD1550',
    '#490A3D'
  ],
  resize: true
});
</script>