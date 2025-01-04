---
permalink: /about/
title: "About Us"
---

## Who We Are
We are a small team of college students from the Metro Atlanta Area, dedicated to transforming the healthcare industry. Our expertise spans:

- **Front-end Development**
- **Agentic System Orchestration**
- **Graph Theory**

---
layout: single
title: "About Us"
permalink: /about/
---

# Meet the Team

Our team is comprised of dedicated individuals passionate about transforming healthcare through technology and innovation.

<div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 20px;">

{% assign team_members = site.data.team %}
{% for member in team_members %}
<div style="text-align: center; flex: 1 0 30%; max-width: 30%; margin: 10px;">
  <a href="{{ member.linkedin }}" target="_blank">
    <img src="{{ member.image }}" alt="{{ member.name }}" style="width: 150px; height: 150px; border-radius: 50%; object-fit: cover;">
  </a>
  <p style="font-size: 0.9em; margin-top: 10px;">
    <strong>{{ member.name }}</strong><br>
    {{ member.occupation }}<br>
    {{ member.position }}
  </p>
</div>
{% endfor %}

</div>

---

## Interested to Join Us?
Are you passionate about innovation in healthcare and cutting-edge technology? We're always looking for enthusiastic individuals to collaborate with us!

### How You Can Get Involved:
- **Front-End**: Join us as an contributor.
- **Researchers**: Partner with us on exciting projects.
- **Organizations**: Collaborate to bring impactful solutions to life.
