---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# About me

Hi! My name is Mohammed Sabri. I am a Ph.D. Candidate in [the Department of Mathematics and Physics](https://www.matfis.unicampania.it/) at [University of Campania “Luigi Vanvitelli”](https://international.unicampania.it/index.php/en/) under supervision of Prof. [Rosanna Verde](https://www.researchgate.net/profile/Rosanna_Verde).

Before joining my Phd, I received my Master's Degree in [Data Science and Machine Learning](https://lipn.univ-paris13.fr/~bennani/Web_Master_Info/Master_Info_EID2_Anglais.html) from galilee institut at [Sorbonne Paris Nord University](https://galilee.univ-paris13.fr/). And a Master's Degree in Applied Mathematics and Data Science from [Faculty of Sciences Dhar El Mehraz](http://www.fsdmfes.ac.ma/) at [Sidi Mohamed Ben Abdellah University](http://www.usmba.ac.ma/~usmba2/). The program of these Master's joins courses with a Computer Science main theme, those with a Statistical data analysis, Data Science, Machine Learning, Advanced Databases, Data Mining, Business Analytics, and Data Warehousing main theme, and those with cultural courses. The electives courses may be chosen, in consultation with the student's advisor, to meet the interdisciplinary  and the speciality distribution requirements. My fourth semester is devoted to an internship about Developpement of Intelligence Artifieciel interested in segmentation of clients under supervision of Prof. [Hamid Tairi](https://scholar.google.fr/citations?user=eBF5ZcwAAAAJ&hl=fr). Since then I was greatly attracted by the beauty of statistics in real life and collaboration with Machine Learning.

My PhD thesis topic is New Methods in Functional Data Analysis.


I'm always excited to collaborate on new projects and discuss ideas in data science and machine learning. Feel free to reach out if you'd like to connect!


# Publications

{% raw %}
{% if site.author.googlescholar %}
  You can also find my articles on <u><a href="{{ site.author.googlescholar }}">my Google Scholar profile</a>.</u>
{% endif %}

{% for pub in site.publications reversed %}
  <div class="publication">
    <h3>{{ pub.title }}</h3>
    <p>{{ pub.authors }}</p>
    <p><em>{{ pub.venue }}</em>, {{ pub.date | default: "1900-01-01" | date: "%Y" }}</p>
    {% if pub.paperurl %}
      <p>Download <a href="{{ pub.paperurl }}"><u>here</u></a></p>
    {% endif %}
  </div>
{% endfor %}
{% endraw %}
