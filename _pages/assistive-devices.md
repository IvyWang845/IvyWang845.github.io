---
layout: page
permalink: /research/assistive-devices
title: Assessment and Measurement
header:
    image: images/papers/spinal.png
description: Research thread aims to propose, design, and validate assessment framework as a pivotal driver for the entire learning system.
nav: false
---

Open-ended questions (constructed-response assessments in science education) and students' written expressions across various genres and registers offer insights into original thoughts to specific topics and the application of disciplinary knowledge. Unlike other assessment types like multiple-choice items, these methods require responses in students' own words. However, challenges exist in the scoring process marked by subjectivity and the substantial cost of human labor. The automation of scoring processes in such assessments, utilizing statistical predictive modeling and artificial intelligence-driven techniques, presents a promising avenue for enhancing efficiency.

In my research endeavors, I have proposed, designed, and refined techniques employing linear regression, machine learning based classifiers, and BERT to evaluate students' writing levels, including their overall writing quality, reasoning efficiency, and expertise levels as my model labels. I have also advocated for the incorporation of features (*textual*: linguistic and semantic features; and *student-related*: cognitive levels of topical knowledge) into language models. Alternatively, large language models can be extended innovatively by integrating linguistic features, thematic attributes, and ontological perspectives to fine-tune the model so as to ensure that the model can effectively score students' educational products based on these important features.

<div class="publications">

{% bibliography -f papers -q @*[category=Assessment & Measurement]* %}

</div>
