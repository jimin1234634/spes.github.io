---
layout: page
title: "Spiritus et Spes"
excerpt: "빠르게 흐르는 일상 속에서, 잠시 숨을 고릅니다."
faginate: false
header:
  overlay_image: /assets/images/hero-rock.jpg
  overlay_filter: 0.45
  caption: "© Spiritus et Spes"
---

<div class="fade-up">
  빠르게 흘러가는 일상 속에서  
  잠시 멈추어 한 모금 쉬어가는 순간을 담습니다.
</div>

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

<script>
document.addEventListener("scroll", () => {
  document.querySelectorAll(".fade-up").forEach(el => {
    const rect = el.getBoundingClientRect();
    if (rect.top < window.innerHeight - 100) {
      el.classList.add("show");
    }
  });
});
</script>
