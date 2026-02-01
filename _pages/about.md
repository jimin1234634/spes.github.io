---
layout: default
title: About
permalink: /about/
---

<style>
/* ===== About Hero ===== */
.about-hero {
  height: 60vh;
  background: url("/assets/images/hero-ad.jpg") center / cover no-repeat;
  position: relative;
  display: flex;
  align-items: center;
  justify-content: center;
}

.about-hero::before {
  content: "";
  position: absolute;
  inset: 0;
  background: rgba(0,0,0,0.35);
}

.about-hero h1 {
  position: relative;
  z-index: 2;
  color: white;
  font-size: 1.6rem;
  letter-spacing: 0.3em;
}

/* ===== About Content ===== */
.about-section {
  max-width: 760px;
  margin: 120px auto 160px;
  padding: 0 24px;
  text-align: center;
}

.about-section p {
  font-size: 0.85rem;
  line-height: 2;
  letter-spacing: 0.05em;
  margin-bottom: 32px;
  opacity: 0.85;
}

/* 상품 키워드 */
.about-products {
  margin: 80px 0;
}

.about-products span {
  display: inline-block;
  margin: 8px 14px;
  font-size: 0.7rem;
  letter-spacing: 0.2em;
  opacity: 0.6;
}

/* 마무리 문장 */
.about-quote {
  margin-top: 80px;
  font-size: 0.75rem;
  letter-spacing: 0.15em;
  opacity: 0.6;
}

/* 모바일 */
@media (max-width: 768px) {
  .about-hero h1 {
    font-size: 1.2rem;
  }

  .about-section {
    margin: 80px auto 120px;
  }
}
</style>

<!-- ===== Hero ===== -->
<section class="about-hero">
  <h1>ABOUT</h1>
</section>

<!-- ===== Content ===== -->
<section class="about-section">

  <p>
    Spiritus et Spes는  
    일상 속에서 반복적으로 손에 쥐고, 들고, 마주하게 되는 물건에  
    이미지와 문장을 더하는 브랜드입니다.
  </p>
 

  <p>
    Spiritus et Spes의 제품들은  
    특별한 날을 위한 물건이 아니라,  
    평범한 하루 곁에 조용히 놓이는 것을 목표로 합니다.
  </p>

  <p class="about-quote">
    Faith, Image, and Quiet Hope
  </p>

</section>
