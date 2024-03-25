---
title: Research
nav:
  order: 1
  tooltip: Resarch interest
---

# {% include icon.html icon="fa-solid fa-wrench" %}Research

Our research is focused on developing and applying computational methods for high-throughput genomics, with a particular interest in characterizing disease mechanisms and evolution in the context of cancer. New measurement technologies are enabling large-scale genetic, transcriptomic and epigenetic profiling of tissues at the single cell level. Working alongside experimental collaborators, the Steif Lab uses statistical machine learning approaches to derive biological insights from these high-dimensional datasets in the presence of noise and measurement bias. 

{% include section.html %}
{% capture text %}

One of our lab interest lies in development and utilization of novel single-cell sequencing technology. With tools like the DLP and Isolatrix sequencing platforms, which provide faster cell dispensing and customizable well chemistry, we aim to obtain high quality genomic data at a single cell resolution. Our research focuses on understanding unique characteristics at the single-cell level, such as cell cycle dynamics and ploidy variation. We're excited to explore these complexities and contribute to the broader understanding of biological systems.

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Single Cell Sequencing"
  text=text
%}


{% capture text %}
By dissecting tumor samples at the single-cell level, we aim to identify distinct clonal populations within the tumor microenvironment. We strive to investigate the unique characteristics of each clonal population, shedding light on their diverse molecular profiles, genetic mutations, and functional attributes. This approach offers a deeper understanding of tumor heterogeneity and evolution, paving the way for more targeted and personalized therapeutic interventions.

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Cancer development"
  text=text
%}
