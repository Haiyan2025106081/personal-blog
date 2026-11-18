---
title: 智能传播与技术实践归档
description: 用于梳理新媒体交互设计、AI 自动化工作流等课程实践材料，集中留存可替换的过程图与阶段成果。
pubDate: 2026-11-17
category: AI与智能传播
tags: [智能传播, 课程实践]
cover: ./cover.jpg
draft: false
---

![文章封面](./cover.jpg)

> 归档说明：本页用于梳理新媒体交互设计、AI 自动化工作流等课程实践材料。内容以可替换的图片位为主，便于后续按实际作业版本逐步更新。

## 长图版 PPT 归档

<style>
.ppt-gallery {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 18px;
  margin: 24px 0 8px;
}

.ppt-card {
  display: flex;
  flex-direction: column;
  border: 1px solid rgba(36, 74, 90, 0.08);
  border-radius: 16px;
  background: rgba(255, 253, 249, 0.72);
  box-shadow: var(--shadow-soft);
  color: inherit;
  text-decoration: none;
  transition: transform 180ms ease, box-shadow 180ms ease;
}

.ppt-card:hover {
  transform: translateY(-4px);
  box-shadow: var(--shadow-lift);
}

.prose .ppt-card__cover {
  display: block;
  width: 100%;
  aspect-ratio: 16 / 9;
  margin: 0;
  border-radius: 16px 16px 0 0;
  box-shadow: none;
  object-fit: contain;
  background-color: #f5f5f5;
}

.ppt-card__body {
  display: flex;
  flex: 1;
  flex-direction: column;
  gap: 10px;
  padding: 18px;
}

.ppt-card__title {
  margin: 0;
  font-size: 17px;
  font-weight: 700;
}

.ppt-card__hint {
  margin-top: auto;
  color: #3C8391;
  font-size: 13px;
}

@media (max-width: 760px) {
  .ppt-gallery {
    grid-template-columns: 1fr;
  }
}

@media (prefers-reduced-motion: reduce) {
  .ppt-card {
    transition: none;
  }
}
</style>

<div class="ppt-gallery">
  <a class="ppt-card" href="/posts/post-1/assets/ppt-01.jpg" target="_blank" rel="noopener noreferrer">
    <img class="ppt-card__cover" src="./assets/cover-01.jpg" alt="封面1" style="width: 100%; height: auto; aspect-ratio: 16 / 9; object-fit: contain; background: #f0f0f0;" />
    <div class="ppt-card__body">
      <p class="ppt-card__title">从精神生产资料看数字时代新闻人民性的消解与重塑</p>
      <span class="ppt-card__hint">点击查看完整长图 →</span>
    </div>
  </a>

  <a class="ppt-card" href="/posts/post-1/assets/ppt-02.jpg" target="_blank" rel="noopener noreferrer">
    <img class="ppt-card__cover" src="./assets/cover-02.jpg" alt="封面2" style="width: 100%; height: auto; aspect-ratio: 16 / 9; object-fit: contain; background: #f0f0f0;" />
    <div class="ppt-card__body">
      <p class="ppt-card__title">速度——运动科学的多维度解析</p>
      <span class="ppt-card__hint">点击查看完整长图 →</span>
    </div>
  </a>

  <a class="ppt-card" href="/posts/post-1/assets/ppt-03.jpg" target="_blank" rel="noopener noreferrer">
    <img class="ppt-card__cover" src="./assets/cover-03.jpg" alt="封面3" style="width: 100%; height: auto; aspect-ratio: 16 / 9; object-fit: contain; background: #f0f0f0;" />
    <div class="ppt-card__body">
      <p class="ppt-card__title">嵌瓷醉月——隆昌嵌瓷坊的雅韵与新生</p>
      <span class="ppt-card__hint">点击查看完整长图 →</span>
    </div>
  </a>
</div>
