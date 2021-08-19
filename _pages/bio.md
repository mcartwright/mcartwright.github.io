---
layout: single
permalink: /
author_profile: true
redirect_from: 
  - /bio/
  - /bio.html
  - /about/
  - /about.html
  - /home/
  - /home.html
---
My [research](/research) lies at the intersection of human-computer interaction, machine learning, and audio signal processing. Specifically, I research human-centered machine listening and audio processing tools for creative expression with sound and understanding the acoustic world. 

I am currently an Assistant Professor at New Jersey Institute of Technology in the [Department of Informatics](https://informatics.njit.edu/).  I completed my PhD in computer science at Northwestern University as a member of the [Interactive Audio Lab](http://music.eecs.northwestern.edu/), and I hold a Master of Arts from Stanford University ([CCRMA](https://ccrma.stanford.edu/)) and a Bachelor of Music from Northwestern University.  Before my current position, I spent four years as a researcher in the [Music and Audio Research Lab (MARL)](https://steinhardt.nyu.edu/marl/) and the [Center for Urban Science and Progress (CUSP)](http://cusp.nyu.edu/) at New York University (NYU).

News
-------
{% for post in site.posts limit:5  %}
  <a href="{{ post.url | relative_url }}" rel="permalink">{{ post.date | date: "%B %Y"}}</a> - {{ post.blurb }}
{% endfor %}
[&#8250; See all news posts](/categories/#news)


Current Affiliation
-------
* [Department of Informatics](https://informatics.njit.edu/)

Contact
-------
<address>
    New Jersey Institute of Technology<br />
    GITC, Room 3902E<br />
    University Heights,<br /> 
    Newark, New Jersey 07102<br />
</address>