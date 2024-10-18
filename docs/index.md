---
layout: rapport
order: 1
---

# Rapports

<a href="/lab-scrum/pkg_global/rapport"> Rapport globale </a> 

## Par packages

<ul>
  {% for package in site.data.packages_json %}
    <li> <a href="/lab-scrum/{{ package.name }}/rapport"> {{ package.titre }} </a> </li>
  {% endfor %}
</ul>
