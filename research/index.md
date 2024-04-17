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


Our lab interest lies in development and utilization of novel single-cell sequencing technology. With tools like the DLP and Isolatrix sequencing platforms, which provide faster cell dispensing and customizable well chemistry, we aim to obtain high quality genomic data at a single cell resolution to resolve cell cycle dynamics and ploidy variation. 

{% endcapture %}

{%
  include feature.html
  image="images/DLP.jpg"
  link="research"
  title="Single Cell Sequencing"
  text=text
%}


{% capture text %}
By dissecting tumor samples at the single-cell level, we aim to identify distinct clonal populations within the tumor microenvironment. We strive to investigate the unique characteristics of each clonal population, shedding light on their tumor heterogeneity and evolution. 

{% endcapture %}

{%
  include feature.html
  image="images/cancer_dev.png"
  link="research"
  title="Cancer development"
  text=text
%}

{% include section.html %}
We gratefully acknowledge funding support from:

{% capture content %}

<img src="../images/funding_logo/UBCMedicine.png" alt="UBC Medicine"/>
<img src="../images/funding_logo/bccancer.png" alt="BC Cancer"/>
<img src="../images/funding_logo/genomeBC.jpg" alt="Genome BC"/>
<img src="../images/funding_logo/Canadian_Institutes_of_Health_Research.png" alt="Canadian Institutes of Health Research"/>
<img src="../images/funding_logo/terry_fox.png" alt="Terry Fox Research Institute"/>
<img src="../images/funding_logo/MichaelSmithHealthResearchBC.png" alt="Michael Smith Foundation for Health Research"/>
<img src="../images/funding_logo/CFI.png" alt="Canada Foundation for Innovation"/>

{% endcapture %}

{% include grid.html content=content %}
