---
layout: project
title: HUBBLE – HUman Behaviour-Based explainable machine LEarning 
slug: hubble
link: na
status: inactive
time: 12/2019–02/2022
funding: German Federal Ministry for Economics and Climate Action
image: HUBBLE-Project-Board.png
description: >-
    Within a very short time, machine learning algorithms analyse huge amounts of data, make predictions and issue personalised recommendations. How the machine arrives at its conclusions and how the results are to be interpreted often remains unclear. This is where the HUBBLE (HUman Behaviour-Based explainable machine Learning) research project comes in. The goal of HUBBLE is to address the role of humans in the development of machine learning algorithms and to transfer it to real work contexts. With the help of a novel algorithm approach - HBBO (Human Behaviour-Based Optimisation) - text data is categorised (classified) in terms of relevance and importance. The special feature of HBBO is that it optimises its mode of operation by imitating human behaviour, e.g. through the algorithmic simulation of groups that form experts, exchange of opinions, and influence each other in the learning process. The University of Applied Sciences Dresden, Mittweida University of Applied Sciences (HSMW) and the Dresden-based company spectos GmbH worked together on the project. The Chair for Visual Enginnering developed the visualisation and an interface to make the HBBO pipeline comprehensible for human viewers from the beginning and to create opportunities for direct influence in the machine learning process. In the process, current approaches for visualising complex relationships in data from the areas of Explainable Machine Learning as well as Visual Analytics will be integrated. The two-year project was funded by the Central Innovation Programme for SMEs (ZIM). After this project, work continues to investigate visualization literacy necessary to understand our interfaces and the role of aesthetics and subjective judgments.
---
<div class="offset3 col9 bottom-padding"></div>

<div class="offset3 col9">
    <h3>Related Publications</h3>
</div>

<div class="offset3 col9 bottom-padding">
    {%- assign sorted = site.publications | reverse -%}
    {%- for publ in sorted -%}
    {% if publ.tags contains "xai" %}
    <p class="small line-space dont-break-out">
        {{ publ.author }} ({{ publ.year }}). <a href="{{publ.link}}">{{ publ.title }}</a>. In: {{ publ.venue }}. {{
        publ.link }}
    </p>
    {% endif %}
    {%- endfor -%}
</div>