---
layout: default
title: Home
permalink: /index.html
---

<section class="hero">
  <div class="profile">
    <img
      src="{{ '/assets/profile.JPG' | relative_url }}"
      alt="Kazbek Hashimov — profile photo"
      loading="lazy"
      style="width:100%;height:100%;object-fit:cover;display:block"
    />
  </div>
  <div class="summary">
    <h1>Kazbek Hashimov</h1>
    <p>I’m an Information Technology student at ADA University building my skills in programming and problem-solving. I’ve completed the CS50 course and developed a logic-gates simulator as my first project. This site is where I share what I’m learning and the work I create along the way.</p>
    <p style="margin-top:12px">
      <a class="btn" href="{{ '/projects.html' | relative_url }}">See Projects</a>
    </p>
  </div>
</section>

<section class="section">
  <h2>Featured Project</h2>
  <div class="card">
    <img src="{{ '/assets/project1.jpg' | relative_url }}" alt="Project 1 screenshot">
    <h3>Project 1 — Building Logic Gates</h3>
    <p>We built a logic-gate system as a team of four, implementing OR, AND, NOT, XOR, and NAND gates and showing how they interact to form basic digital logic. The project helped us understand how these fundamental components operate and connect. You can learn more about it by clicking the “See Projects” button above.</p>
  </div>
</section>