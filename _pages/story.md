---
title: Our Story
permalink: /story/
layout: single
author_profile: false
---

<style>
.fade-up {
  opacity: 0;
  transform: translateY(30px);
  transition: opacity 0.8s ease, transform 0.8s ease;
}
.fade-up.show {
  opacity: 1;
  transform: translateY(0);
}
</style>

<div class="fade-up">
빠르게 흘러가는 일상 속에서  
잠시 멈추어 한 모금 쉬어가는 순간을 담습니다.
</div>

<div class="fade-up" style="margin-top:40px;">
숨을 고르고,  
다시 시작할 수 있도록.
</div>

<script>
document.addEventListener("DOMContentLoaded", () => {
  const items = document.querySelectorAll(".fade-up");

  const observer = new IntersectionObserver(entries => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.classList.add("show");
      }
    });
  }, { threshold: 0.2 });

  items.forEach(el => observer.observe(el));
});
</script>
