---
layout: default
permalink: /research/
title: research
categories: [Learning Differences, Instruction & Curriculum, Assessment & Measurement]
description:  
nav: true
nav_order: 1
dropdown: true
children:
    - title: "Overview"
      permalink: /research/
    - title: "Thread 1: Learning Differences"
      permalink: /research/learning-difference
    - title: "Thread 2: Instruction & Curriculum"
      permalink: /research/instruction-curriculum
    - title: "Thread 3: Assessment & Measurement"
      permalink: /research/assessment-measurement
    - title: All Publications
      permalink: /publications/
---

<center>    
    <h4> My research aims to develop and unify techniques from both prominent educational theories and statistical methods and AI-driven models to explore the complexities of language, ultimately enhancing students' learning experiences. This involves gaining a nuanced understanding of the structure of written expression, investigating individual learning differences in literacy-related skills, and examining how classroom practices and assessments shape the overall learning atmosphere.
    <!-- <b>Bipedal Locomotion</b>, <b>Human Robot Interaction</b>, and <b>Lower-Body Assistive Devices</b>. -->
    </h4>
</center>


<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="images/papers/LD.jpg" class="img-fluid rounded z-depth-1" overlay="Learning Differences"
            overlay-url="/research/learning-difference" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="images/papers/curri.jpg" class="img-fluid rounded z-depth-1" overlay="Instruction and Curriculum"
        overlay-url="/research/instruction-curriculum" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="images/papers/AI.png" class="img-fluid rounded z-depth-1" overlay="Assessment and Measurement"
        overlay-url="/research/assessment-measurement" %}
    </div>
</div>

<!-- _pages/publications.md -->
<div class="publications">
{%- for c in page.categories %}

  <h2 class="year">{{c}}</h2>

  {% bibliography -f papers -q @*[category={{c}}]* %}

{% endfor %}


</div>
