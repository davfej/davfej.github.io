---
layout: page
title: ""
---

<div style="text-align: center"><img src="https://i.ibb.co/9WrxB5L/smaller.png" alt="smaller" border="0" width=400 height=115></div>
<br />

## Hi
I’m a junior iOS Developer located in Hungary. I have a passion for creating apps with beautiful UI, animations and intuitive, dynamic user experiences.
Since beginning my journey as an iOS Developer, I’ve published a indie app on the [App Store](https://apps.apple.com/us/app/drinkspot-daily-drink-tracker/id1545770917), worked on multiple projects, and collaborated with talented people. 

In 2021, I've landed my first job as an iOS Developer, working at [CodeYard](https://codeyard.eu)



<div class="skill-bar">
    {% for i in (1..5) %}
        {% if i <= include.level %}
            {% include svg-icon.html icon="dot" size="sm" %}
        {% else %}
            {% include svg-icon.html icon="empty-dot" size="sm" %}
        {% endif %}
    {% endfor %}
</div>
