---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Meet our team!

Meet our diverse interdisplinary team of biological, computational and mathematical researchers. The team includes undergraduates, master students and staff members. Click [here]({% link contact/index.md %}) if you would join our team.

{% include section.html %}

# **Dr. Adi Steif**, Professor
{% capture info %}
Dr. Adi Steif’s research is focused on developing and applying computational methods for high-throughput genomics, with a particular interest in characterizing disease mechanisms and evolution in the context of cancer. New measurement technologies are enabling large-scale genetic, transcriptomic and epigenetic profiling of tissues at the single cell level. 
  
Dr. Steif was previously a Junior Research Fellow at Trinity College, University of Cambridge and a member of the inaugural class of Schmidt Science Fellows. She completed her postdoctoral research at the Cancer Research UK Cambridge Institute and European Bioinformatics Institute with Dr. John Marioni. Prior to this, she obtained her Ph.D. at UBC and BC Cancer under the supervision of Dr. Sohrab Shah and Dr. Sam Aparicio.

Dr. Steif is currently program affiliation includes Medical Genetics, Bioinformatics, and Genome Science and Technology program at the University of British Columbia.
{% endcapture %}

{%
  include feature.html
  image="images/people/adi_steif.jpg"
  text=info
%}


{% include section.html %}

### {% include icon.html icon="fa-solid fa-users" %}Current Lab Members

{% include list.html data="members" component="portrait" filters="role: programmer" %}
{% include list.html data="members" component="portrait" filters="role: postdoc" %}
{% include list.html data="members" component="portrait" filters="role: phd" %}
{% include list.html data="members" component="portrait" filters="role: master" %}
{% include list.html data="members" component="portrait" filters="role: undergrad" %}


{% include section.html %}
### {% include icon.html icon="fa-solid fa-graduation-cap" %}Alumni 

{% include list.html data="members" component="portrait" filters="role: alumni" %}

