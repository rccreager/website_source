---
layout: default
title: Gallery
big_header: true
categories:
 - gallery

images:
  - image_path: 20170126-IMG_9112.jpg
  - image_path: 20170126-IMG_9131.jpg
  - image_path: 20170126-IMG_9135.jpg
  - image_path: 20170126-IMG_9141.jpg
  - image_path: 20170126-IMG_9143.jpg
  - image_path: 20170126-IMG_9150.jpg
  - image_path: 20170126-IMG_9161.jpg
  - image_path: 20170126-IMG_9167.jpg
  - image_path: 20170126-IMG_9168.jpg
  - image_path: Healthcare-1.jpg
  - image_path: Healthcare-2.jpg
  - image_path: Healthcare-3.jpg
  - image_path: Healthcare-4.jpg
---

<ul id="lightSlider">
  {% for image in page.images %}
    <li><img size="50%" src="{{ image.image_path }}" alt="PDSG Event"/></li>
  {% endfor %}
</ul>
<script type="text/javascript">
    $(document).ready(function() {
      $("#lightSlider").lightSlider(); 
    });
</script>
