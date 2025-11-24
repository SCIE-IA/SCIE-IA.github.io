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
  - IMG0006.JPG
  - IMG0007.JPG
  - IMG0008.JPG
  - IMG0009.JPG
  - IMG0010.JPG
  - IMG0011.JPG
  - IMG0012.JPG
  - IMG0013.JPG
  - IMG0014.JPG 
  - IMG0015.JPG
  - IMG0016.JPG
  - IMG0017.JPG
  - IMG0018.JPG
  - IMG0019.JPG
  - IMG0020.JPG
  - IMG0021.JPG
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