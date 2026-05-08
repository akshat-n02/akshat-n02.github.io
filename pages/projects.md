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
.section-divider {
  border: none;
  border-top: 1px solid #eee;
  margin: 80px 0;
}
.section-heading {
  font-size: 2rem;
  font-weight: 900;
  text-transform: uppercase;
  margin-bottom: 40px;
  letter-spacing: 2px;
}
.about-section {
  max-width: 700px;
  font-size: 15px;
  line-height: 1.8;
  font-weight: 200;
  text-transform: none;
}
.about-section p {
  margin-bottom: 20px;
  text-transform: none;
}
.contact-wrapper {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 60px;
  margin-top: 40px;
  align-items: center;
}
.contact-left h2 {
  text-transform: none;
  font-size: 24px;
  font-weight: 200;
  margin-bottom: 24px;
  line-height: 1.3;
}
.contact-right form {
  display: flex;
  flex-direction: column;
  gap: 16px;
}
.contact-right input,
.contact-right textarea {
  width: 100%;
  padding: 12px 0;
  border: none;
  border-bottom: 1px solid #333;
  background: transparent;
  font-size: 14px;
  font-family: inherit;
  outline: none;
  box-sizing: border-box;
  text-transform: none;
}
.contact-right textarea {
  height: 120px;
  resize: none;
}
.contact-right button {
  margin-top: 8px;
  padding: 14px;
  background: #000;
  color: #fff;
  border: none;
  font-size: 13px;
  font-family: inherit;
  letter-spacing: 2px;
  cursor: pointer;
  text-transform: uppercase;
}
.contact-right button:hover {
  background: #333;
}
</style>

<div id="projects">
  <p class="projects-intro">Hello hello helloooo here i talk about myself.</p>
  <div class="row-3">
    <a href="/projects/MONOM/" class="project-card">
      <div class="placeholder centered" style="background-image: url('/assets/img/MONOMbg.jpg');">
        <img src="/assets/img/monomlogo.jpg" alt="MONOM logo" style="width: 40%;">
      </div>
    </a>
    <a href="/projects/4DSOUND/" class="project-card">
      <div class="placeholder centered" style="background-image: url('/assets/img/4dsoundbg.png');">
        <img src="/assets/img/4dsoundlogo.png" alt="4DSOUND logo" style="width: 90%;">
      </div>
    </a>
    <a href="/projects/DDOCK/" class="project-card">
      <div class="placeholder centered" style="background-image: url('/assets/img/DB55');">
        <img src="/assets/img/logo-d-dock.png" alt="D/DOCK logo" style="width: 50%; filter: invert(1);">
      </div>
    </a>
  </div>
</div>

<hr class="section-divider">

<div id="about">
  <h2 class="section-heading">About Me</h2>
  <div class="about-section">
    <p>Hi, I'm Akshat, born in the US
