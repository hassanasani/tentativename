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

## Meet the Team

<div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 20px;">

{% assign team_members = site.data.team %}
{% for member in team_members %}
  <div style="text-align: center; width: 200px; margin: 10px;">
    <!-- Image -->
    <img src="{{ member.image }}" alt="{{ member.name }}" style="width: 150px; height: 150px; border-radius: 50%; object-fit: cover; margin-bottom: 10px;">
    
    <!-- Name (Linked to LinkedIn) -->
    <p style="margin: 0; font-size: 1.1em; font-weight: bold;">
      <a href="{{ member.linkedin }}" target="_blank" style="text-decoration: none; color: #007acc;">{{ member.name }}</a>
    </p>
    
    <!-- Occupation and Position -->
    <p style="margin: 0; font-size: 0.9em;">{{ member.occupation }}</p>
    <p style="margin: 0; font-size: 0.9em;">{{ member.position }}</p>
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
