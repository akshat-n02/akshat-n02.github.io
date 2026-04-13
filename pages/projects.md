---
layout: default
title: 
permalink: /projects/
---

<style>
.row-3 {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  gap: 16px;
}
.project-card {
  text-decoration: none;
  color: inherit;
}
.project-card .placeholder {
  width: 100%;
  height: 500px;
  background-color: #222;
  border: 1px solid #555;
}
.project-card .placeholder.centered {
  background-image: url('/assets/img/DB55');
  background-size: cover;
  background-position: center;
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
}
.project-card .placeholder.centered::after {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.5);
}
.project-card .placeholder.centered img {
  width: 60%;
  height: auto;
  filter: invert(1);
  display: block;
  margin: auto !important;
  position: relative;
  z-index: 1;
}
.project-card p {
  margin: 8px 0 16px 0;
  font-size: 14px;
}
</style>

<div class="row-3">
  <a href="/projects/project1/" class="project-card">
    <div class="placeholder"></div>
    <p>Project One Title</p>
  </a>
  <a href="/projects/project2/" class="project-card">
    <div class="placeholder"></div>
    <p>Project Two Title</p>
  </a>
  <a href="/projects/project3/" class="project-card">
    <div class="placeholder centered">
      <img src="/assets/img/logo-d-dock.png" alt="D/DOCK logo">
    </div>
    <p>D/DOCK</p>
  </a>
</div>
