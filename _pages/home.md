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

Tuesday - Thursday: 10am - 6pm

Friday & Saturday: 10am - 5pm


Sunday & Monday: closed

<br>

# Contact

[(413) 253-7722](tel:+14132537722)

<br>

# We are open throughout construction next door!

There is construction across the alley and, though the alley will periodically be closed, **we will be open** throughout. Three alleys provide access to our store and only the northernmost alley will be affected by construction. You can always enter through the southernmost alley. 

The entry to the southernmost alley is just south of 79 S. Pleasant Street, a large white building with a large cupola. The entrance is 3m south of a covered bus stop. [This link will open a directions to the entrace](https://www.google.com/maps/dir//42.3743889,-72.5199763/@42.3744161,-72.5201386,149m/data=!3m1!1e3!4m2!4m1!3e0?entry=ttu) and you can see a [streetview of the entrance here](https://www.google.com/maps/@42.3743714,-72.5197956,3a,75y,276.01h,91.61t/data=!3m6!1e1!3m4!1sjVKDIzK8fatVIjrIog4Lpg!2e0!7i16384!8i8192?coh=205409&entry=ttu).

<div id="observablehq-viewof-map-eb52eb73"></div>

<br>

# Location

63 Rear S. Pleasant Street, Amherst, MA (around the back) [Directions are here](https://www.google.com/maps/dir//42.3747852,-72.5202888/@42.3749162,-72.5205297,20.62z/data=!4m2!4m1!3e0?entry=ttu). Please note that the alley may sometimes be closed. Reference the map and links above for instructions on how to access Laughing Dog Bicycles when the northermost alley is closed.


<br>

# Recent announcements

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


<head><script type="module">
import {Runtime, Inspector} from "https://cdn.jsdelivr.net/npm/@observablehq/runtime@5/dist/runtime.js";
import define from "https://api.observablehq.com/@cyrusobrien/laughing-dog-map.js?v=4";
new Runtime().module(define, name => {
  if (name === "viewof map") return new Inspector(document.querySelector("#observablehq-viewof-map-eb52eb73"));
});
</script>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@observablehq/inspector@5/dist/inspector.css">
</head>