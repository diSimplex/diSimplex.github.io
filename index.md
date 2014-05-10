---
layout: default
title: diSimplex
projects:
- title: diSimplexEngine
  url: diSimplexEngine
  caption: The diSimplexEngine project documents the internals of the directed simplex programming engine which can be used to run mathematical proofs.
--- 

# diSimplex

The diSimplex organization is devoted to exploring the foundations of 
mathematics using directed simplicial structures.

# Projects

{% for project in page.projects %}
- [**{{project.title}}**]({{project.url}}) {{project.caption}}
{% endfor %}
