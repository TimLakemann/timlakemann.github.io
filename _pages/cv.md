---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. Candidate, Multi-Robot Systems Group, Czech Technical University in Prague (ongoing)  
* M.Sc. in Aerospace Computer Science, Julius-Maximilian University of Würzburg, Germany, 2023 (*Final Grade: 1.1 [A]*)  
* B.Sc. in Aerospace Computer Science, Julius-Maximilian University of Würzburg, Germany, 2019 (*Final Grade: 1.8 [B]*)  

Work Experience
======
* **01/2020 – 09/2021: Software and Hardware Developer**  
  *Emqopter GmbH, Würzburg*  
  * Development of a fully autonomous UAV landing platform in C++ and Python  
  * Design and construction of 3D components for UAV systems  
  * UI implementation using Qt Creator  

* **10/2019 – 12/2019: Research Assistant**  
  *Zentrum für Telematik e.V., Würzburg*  
  * Configuration of wireless communication networks for telematics systems  

Publications
======
<ul>
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

Skills
======
* **Programming:** C++, C, Python, MATLAB, ROS/Gazebo  
* **Research Focus:** Multi-robot systems, Mutual Relative Localization, Computer Vision, Communication Systems
