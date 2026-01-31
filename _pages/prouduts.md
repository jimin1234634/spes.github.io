---
layout: default
title: Products
permalink: /products/
---

<style>
/* ===== Products Page ===== */
.products {
  max-width: 1100px;
  margin: 120px auto 160px;
  padding: 0 24px;
}

.products h1 {
  text-align: center;
  letter-spacing: 0.2em;
  margin-bottom: 80px;
}

/* Grid */
.products-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 48px;
}

/* Card */
.product-card {
  text-align: center;
}

.product-card img {
  width: 100%;
  aspect-ratio: 4 / 5;
  object-fit: cover;
  margin-bottom: 20px;
}

.product-name {
  font-size: 0.9rem;
  letter-spacing: 0.12em;
  margin-bottom: 8px;
}

.product-desc {
  font-size: 0.75rem;
  opacity: 0.7;
  margin-bottom: 18px;
}

/* Button */
.product-btn {
  display: inline-block;
  padding: 10px 28px;
  font-size: 0.7rem;
  letter-spacing: 0.2em;
  border: 1px solid #111;
  transition: all 0.3s ease;
}

.product-btn:hover {
  background: #111;
  color: #fff;
}
</style>

<section class="products-section">
  <div class="products-grid">

    <div class="product-card">
      <img src="{{ '/assets/images/sample1.jpg' | relative_url }}" alt="">
      <h3>PRODUCT 01</h3>
      <p>Brief description</p>
      <a class="btn" href="#">VIEW</a>
    </div>

    <div class="product-card">
      <img src="{{ '/assets/images/sample2.jpg' | relative_url }}" alt="">
      <h3>PRODUCT 02</h3>
      <p>Brief description</p>
      <a class="btn" href="#">VIEW</a>
    </div>

    <div class="product-card">
      <img src="{{ '/assets/images/sample3.jpg' | relative_url }}" alt="">
      <h3>PRODUCT 03</h3>
      <p>Brief description</p>
      <a class="btn" href="#">VIEW</a>
    </div>

  </div>
</section>
