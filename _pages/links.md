---
layout: default
title: Links
---

<style>
/* LINKS HERO */
.links-hero {
  height: 100vh;
  background: url("/assets/images/hero-rock.jpg") center / cover no-repeat;
  display: flex;
  align-items: center;
  justify-content: center;
}

.links-hero-text {
  text-align: center;
}

.links-hero-text h1 {
  color: white;
  letter-spacing: 0.25em;
  background: rgba(0,0,0,0.35);
  padding: 20px 36px;
}

.links-hero-text p {
  margin-top: 12px;
  font-size: 0.75rem;
  letter-spacing: 0.15em;
  color: white;
  opacity: 0.85;
}

/* 버튼 */
.hero-btn {
  display: inline-block;
  margin-top: 28px;
  padding: 10px 28px;
  font-size: 0.75rem;
  letter-spacing: 0.2em;
  color: white;
  text-decoration: none;
  border: 1px solid rgba(255,255,255,0.6);
  background: transparent;
  transition: all 0.3s ease;
}

.hero-btn:hover {
  background: white;
  color: #111;
}

/* 모바일 */
@media (max-width: 768px) {
  .links-hero-text h1 {
    font-size: 1.1rem;
    padding: 16px 24px;
  }
}
</style>

<section class="links-hero">
  <div class="links-hero-text">
    <h1>LINKS</h1>
    <p>Faith, Image, and Quiet Hope</p>

    <a
      href="https://instagram.com/계정명"
      target="_blank"
      class="hero-btn"
    >
      Instagram
    </a>
  </div>
</section>
