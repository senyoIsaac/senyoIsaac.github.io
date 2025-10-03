---
layout: archive
title: "Gallery"
permalink: /gallery/
---

Explore images and visuals of me, a journey in the making.

<style>
  .gallery-section {
    margin-bottom: 40px;
  }
  .gallery-title {
    font-size: 24px;
    margin-bottom: 10px;
  }
  .gallery-images {
    display: flex;
    flex-wrap: wrap;
    gap: 15px;
  }
  .gallery-images img {
    width: 300px;
    height: 200px;
    object-fit: cover;
    border-radius: 8px;
    border: 2px solid #ddd;
    transition: transform 0.3s;
  }
  .gallery-images img:hover {
    transform: scale(1.05);
    border-color: #007bff;
  }
</style>

---

## 6-Months Labourer At NickSeth Construction Company
Highlights of activities that shaped my engineering thoughts.

<div class="gallery-section">
  <div class="gallery-title">2021</div>
  <div class="gallery-images">
    {% for i in (1..15) %}
      <img src="/images/NickSeth/NickSeth{{ i }}.jpg" alt="Labourer {{ i }}">
    {% endfor %}
  </div>
</div>

