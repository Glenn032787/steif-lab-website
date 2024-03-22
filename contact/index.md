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

If you are interested to join the lab, collaborate, or inquire, please do not hesitate to send Adi an email (asteif@bcgsc.ca). 

**Undergraduate students:** To discuss potential research projects or ideas, feel free to reach out to Titipat and arrange a brief meeting.

**Graduate students:** Prospective students interested in pursuing a Masters or PhD program in Bioinformatics at University of British Columbia (UBC) or Simon Fraser University (SFU) can submit a CV along with a brief statement of their research interests before applying. Adi is also available for co-advising in various departments.

**Other positions:** The lab is always actively looking for interns, researchers, and developers. If you are interested in doing these position (locally or remotely), please also do not hesitate to email Adi to discuss.

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

{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/xg3FeCSWRk85p4n58"
%}



{% endcapture %}

{% capture col2 %}


{%
  include figure.html
  image="images/bccrc.jpg"
  caption="BC Cancer Research Center\n(675 W 10th Ave, Vancouver, BC V5Z 1L3)"
%}
{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}