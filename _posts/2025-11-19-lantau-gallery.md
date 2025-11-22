---
layout: post
title: Lantau Gallery
date: 2025-11-19 10:00:00 -0500
# This is where you list your images. 
# Just add a new line with "- " and the filename for each photo.
gallery_images:
  - IMG0001.JPG
  - IMG0002.JPG
  - IMG0003.JPG
  - IMG0004.JPG
  - IMG0005.JPG
---

Here are the photos from our lantau trip!

<div style="display: flex; flex-wrap: wrap; gap: 10px; justify-content: center;">
  {% for image in page.gallery_images %}
    <div style="flex: 1 1 300px; max-width: 400px;">
      <img src="{{ site.baseurl }}/assets/images/{{ image }}" alt="{{ image }}" style="width: 100%; height: auto; border-radius: 5px;">
    </div>
  {% endfor %}
</div>

Hope you liked them!