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
  display: none;
}
.section-heading {
  font-size: 2rem;
  font-weight: 600;
  text-transform: uppercase;
  margin-bottom: 40px;
  letter-spacing: 2px;
}
#contact .section-heading {
  margin-bottom: 10px;
}
#projects {
  background-image: url('/assets/img/akiaboutme.jpg');
  background-size: cover;
  background-position: center;
  padding: 60px 200px;
  margin: 0 -200px;
}
#about {
  background-image: url('/assets/img/mergedimage.png');
  background-size: cover;
  background-position: top;
  padding: 60px 200px;
  margin: 0 -200px;
}
#contact {
  background-image: url('/assets/img/mergedimage.png');
  background-size: cover;
  background-position: bottom;
  padding: 60px 200px;
  margin: 0 -200px;
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
  display: flex;
  flex-direction: column;
  gap: 30px;
  margin-top: 10px;
  max-width: 600px;
}
.contact-left h2 {
  text-transform: none;
  font-size: 13px;
  font-weight: 200;
  line-height: 1.8;
  text-align: left;
  max-width: 100%;
  margin-top: 0;
  margin-bottom: 0;
}
.contact-right {
  width: 100%;
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
  <h2 class="section-heading">Projects</h
