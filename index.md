---
layout: splash
author_profile: false
header:
  image: images/Dami.jpeg
  overlay_image: true # Adds the overlay effect to the image
  overlay_filter: rgba(0, 0, 0, 0.5) # Darkens the image to make the text more readable
intro: 
  - title: ""
    excerpt: " **Welcome! I'm Victor Adu**.<br><br>

              I recently graduated with a degree in Mechanical and Mechatronics Engineering from the [University of Cape Town](https://www.uct.ac.za). My passion lies at the intersection of Controls, Data Analytics, and Aerospace Engineering. I'm currently on the lookout for exciting graduate opportunities in top institutions across the United States.
     "
---

{% include feature_row id="intro" type="center" %}

<style>
  .page-header {
    position: relative;
  }
  
  .page-header::before {
    content: '';
    background: rgba(0, 0, 0, 0.5); /* Adjust this for a darker or lighter overlay */
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
  }

  .page-header h1, .page-header p {
    position: absolute;
    color: white;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    text-align: center;
    padding: 20px;
  }
</style>
