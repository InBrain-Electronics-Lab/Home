---
title: Our Team
nav:
  order: 3
  tooltip: About our lab
---

# {% include icon.html icon="fa-solid fa-users" %}A small but mighty team makes up the InBrain Electronics Lab!

{% include section.html %}
{% include section.html background="images/background.jpg" dark=true %}
{% include list.html data="site.members" component="portrait" filter="role == 'pi'" %}

  Assistant Professor, Biomedical Engineering, Stevens Institute of Technology
  Postdoctoral Researcher, Electrical Engineering, Columbia University
  PhD, Electrical Engineering, École des Mines de Saint-Étienne
  Master of Science, Biophysics, Technical University of Dresden
  Bachelor's Degree, Electrical Engineering, Yildiz Technical University

Research Interests:
Hobbies: 

{% include section.html %}

{% include list.html data="members/ilke-uguz.md" component="portrait" filter="role == 'Principal Investigator'" %} {% include section.html background="images/background.jpg" dark=true %} {% include figure.html image="images/Ilke.png" %}

{% include section.html %}
{% include list.html data="members/sara-bender-bier.md" component="portrait" filter="role == 'PhD Student'" %}
{% include section.html background="images/background.jpg" dark=true %}
{% include figure.html image="images/Sara.jpg" %}

  PhD Student, Biomedical Engineering, Stevens Institute of Technology
  Master of BioEngineering, Applied Bioengineering, Rice University
  Bachelor of Science, Cellular & Molecular Biology: Biomedical Engineering, University of Michigan
  
Sara has expertise in bipolar and multipolar electrical sensing and stimulation applications in the medical device industry. Before joining the InBrain Electronics Lab, she spent three years focused on Cardiac Rhythm Management at Abbott, troubleshooting and programming pacemakers and defibrillators. Before Abbott, she was the Lead Product Development Engineer at a startup called XN Health, developing a novel multipolar basket catheter for trans-tracheal electrical stimulation. Before completing her Master's at Rice, Sara was an ORISE Fellow at the Center for Devices and Radiological Health (CDRH) at the FDA in the Division of Applied Mechanics, focused on the development of safety parameters for ultrasound permeation of the Blood-Brain Barrier, as well as COVID-19 Infection Modeling.

Research Interests: Visual Prosthetics, Flexible Microelectronics, Chemical Sensing
Hobbies: Soccer, Hiking, 3D Printing, Hanging out with my dog Lincoln

{% capture content %}

{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
