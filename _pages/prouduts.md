---
layout: default
title: Products
permalink: /products/
---

<style>
.products-section {
  padding: 120px 8vw;
}

.products-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 80px;
  align-items: start;
}

.product-card {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
}

/* 이미지 영역 */
.product-card img {
  width: 100%;
  max-width: 320px;
  height: 220px;
  object-fit: cover;
  background: #eee; /* 이미지 없을 때 대비 */
  margin-bottom: 32px;
}

/* 제목 */
.product-card h3 {
  font-size: 0.9rem;
  letter-spacing: 0.2em;
  margin-bottom: 10px;
}

/* 설명 */
.product-card p {
  font-size: 0.75rem;
  opacity: 0.7;
  margin-bottom: 18px;
}

/* 버튼 */
.product-card .btn {
  display: inline-block;
  padding: 8px 28px;
  border: 1px solid #111;
  font-size: 0.7rem;
  letter-spacing: 0.15em;
  text-decoration: none;
  color: #111;
}

.product-card .btn:hover {
  background: #111;
  color: #fff;
}
</style>

<section class="products-section">
  <div class="products-grid">

    <div class="product-card">
      <img src="/assets/images/sample1.jpg" alt="">
      <h3>PRODUCT 01</h3>
      <p>Brief description</p>
      <a class="btn" href="#">VIEW</a>
    </div>

    <div class="product-card">
      <img src="/assets/images/sample1.jpg" alt="">
      <h3>PRODUCT 02</h3>
      <p>Brief description</p>
      <a class="btn" href="#">VIEW</a>
    </div>

    <div class="product-card">
      <img src="/assets/images/sample1.jpg" alt="">
      <h3>PRODUCT 03</h3>
      <p>Brief description</p>
      <a class="btn" href="#">VIEW</a>
    </div>

  </div>
</section>
