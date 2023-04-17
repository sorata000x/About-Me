---
layout: page
title: Projects
permalink: /projects/
---


<!--- Achievement -->

{% for repo in site.github.public_repositories %}

{% if repo.name == 'Achievement' %}

### [Achievement]({{ repo.html_url }})

{{ repo.description }}

<image src="../image/project/achievement_demo.gif" width=500/> <br>

Topics: {{ repo.topics | array_to_sentence_string }}

Last updated: {{ repo.updated_at | date_to_string }}

{% endif %}


<!--- Experience Bar -->

{% if repo.name == 'Experience-Bar' %}

### [Experience Bar]({{ repo.html_url }})

{{ repo.description }}

<image src="../image/project/expbar_demo.gif" width=500/> <br>

Topics: {{ repo.topics | array_to_sentence_string }}

Last updated: {{ repo.updated_at | date_to_string }}

{% endif %}


<!--- Relational Database C++ -->

{% if repo.name == 'Database-C-' %}

### [ Relational Database C++ ]({{ repo.html_url }})

{{ repo.description }}

Topics: {{ repo.topics | array_to_sentence_string }}

Last updated: {{ repo.updated_at | date_to_string }}

{% endif %}


<!--- Battleship Game Python -->

{% if repo.name == 'Battleship-Game-Python' %}

### [Battleship Game Python]({{ repo.html_url }})

{{ repo.description }}

<image src="../image/project/battleship_demo.gif" width=500/> <br>

Topics: {{ repo.topics | array_to_sentence_string }}

Last updated: {{ repo.updated_at | date_to_string }}

{% endif %}


<!--- Chess Game Java -->

{% if repo.name == 'GUI-Chess-Game-Java' %}

### [Chess Game Java]({{ repo.html_url }})

{{ repo.description }}

<image src="../image/project/chess_demo.gif" width=500/> <br>

Topics: {{ repo.topics | array_to_sentence_string }}

Last updated: {{ repo.updated_at | date_to_string }}

{% endif %}


{% endfor %}
