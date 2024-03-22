---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact



{% include section.html %}

{% capture col1 %}
We are part of the BC Cancer in Vancouver Canada. The lab is located on the 8th floor of the [BC Cancer Research Center building](https://www.google.com/maps/place/BC+Cancer+Research+Centre/@49.2625745,-123.1193424,15z/data=!4m2!3m1!1s0x0:0x8120a7e52adbc3f2?sa=X&ved=1t:2428&hl=en&ictx=111). Card access is required for entry to lab spaces.

We are a fully computational lab, if you are interested to join the lab, collaborate, or inquire, please do not hesitate to contact Adi. 

**Undergraduate students:** To join our lab, please apply through directed studies or co-op program. Feel free to reach out to discuss potential research projects.

**Graduate students:** We welcome highly motivated graduate students interested in computational research to join our lab through the University of British Columbia [Bioinformatics](https://www.bioinformatics.ubc.ca/apply/), [Genome Science and Technology](https://www.gsat.ubc.ca/admission/) or [Medical Genetic](https://medgen.med.ubc.ca/graduate-program/prospective-students/) program. Feel free to contact Adi to discuss through the ["Supervisor Enquiry" form](https://www.grad.ubc.ca/researcher/20992-steif).

**Other positions:** For additional positions, please look out for job positings on Michael Smith Genome Sciences Centre [careers board](https://www.bcgsc.ca/careers) 

{% endcapture %}

{% capture col2 %}


{%
  include figure.html
  image="images/bccrc.jpg"
  caption="BC Cancer Research Center<br>(675 W 10th Ave, Vancouver, BC V5Z 1L3)"
%}


{%
  include button.html
  type="address"
  tooltip="Address"
  link="https://maps.app.goo.gl/xg3FeCSWRk85p4n58"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}