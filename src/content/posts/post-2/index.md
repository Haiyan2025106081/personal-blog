---
title: 视觉创作与角色演绎记录
description: 用于集中归档视觉二创、妆造与后期处理的过程记录和作品图片，保留可替换的展示位。
pubDate: 2026-11-16
category: 视觉与二创
tags: [视觉创作, 角色演绎]
cover: ./cover.jpg
draft: false
---

![文章封面](./cover.jpg)

> 归档说明：本页记录视觉二创、妆造和后期心得，当前仅保留可替换的作品照片位，后续可按实际拍摄与制作版本补充。

## 作品照片位

<style>
.cos-gallery {
  display: grid;
  grid-template-columns: repeat(4, minmax(0, 1fr));
  gap: 44px 40px;
  margin: 28px 0 8px;
  padding: 20px 24px 32px;
}

.cos-photo-wrapper {
  position: relative;
  isolation: isolate;
}

/* 底层色块：与照片等尺寸，顺时针旋转 10deg，置于照片下方形成错位拼贴 */
.cos-photo-wrapper::before {
  content: "";
  position: absolute;
  inset: 0;
  z-index: -1;
  border-radius: 2px;
  background: linear-gradient(135deg, #EEF2F4 0%, #F6E9F0 55%, #FBEEDD 100%);
  transform: rotate(10deg);
  transform-origin: center center;
  box-shadow: 0 6px 16px rgba(36, 74, 90, 0.1);
}

.cos-photo-wrapper:nth-child(1)::before {
  background: linear-gradient(135deg, #E4EDF1 0%, #D6E8E8 100%);
}

.cos-photo-wrapper:nth-child(2)::before {
  background: linear-gradient(135deg, #F2E5EF 0%, #E6DCEF 100%);
}

.cos-photo-wrapper:nth-child(3)::before {
  background: linear-gradient(135deg, #FBEADB 0%, #F6DDC8 100%);
}

.cos-photo-wrapper:nth-child(4)::before {
  background: linear-gradient(135deg, #E7EFE6 0%, #D9E8E4 100%);
}

/* 照片本体：正向显示、层级在上，极细白边 + 柔和阴影模拟拍立得 */
.prose .cos-photo {
  position: relative;
  z-index: 1;
  display: block;
  width: 100%;
  height: auto;
  margin: 0;
  object-fit: contain;
  border: 2px solid #ffffff;
  border-radius: 2px;
  box-shadow: 0 8px 20px rgba(36, 74, 90, 0.14);
}

@media (max-width: 720px) {
  .cos-gallery {
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 34px 32px;
    padding: 18px 20px 28px;
  }
}

@media (prefers-reduced-motion: reduce) {
  .cos-photo-wrapper::before {
    transform: none;
  }
}
</style>

<div class="cos-gallery">
  <div class="cos-photo-wrapper">
    <img class="cos-photo" src="./assets/cosplay-01.jpg" alt="Cosplay 作品照片 01" style="display: block; width: 100%; height: auto; object-fit: contain; margin: 0; border: 2px solid #ffffff; border-radius: 2px; box-shadow: 0 8px 20px rgba(36, 74, 90, 0.14);" />
  </div>
  <div class="cos-photo-wrapper">
    <img class="cos-photo" src="./assets/cosplay-02.jpg" alt="Cosplay 作品照片 02" style="display: block; width: 100%; height: auto; object-fit: contain; margin: 0; border: 2px solid #ffffff; border-radius: 2px; box-shadow: 0 8px 20px rgba(36, 74, 90, 0.14);" />
  </div>
  <div class="cos-photo-wrapper">
    <img class="cos-photo" src="./assets/cosplay-03.jpg" alt="Cosplay 作品照片 03" style="display: block; width: 100%; height: auto; object-fit: contain; margin: 0; border: 2px solid #ffffff; border-radius: 2px; box-shadow: 0 8px 20px rgba(36, 74, 90, 0.14);" />
  </div>
  <div class="cos-photo-wrapper">
    <img class="cos-photo" src="./assets/cosplay-04.jpg" alt="Cosplay 作品照片 04" style="display: block; width: 100%; height: auto; object-fit: contain; margin: 0; border: 2px solid #ffffff; border-radius: 2px; box-shadow: 0 8px 20px rgba(36, 74, 90, 0.14);" />
  </div>
</div>
