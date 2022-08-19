---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

# Ester Karen Aida

## Welcome


## Poems

- [Mitosis in the Burial Mounds](/poems/mitosis-in-the-burial-mounds.md)



<ul>
  {% for poem in site.poems %}
    <li>
      <a href="{{ poem.url }}">{{ poem.title }}</a>
    </li>
  {% endfor %}
</ul>


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
