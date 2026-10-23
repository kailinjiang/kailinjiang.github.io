<style>
/* 正文内链接文字加粗（仅本页主内容区，不含侧边栏） */
.page__content a {
  font-weight: 700;
}

.entity-mention {
  display: inline-flex;
  align-items: center;
  gap: 4px;
  color: var(--entity-color);
  background: var(--entity-bg);
  border-radius: 4px;
  padding: 1px 6px;
  vertical-align: middle;
  white-space: nowrap;
  -webkit-box-decoration-break: clone;
  box-decoration-break: clone;
}

.entity-logo {
  width: 1em;
  height: 1em;
  margin: 0;
  flex: 0 0 auto;
  object-fit: contain;
  box-shadow: none !important;
}

.entity-mention:hover {
  background: var(--entity-hover-bg);
  box-shadow: 0 0 8px var(--entity-glow), 0 0 16px var(--entity-glow-soft);
}

.entity-link,
.entity-link:hover {
  text-decoration: none !important;
  border-bottom: none !important;
}
</style>

<div>
<a href="https://kailinjiang.github.io/">
  <img 
    src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:D22229,100:2B4FA3&text=Hi%2C%20I'm%20Kailin%20Jiang%2C%20%E8%92%8B%E5%87%AF%E6%9E%97&reversal=false&fontSize=40&fontAlignY=40&fontColor=FFFFFF" 
    alt="Hi, I'm Kailin Jiang, 蒋凯林" 
    style="width: 100%; height: auto;"
  >
</a>
</div>

---



<style>
.activities-scroll { 
  max-height: 300px; 
  overflow-y: auto; 
  padding: 8px 6px; 
  border: 1px solid #eaeaea; 
  border-radius: 12px; 
  background: #fff; 
  box-shadow: inset 0 1px 0 rgba(255,255,255,0.6), 0 6px 14px rgba(0,0,0,0.04); 
}
.activities-scroll::-webkit-scrollbar { width: 8px; }
.activities-scroll::-webkit-scrollbar-thumb { background: #ddd; border-radius: 4px; }
.activities-container { 
  display: flex; 
  flex-wrap: wrap; 
  justify-content: space-between; 
  gap: 15px; 
}
.activities-item { 
  flex: 0 0 calc(32.5% - 10px); 
  text-align: center; 
  min-width: 0;
}
.activities-item p {
  font-size: 0.88em;
  color: #666;
  margin: 0;
  font-weight: bold;
  line-height: 1.2;
  white-space: nowrap;
}
@media (max-width: 768px) {
  .activities-item { flex: 0 0 100%; }
  .activities-item p { white-space: normal; }
}
/* 活动多图：横向自动来回切换（两张及以上均支持；两张时为来回，三张及以上顺序循环） */
.activities-img-slide-view {
  position: relative;
  width: 100%;
  overflow: hidden;
  border-radius: 8px;
  margin-bottom: 10px;
  height: 200px;
  background: #f3f3f3;
}
.activities-img-slide-track {
  display: flex;
  height: 100%;
  will-change: transform;
}
.activities-img-slide-track img {
  height: 100%;
  object-fit: cover;
  display: block;
  min-width: 0;
}
/* 两张图：每张占轨道宽度的一半（轨道为视区 200%） */
.activities-img-slide-view[data-slide-count="2"] .activities-img-slide-track img {
  flex: 0 0 50%;
  width: 50%;
}
/* 两张图：轨道宽度 200%，keyframes 在 0% 与 100% 间来回 */
.activities-img-slide-view[data-slide-count="2"] .activities-img-slide-track {
  width: 200%;
  animation: activities-slide-2 6s ease-in-out infinite;
}
@keyframes activities-slide-2 {
  0%, 42% { transform: translateX(0); }
  50%, 92% { transform: translateX(-50%); }
  100% { transform: translateX(0); }
}
/* 三张及以上：轨道宽度与 JS 轮播；无 JS 时静止在第一张 */
.activities-img-slide-view[data-slide-count]:not([data-slide-count="2"]) .activities-img-slide-track {
  width: calc(var(--slide-n, 3) * 100%);
  transition: transform 0.55s ease-in-out;
}
.activities-img-slide-view[data-slide-count]:not([data-slide-count="2"]) .activities-img-slide-track img {
  flex: 0 0 calc(100% / var(--slide-n, 3));
}
@media (prefers-reduced-motion: reduce) {
  .activities-img-slide-view[data-slide-count="2"] .activities-img-slide-track {
    animation: none !important;
    transform: none !important;
  }
  .activities-img-slide-view[data-slide-count]:not([data-slide-count="2"]) .activities-img-slide-track {
    transition: none !important;
    transform: none !important;
  }
}
</style>






<div class="activities-scroll">
  <div class="activities-container">
    {% for item in site.data.activities %}
    <div class="activities-item">
      {% if item.images and item.images.size > 1 %}
      <div class="activities-img-slide-view" data-slide-count="{{ item.images.size }}" data-slide-interval="4000"{% if item.images.size > 2 %} style="--slide-n: {{ item.images.size }};"{% endif %} role="img" aria-label="{{ item.alt | default: 'Activity photos' }}">
        <div class="activities-img-slide-track">
          {% for img in item.images %}
          <img src="{{ img | relative_url }}" alt="" loading="{% if forloop.first %}eager{% else %}lazy{% endif %}">
          {% endfor %}
        </div>
      </div>
      {% elsif item.images and item.images.size == 1 %}
      <img src="{{ item.images[0] | relative_url }}" alt="{{ item.alt | default: 'Activity' }}" style="display: block; margin-bottom: 10px; width: 100%; height: 200px; object-fit: cover; border-radius: 8px;">
      {% else %}
      <img src="{{ item.image | relative_url }}" alt="{{ item.alt | default: 'Activity' }}" style="display: block; margin-bottom: 10px; width: 100%; height: 200px; object-fit: cover; border-radius: 8px;">
      {% endif %}
      <p>{% if item.link %}<a href="{{ item.link }}" target="_blank" rel="noopener noreferrer">{{ item.link_text }}</a> {{ item.suffix }}{% else %}{{ item.text }}{% endif %}</p>
    </div>
    {% endfor %}
  </div>
</div>
<script>
(function () {
  if (window.matchMedia("(prefers-reduced-motion: reduce)").matches) return;
  document.querySelectorAll(".activities-img-slide-view[data-slide-count]").forEach(function (view) {
    var n = parseInt(view.getAttribute("data-slide-count"), 10);
    if (n <= 2) return;
    var track = view.querySelector(".activities-img-slide-track");
    if (!track) return;
    var ms = parseInt(view.getAttribute("data-slide-interval") || "4000", 10);
    var i = 0;
    setInterval(function () {
      i = (i + 1) % n;
      track.style.transform = "translateX(calc(-100% * " + i + " / " + n + "))";
    }, ms);
  });
})();
</script>
<div style="margin-top: 5px; font-size: small; margin-bottom: 0px;">⬆ Scrollable</div>

<br>
