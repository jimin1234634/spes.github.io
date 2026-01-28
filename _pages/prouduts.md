---
title: Products
permalink: /products/
layout: single
author_profile: false
---
<style>
  .product-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
  margin-top: 30px;
}

.product-card {
  border: 1px solid #e5e5e5;
  border-radius: 12px;
  padding: 16px;
  text-align: center;
  background: #fff;
}

.product-card img {
  width: 100%;
  border-radius: 10px;
  margin-bottom: 12px;
}

.product-card h3 {
  margin: 8px 0;
}

.product-btn {
  display: inline-block;
  margin-top: 10px;
  padding: 10px 16px;
  background: #000;
  color: #fff;
  border-radius: 20px;
  text-decoration: none;
  font-size: 14px;
}
</style>

<div class="product-grid">

  <div class="product-card">
    <img src="/assets/sample1.jpg" alt="상품 1">
    <h3>상품명 01</h3>
    <p>간단한 설명</p>
    <a class="product-btn" href="https://example.com" target="_blank">
      구매하기
    </a>
  </div>

</div>


