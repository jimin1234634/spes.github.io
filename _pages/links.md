---
layout: default
title: Links
permalink: /links/
---

<style>
/* ===== HERO ===== */
.links-hero {
  position: relative;
  height: 100vh;
  background: url("/assets/images/hero-lake.jpg") center / cover no-repeat;
  display: flex;
  align-items: center;
  justify-content: center;
}

/* 어두운 오버레이 */
.links-hero::before {
  content: "";
  position: absolute;
  inset: 0;
  background: rgba(0,0,0,0.35);
  z-index: 1;
}

/* 중앙 텍스트 */
.links-hero-content {
  position: relative;
  z-index: 2;
  text-align: center;
  color: white;
}

.links-hero-content h1 {
  letter-spacing: 0.25em;
  font-size: 1.6rem;
  margin-bottom: 32px;
}

/* ===== 버튼 ===== */
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

/* ===== 상단바 (메인과 동일하게) ===== */
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

/* 모바일 */
@media (max-width: 768px) {
  .links-hero-content h1 {
    font-size: 1.2rem;
    letter-spacing: 0.18em;
  }

  .link-btn {
    padding: 12px 28px;
    font-size: 0.75rem;
  }
}
</style>

<section class="links-hero">
  <div class="links-hero-content">
    <h1>LINKS</h1>

    <a class="link-btn" href="https://instagram.com/might.take" target="_blank">
      📷 INSTAGRAM
    </a>
  </div>
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
