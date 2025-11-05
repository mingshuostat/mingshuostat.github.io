---
layout: single
title: "Follow my lens."
permalink: /photograph/
author_profile: true
---
 
Through my lens — moments under the stars and beyond.  
Click on any photo to view it in full size.

<style>
.container-narrow { max-width: 1100px; margin: 0 auto; }

.photo-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr); /* 2 列 */
  gap: 16px;
  margin-top: 1rem;
}
.photo-grid a { display: block; }

.photo-grid img {
  width: 100%; height: 100%;
  object-fit: cover; object-position: center;
  border-radius: 12px; box-shadow: 0 2px 10px rgba(0,0,0,.08);
  transition: transform .2s ease;
}
.photo-grid a:hover img { transform: scale(1.01); }

/* 核心：竖图与横图用不同纵横比 */
img.portrait  { aspect-ratio: 3 / 4; }   /* 竖图 */
img.landscape { aspect-ratio: 16 / 9; }  /* 横图 */

/* 手机端：单列 */
@media (max-width: 720px) {
  .photo-grid { grid-template-columns: 1fr; }
}
</style>

<div class="container-narrow">
  <div class="photo-grid">
    <!-- 前两张竖图 -->
    <a href="/images/photograph/star1.JPG" target="_blank" rel="noopener">
      <img class="portrait"  src="/images/photograph/star1.JPG"  alt="Photo 1" loading="lazy">
    </a>
    <a href="/images/photograph/snow.JPG" target="_blank" rel="noopener">
      <img class="portrait"  src="/images/photograph/snow.JPG"  alt="Photo 2" loading="lazy">
    </a>

    <!-- 后面四张横图 -->
    <a href="/images/photograph/star2.JPG" target="_blank" rel="noopener">
      <img class="landscape" src="/images/photograph/star2.JPG" alt="Photo 3" loading="lazy">
    </a>
    <a href="/images/photograph/rainbow.JPG" target="_blank" rel="noopener">
      <img class="landscape" src="/images/photograph/rainbow.JPG" alt="Photo 4" loading="lazy">
    </a>
    <a href="/images/photograph/yellowstone.jpg" target="_blank" rel="noopener">
      <img class="landscape" src="/images/photograph/yellowstone.jpg" alt="Photo 5" loading="lazy">
    </a>
    <a href="/images/photograph/sea.JPG" target="_blank" rel="noopener">
      <img class="landscape" src="/images/photograph/sea.JPG" alt="Photo 6" loading="lazy">
    </a>
  </div>
</div>
