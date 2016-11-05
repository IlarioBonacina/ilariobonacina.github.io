---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---
<img align="right" src="images/me.png">

I'm a postdoc in the [Theoretical Computer Science Group](https://www.kth.se/en/csc/forskning/tcs/) at the [School of Computer Science and Communication (CSC)](https://www.kth.se/en/csc) at [KTH Royal Institute of Technology](https://www.kth.se/en) in Stockholm, Sweden. I'm hosted by [Jakob Nordström](http://www.csc.kth.se/~jakobn/).

Previously I was a PhD student at the [Computer Science Department](http://www.di.uniroma1.it/en) at [Sapienza University of Rome](http://en.uniroma1.it) under the supervision of [Nicola Galesi](http://wwwusers.di.uniroma1.it/~galesi/).

I'm interested in Computational Complexity, Mathematical Logic and in particular in Proof Complexity.

***
***
***
***

### Latest News

{% for post in site.posts limit:5 %}
*{{ post.date | date: "%b %-d, %Y" }}*
[{{ post.title | escape }}]({{ post.url | relative_url }})
{% endfor%}

***
***
***
***

### Contact Info
**Email:** [{{ site.work_email }}](mailto:{{ site.work_email }})

**Visiting address:**	{{ site.work_visiting_address }}

**Mailing address**

{{ site.work_address }}
