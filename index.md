---
layout: default
---

The list of Fediverse organizations are also available as a [JSON file](/orgs.json) suitable for consuming programmatically.

Insert some info about how to add yours here in the github repo [CoSocial-Canada/FediverseGalaxies](https://github.com/CoSocial-Canada/FediverseGalaxies)

<h2>Latest Fediverse Organizations</h2>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>