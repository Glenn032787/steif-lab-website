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

# **Dr. Adi Steif**, Professor
{%
  include feature.html
  image="images/group-photo.jpg"
  text="Dr. Adi Steif’s research is focused on developing and applying computational methods for high-throughput genomics, with a particular interest in characterizing disease mechanisms and evolution in the context of cancer. New measurement technologies are enabling large-scale genetic, transcriptomic and epigenetic profiling of tissues at the single cell level. Working alongside experimental collaborators, Dr. Steif uses statistical machine learning approaches to derive biological insights from these high-dimensional datasets in the presence of noise and measurement bias. Her past research contributions focused on copy number inference and clonal evolution in breast cancer, and characterizing changes in normal mammary tissue in the context of ageing and inherited cancer susceptibility.
  
  Dr. Steif was previously a Junior Research Fellow at Trinity College, University of Cambridge and a member of the inaugural class of Schmidt Science Fellows. She completed her postdoctoral research at the Cancer Research UK Cambridge Institute and European Bioinformatics Institute with Dr. John Marioni. Prior to this, she obtained her Ph.D. at UBC and BC Cancer under the supervision of Dr. Sohrab Shah and Dr. Sam Aparicio."
%}


{%
  include button.html
  type="email"
  link="asteif@bcgsc.ca"
  text="asteif@bcgsc.ca"
  tooltip="asteif@bcgsc.ca"
  style="bare"
%}
{%
  include button.html
  type="phone"
  text="604–707–5900"
  style="bare"
%}
{%
  include button.html
  type="google-scholar"
  link="https://scholar.google.com/citations?user=aCAx8r4AAAAJ"
  text="Google Scholar"
  tooltip="Google Scholar"
  style="bare"
%}
### {% include icon.html icon="fa-solid fa-users" %}Current Lab Members

{% include list.html data="members" component="portrait" filters="role: ^(?!pi$|alum$)" %}

### {% include icon.html icon="fa-solid fa-graduation-cap" %}Alumn

{% include list.html data="members" component="portrait" filters="role: alum" %}
