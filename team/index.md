---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Meet our team!

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

### {% include icon.html icon="fa-solid fa-users" %}Current Members

{%
  include feature.html
  image="images/group-photo.jpg"
  title="Dr. Adi Steif"
  text="I am in the department of Molecular Biology and Biochemistry at Simon Fraser University and hold a Scientist appointment in the BC Cancer Genome Sciences Centre. I completed my MSc and PhD in bioinformatics at UBC in the laboratory of Marco Marra. My early research involved the use of massively parallel sequencing to identify driver mutations in leukemias and lymphomas including histone modifiers such as EZH2 and KMT2D. My current research focus involves using genome and transcriptome sequencing to discover novel drivers in B-cell lymphomas and to determine mechanisms that underlie tumour progression and treatment resistance. I have a general interest in developing methods to identify non-coding mutations with regulatory potential from genome-wide data sets and error-corrected sequencing strategies and algorithms to identify mutations and copy number from circulating tumour DNA (ctDNA). Dr. Morin is a Scholar of the Michael Smith Foundation for Health Research."
%}

{% include list.html data="members" component="portrait" filters="role: ^(?!pi$|alum$)" %}

### {% include icon.html icon="fa-solid fa-graduation-cap" %}Alumn

{% include list.html data="members" component="portrait" filters="role: alum" %}
