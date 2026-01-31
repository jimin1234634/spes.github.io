---
layout: default
title: Links
permalink: /links/
---

<style>
/* ===== Links Hero ===== */
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

/* 중앙 콘텐츠 */
.links-hero-content {
  position: relative;
  z-index: 2;
  text-align: center;
  color: white;
}

.links-hero-content h1 {
  font-size: 1.4rem;
  letter-spacing: 0.25em;
  margin-bottom: 28px;
}

/* 링크 버튼 */
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

/* 모바일 */
@media (max-width: 768px) {
  .links-hero-content h1 {
    font-size: 1.1rem;
    letter-spacing: 0.18em;
  }

  .link-btn {
    padding: 12px 28px;
    font-size: 0.75rem;
  }
}

  /* ===== 기본 마크다운 제목 & 링크 색 제거 ===== */
main h1,
main h2,
main h3 {
  color: #111;
  text-decoration: none;
}

main a {
  color: #111;
  text-decoration: none;
}

main a:visited {
  color: #111;
}

main a:hover {
  text-decoration: underline;
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
