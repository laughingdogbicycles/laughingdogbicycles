---
layout: splash
permalink: /
hidden: false
title: Laughing Dog Bicycles
header:
    overlay_image: assets/images/main_photo.jpg
    overlay_filter: rgba(0, 0, 0, 0.4)

---

<br>

# Hours

Monday - Thursday 10am - 6pm

Friday - Saturday 10am - 5pm

Sunday - closed

<br>

# Contact

[(413) 253-7722](tel:+14132537722)

<br>

# Location

69 S. Pleasant Street, Amherst, MA (around the back) [Directions](https://www.google.com/maps/dir//42.3747852,-72.5202888/@42.3749162,-72.5205297,20.62z/data=!4m2!4m1!3e0?entry=ttu)

<br>

# Recent Announcements

{% if paginator %}
  {% assign posts = paginator.posts %}
{% else %}
  {% assign posts = site.posts %}
{% endif %}

{% assign entries_layout = page.entries_layout | default: 'list' %}
<div class="entries-{{ entries_layout }}">
  {% for post in posts limit: 3%}
    {% include archive-single.html type=entries_layout %}
  {% endfor %}
</div>

{% include paginator.html %}