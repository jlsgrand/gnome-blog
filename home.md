---
permalink: /
layout: main.html
---

# Bienvenue sur le blog de Gilles

Ma passion : les nains de jardin

## Mes Derniers Posts

{% for post in collections.posts %}
- [{{post.data.title}}]({{post.url}})
{% endfor %}
