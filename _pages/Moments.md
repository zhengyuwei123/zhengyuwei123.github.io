---
layout: page
title: Moments
permalink: /Moments/
---

<style>
    .image-grid {
      display: flex;
      flex-wrap: wrap;
      gap: 20px; /* 图片之间的间距 */
      justify-content: center;
    }

    .image-grid div {
      flex: 0 0 calc(50% - 20px); /* 每排两个，减去间距 */
      box-sizing: border-box;
    }

    .image-grid img {
      width: 100%;
      height: auto;
      display: block;
      border-radius: 10px; /* 可选：图片圆角 */
      box-shadow: 0 4px 10px rgba(0,0,0,0.1); /* 可选：阴影 */
    }

    @media (max-width: 600px) {
      .image-grid div {
        flex: 0 0 100%; /* 小屏幕下单列显示 */
      }
    }
  </style>

# <span style="font-family: Roboto; font-size: 24px;">📝 Moments</span>


<div class="image-grid">
  <div><img src="/images/Trip/p1.jpg" alt="p1"></div>
  <div><img src="/images/Trip/p2.jpg" alt="p2"></div>
  <div><img src="/images/Trip/p3.jpg" alt="p3"></div>
  <div><img src="/images/Trip/p4.jpg" alt="p4"></div>
  <!-- 继续添加更多图片 -->
</div>
