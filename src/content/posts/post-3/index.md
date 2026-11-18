---
title: 课程论文与实践作品汇总
description: 汇总课程论文与实践作品清单，以展览说明牌形式呈现三项代表性成果。
pubDate: 2026-11-15
category: 课程实践归档
tags: [课程论文, 作品汇总]
cover: ./cover.jpg
draft: false
---

汇总我的课程论文与实践作品清单。

<style>
.course-gallery {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 30px;
  margin: 32px 0 16px;
  padding: 14px 10px 26px;
}

.course-card {
  position: relative;
  display: flex;
  min-height: 260px;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  overflow: hidden;
  padding: 34px 26px;
  border: 1px solid rgba(255, 255, 255, 0.7);
  border-radius: 16px;
  color: var(--ink);
  text-align: center;
  text-decoration: none;
  -webkit-backdrop-filter: blur(12px);
  backdrop-filter: blur(12px);
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.15), inset 0 1px 1px rgba(255, 255, 255, 0.9), inset 0 -14px 26px rgba(255, 255, 255, 0.35);
  transition: transform 200ms ease, box-shadow 200ms ease;
}

.course-card::before {
  content: "";
  position: absolute;
  inset: 0;
  z-index: 0;
  opacity: 0.05;
  pointer-events: none;
  background-image: url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHdpZHRoPScxMjAnIGhlaWdodD0nMTIwJz48ZmlsdGVyIGlkPSduJz48ZmVUdXJidWxlbmNlIHR5cGU9J2ZyYWN0YWxOb2lzZScgYmFzZUZyZXF1ZW5jeT0nMC44NScgbnVtT2N0YXZlcz0nMycgc3RpdGNoVGlsZXM9J3N0aXRjaCcvPjwvZmlsdGVyPjxyZWN0IHdpZHRoPScxMDAlJyBoZWlnaHQ9JzEwMCUnIGZpbHRlcj0ndXJsKCNuKScvPjwvc3ZnPg==");
  background-repeat: repeat;
  background-size: 120px 120px;
}

.course-card:hover {
  transform: translateY(-6px);
  box-shadow: 0 16px 38px rgba(0, 0, 0, 0.18), inset 0 1px 1px rgba(255, 255, 255, 0.9), inset 0 -14px 26px rgba(255, 255, 255, 0.35);
}

.course-card span {
  position: relative;
  z-index: 1;
  font-size: 19px;
  font-weight: 800;
  letter-spacing: 0.08em;
  line-height: 1.7;
}

.course-card .course-hint {
  display: block;
  margin-top: 10px;
  font-size: 14px;
  font-weight: 500;
  letter-spacing: 0.04em;
  opacity: 0.7;
}

.course-card--teal {
  background: rgba(210, 240, 235, 0.7);
}

.course-card--blue {
  background: rgba(210, 230, 250, 0.7);
}

.course-card--lilac {
  background: rgba(230, 215, 245, 0.7);
}

@media (max-width: 860px) {
  .course-gallery {
    grid-template-columns: 1fr;
    gap: 22px;
  }
}

@media (prefers-reduced-motion: reduce) {
  .course-card {
    transition: none;
  }
}
</style>

<div class="course-gallery">
  <a href="./assets/course-01.jpg" target="_blank" class="course-card course-card--teal">
    <span>外婆的银镯无声陪伴——数字时代下遗物的媒介特性与情感传播</span>
    <span class="course-hint">点击查看完整内容 →</span>
  </a>
  <a href="./assets/course-02.jpg" target="_blank" class="course-card course-card--blue">
    <span>《新闻采访与写作》实践作品</span>
    <span class="course-hint">点击查看完整内容 →</span>
  </a>
  <a href="./assets/course-03.jpg" target="_blank" class="course-card course-card--lilac">
    <span>看见幸福就“破防”——网络社会中的比较心理与幸福观</span>
    <span class="course-hint">点击查看完整内容 →</span>
  </a>
</div>
