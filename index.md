---
layout: splash
author_profile: false
title: "Spiritus et Spes"
tagline: "Breath, Sip, Begin again"
header:
  overlay_image: /profile.png
  overlay_color: "#000000"
  overlay_filter: "0.6"
---
빠르게 흘러가는 일상 속에서 
잠시 멈추어 한 모금 쉬어가는 순간을 담습니다. 

---
layout: home
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

<script>
document.addEventListener("DOMContentLoaded", () => {
  const elements = document.querySelectorAll(".fade-up");

  const observer = new IntersectionObserver(entries => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.classList.add("show");
      }
    });
  }, { threshold: 0.15 });

  elements.forEach(el => observer.observe(el));
});
</script>
