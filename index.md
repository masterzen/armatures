---
layout: page
title: Armatures
---

# Armatures #

Here are the armatures:

<table>
    <th>
      <td>#</td><td>Title</td><td>Revision</td><td>Champion</td><td>Project</td>
    </th>
    {% for page in site.pages %}
      {% if page.main-page %}
      <tr>
        <td>{{page.arm}}</td><td><a href="{{page.url}}">{{page.title}}</a></td><td>{{page.champion}}</td><td>{{page.project}}</td>
      </tr>
      {% endif %}
    {% endfor %}
</table>
