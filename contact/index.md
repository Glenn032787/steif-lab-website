---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact



{% include section.html %}

{% capture col1 %}
If you are interested to join the lab, collaborate, or inquire, please do not hesitate to send Adi an email (asteif@bcgsc.ca). 

{%
  include button.html
  type="email"
  text="asteif@bcgsc.ca"
  link="asteif@bcgsc.ca"
%}
{%
  include button.html
  type="phone"
  text="(604) 707–5900"
  link="+1-604–707–5900"
%}


{% endcapture %}

{% capture col2 %}

We are located at on the 8th floor of the BC Cancer Research Center.

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/xg3FeCSWRk85p4n58"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html}

# Join Us
**Undergraduate students:** To discuss potential research projects or ideas, feel free to reach out to Titipat and arrange a brief meeting.

**Graduate students:** Prospective students interested in pursuing a Masters or PhD program in Bioinformatics at University of British Columbia (UBC) or Simon Fraser University (SFU) can submit a CV along with a brief statement of their research interests before applying. Adi is also available for co-advising in various departments.

**Other positions:** The lab is always actively looking for interns, researchers, and developers. If you are interested in doing these position (locally or remotely), please also do not hesitate to email Titipat to discuss.
