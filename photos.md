---
layout: page
title: Photos
permalink: /photos/
---

I try to take pictures sometimes.

<div class="photo-grid">
  <img src="/assets/photos/1.jpg" alt="Photo 1" />
  <img src="/assets/photos/2.jpg" alt="Photo 2" />
  <img src="/assets/photos/3.jpg" alt="Photo 3" />
  <img src="/assets/photos/4.jpg" alt="Photo 4" />
  <img src="/assets/photos/5.jpg" alt="Photo 5" />
  <img src="/assets/photos/6.jpg" alt="Photo 6" />
  <img src="/assets/photos/7.jpg" alt="Photo 7" />
  <img src="/assets/photos/8.jpg" alt="Photo 8"/>
  <img src="/assets/photos/9.jpg" alt="Photo 9">
  <img src="/assets/photos/10.jpg" alt="Photo 10"/>
  <img src="/assets/photos/11.jpg" alt="Photo 11"/>
</div>

<style>
.photo-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
  gap: 1rem;
  margin-top: 1.5rem;
}

.photo-grid img {
  width: 100%;
  height: 220px;
  object-fit: cover;
  border-radius: 8px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.3);
  transition: transform 0.2s;
}

.photo-grid img:hover {
  transform: scale(1.02);
}
</style>