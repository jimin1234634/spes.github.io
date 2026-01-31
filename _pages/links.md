---
layout: default
title: Links
permalink: /links/
---

<style>
.links-hero {
  position: relative;
  height: 100vh;
  background: url("/assets/images/hero-lake.jpg") center / cover no-repeat;
  display: flex;
  align-items: center;
  justify-content: center;
}

.links-hero::before {
  content: "";
  position: absolute;
  inset: 0;
  background: rgba(0,0,0,0.35);
}

.links-hero-content {
  position: relative;
  text-align: center;
  color: white;
}

.links-hero-content h1 {
  letter-spacing: 0.25em;
  font-size: 1.6rem;
  margin-bottom: 32px;
}

.link-btn {
  display: inline-flex;
  align-items: center;
  gap: 10px;
  padding: 14px 40px;
  border: 1px solid rgba(255,255,255,0.7);
  color: white;
  text-decoration: none;
  letter-spacing: 0.15em;
  font-size: 0.8rem;
  transition: all 0.3s ease;
}

.link-btn:hover {
  background: white;
  color: #111;
}
</style>

<section class="links-hero">
  <div class="links-hero-content">
    <h1>LINKS</h1>
    <a class="link-btn" href="https://instagram.com/midnight.take" target="_blank">
      📷 INSTAGRAM
    </a>
  </div>
</section>
