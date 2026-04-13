---
layout: default
title: 
permalink: /projects/
---

<style>
.projects-intro {
  margin-bottom: 40px;
  font-size: 15px;
  line-height: 1.7;
}
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
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
  background-size: cover;
  background-position: center;
  overflow: hidden;
}
.project-card .placeholder.centered::after {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.2);
}
.project-card .placeholder.centered img {
  height: auto;
  display: block;
  margin: auto !important;
  position: relative;
  z-index: 1;
}
</style>

<p class="projects-intro">Hello hello helloooo here i talk about myself.</p>

<div class="row-3">
  <a href="/projects/project1/" class="project-card">
    <div class="placeholder centered" style="background-image: url('/assets/img/MONOMbg.jpg');">
      <img src="/assets/img/monomlogo.jpg" alt="MONOM logo" style="width: 40%;">
    </div>
  </a>
  <a href="/projects/project2/" class="project-card">
    <div class="placeholder centered" style="background-image: url('/assets/img/4dsoundbg.png');">
      <img src="/assets/img/4dsoundlogo.png" alt="4DSOUND logo" style="width: 90%;">
    </div>
  </a>
  <a href="/projects/project3/" class="project-card">
    <div class="placeholder centered" style="background-image: url('/assets/img/DB55');">
      <img src="/assets/img/logo-d-dock.png" alt="D/DOCK logo" style="width: 50%; filter: invert(1);">
    </div>
  </a>
</div>
