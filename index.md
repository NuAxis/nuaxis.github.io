---
layout: default
---

# NuAxis Open Source
~~~~~~~~~~~~~~~~~~~~~

We are a group of people who are passionate about open source. We have delivered successful solutions by leveraging open source technologies. We have been able to spend more time on building the solution rather than on technology because of the openness and free availability of open source software.

We want to create more value than we capture and we actively encourage our team members to contribute towards open source projects. We hope that our contributions would help sustain this open and free community.


{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }})
{% endfor %}
