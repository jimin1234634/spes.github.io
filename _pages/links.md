---
layout: default
title: Links
permalink: /links/
---

<style>
/* ===== HERO ===== */
.page-hero {
  height: 70vh;
  background: url("/assets/images/hero-lake.jpg") center / cover no-repeat;
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
}

.page-hero::after {
  content: "";
  position: absolute;
  inset: 0;
  background: rgba(0,0,0,0.25);
}

.page-hero-inner {
  position: relative;
  z-index: 2;
  text-align: center;
  color: white;
}

.page-hero-inner h1 {
  letter-spacing: 0.25em;
  font-size: 2rem;
}

/* ===== TOP BAR (메인과 동일) ===== */
.top-bar {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 56px;
  background: rgba(255,255,255,0);
  transition: background 0.3s ease, backdrop-filter 0.3s ease;
  z-index: 100;
}

.top-bar.scrolled {
  background: rgba(255,255,255,0.9);
  backdrop-filter: blur(6px);
}

/* ===== LINKS SECTION ===== */
.links-section {
  padding: 120px 20px;
  text-align: center;
}

.link-btn {
  display: inline-block;
  padding: 14px 40px;
  border: 1px solid #111;
  text-decoration: none;
  color: #111;
  letter-spacing: 0.15em;
  transition: all 0.3s ease;
}

.link-btn:hover {
  background: #111;
  color: #fff;
}
</style>

<section class="page-hero">
  <div class="page-hero-inner">
    <h1>LINKS</h1>
  </div>
</section>

<section class="links-section">
  <a class="link-btn" href="https://instagram.com" target="_blank">
    Instagram
  </a>
</section>

<script>
  const topBar = document.querySelector('.top-bar');
  window.addEventListener('scroll', () => {
    if (window.scrollY > 50) {
      topBar.classList.add('scrolled');
    } else {
      topBar.classList.remove('scrolled');
    }
  });
</script>
