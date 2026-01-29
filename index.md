---
layout: splash
title: Spiritus et Spes
excerpt: 빠르게 흐르는 일상 속에서 잠시 멈추어 숨을 고릅니다.
---

<style>
.main-visual {
  position: relative;
  width: 100%;
  max-height: 90vh;
  overflow: hidden;
}

.main-visual img {
  width: 100%;
  height: 90vh;
  object-fit: cover;
  display: block;
}

.main-text {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  text-align: center;
  color: white;
}

.main-text h1 {
  font-size: 3rem;
  margin-bottom: 12px;
}

.main-text p {
  font-size: 1.2rem;
  line-height: 1.6;
}
</style>




<div class="main-visual">
  <img src="/assets/images/hero-rock.jpg" alt="main image">

  <div class="main-text">
    <h1>Spiritus et Spes</h1>
    <p>빠르게 흐르는 일상 속에서<br>잠시 멈추어 숨을 고릅니다.</p>
  </div>
</div>

/* Stardom 폰트 등록 */
@font-face {
  font-family: 'Stardom-Regular';
  src: url('/assets/fonts/stardom/Stardom-Regular.woff2') format('woff2'),
       url('/assets/fonts/stardom/Stardom-Regular.woff') format('woff'),
       url('/assets/fonts/stardom/Stardom-Regular.ttf') format('truetype');
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}

/* 기본 폰트 설정 (한글은 시스템, 영문은 Stardom) */
body {
  font-family: system-ui, -apple-system, BlinkMacSystemFont,
               'Apple SD Gothic Neo', 'Noto Sans KR',
               'Malgun Gothic', sans-serif;
}

/* 타이틀에 Stardom 적용 */
h1, .hero-title {
  font-family: 'Stardom-Regular', serif;
  letter-spacing: 0.02em; /* 감성 살짝 */
}
