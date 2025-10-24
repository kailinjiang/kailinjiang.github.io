---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>
# 😊 About me

I am an upcoming joint **PhD student** at **the State Key Laboratory of General Artificial Intelligence** <a href='https://www.bigai.ai/'>(BIGAI)</a> and **the University of Science and Technology of China** (USTC), supervised by <a href='https://liqing.io/'>Qing Li(BIGAI, 李庆)</a>, <a href='https://yuntaodu.github.io/'>Yuntao Du(SDU, 杜云涛)</a>, <a href='https://siyuanqi.github.io/'>Siyuan Qi (Gyges Labs, 綦思源)</a> and <a href='http://staff.ustc.edu.cn/~binli/'>Bin Li (USTC, 李斌)</a>, <a href='https://faculty.ustc.edu.cn/liulei13/zh_CN/index.htm'>Lei Liu (USTC, 刘磊)</a>. Currently, I am doing my internship in State Key Laboratory of General Artificial Intelligence.


I am currently working on knowledge editing, knowledge injection, multimodal learning, continual learning, <a href='https://scholar.google.com/citations?user=NSHQsrAAAAAJ'><img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2FKailinJiang%2Fkailinjiang.github.io@google-scholar-stats%2Fgs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations">


My huggingface at 🤗 [Huggingface home](https://huggingface.co/kailinjiang).





# 🔥 News



<style>
/* News section scroll window styles (scoped) */
.news .scroll-window { max-height: 640px; overflow-y: auto; padding: 8px 6px; border: 1px solid #eaeaea; border-radius: 12px; background: #fff; box-shadow: inset 0 1px 0 rgba(255,255,255,0.6), 0 6px 14px rgba(0,0,0,0.04); }
.news .scroll-window::-webkit-scrollbar { width: 8px; }
.news .scroll-window::-webkit-scrollbar-thumb { background: #ddd; border-radius: 4px; }
</style>



<div class="news" markdown="1">
<div class="scroll-window" markdown="1">
- **2025.09**: &nbsp;🎉🎉 I will serve as **Reviewer** in ICLR 2026！
- **2025.03**: &nbsp;🎉🎉 One paper have been accepted by **ICLR 2025 Workshop SSI-FM**! <a href='https://mmke-bench-iclr.github.io/'>Multimodal Knowledge Editing</a>！
- **2025.01**: &nbsp;🎉🎉 Two paper have been accepted by **ICLR 2025**! <a href='https://arxiv.org/pdf/2406.11194'>In Context Editing</a> and <a href='https://mmke-bench-iclr.github.io/'>Multimodal Knowledge Editing</a>！
- **2024.09**: &nbsp;🎉🎉 I joined the **IIP Lab** at the University of Science and Technology of China to pursue a doctoral degree！
- **2024.06**: &nbsp;🎉🎉 I successfully completed my undergraduate studies from the College of Science of Sichuan Agricultural University!
- **2024.02**: &nbsp;📣📣 I will go to the State Key Laboratory of General Artificial Intelligence <a href='https://www.bigai.ai/'>(BIGAI)</a> to start my internship!

</div>
</div>

<script>
(function() {
  function setNewsScrollWindowHeight() {
    var container = document.querySelector('.news .scroll-window');
    if (!container) return;
    var firstLi = container.querySelector('li');
    if (!firstLi) return; // fallback to CSS default max-height
    var liRect = firstLi.getBoundingClientRect();
    var liStyle = window.getComputedStyle(firstLi);
    var marginTop = parseFloat(liStyle.marginTop) || 0;
    var marginBottom = parseFloat(liStyle.marginBottom) || 0;
    var perItem = liRect.height + (marginTop + marginBottom);
    var target = perItem * 9; // show ~9 items
    container.style.maxHeight = target + 'px';
  }
  function onReady(fn) {
    if (document.readyState === 'loading') {
      document.addEventListener('DOMContentLoaded', fn, { once: true });
    } else { fn(); }
  }
  onReady(setNewsScrollWindowHeight);
  var resizeTimeout;
  window.addEventListener('resize', function() {
    clearTimeout(resizeTimeout);
    resizeTimeout = setTimeout(setNewsScrollWindowHeight, 150);
  });
})();
</script>




# 📝 Publications
*: Co-First Author, Equal Contribution

<div style="display: flex; justify-content: center; gap: 20px;">
  <div style="display: flex; align-items: center;">
    <img src="./images/conference/ICLR.png" alt="ICLR" style="width: 150px; height: 45px;">
    <span style="margin-left: 10px; font-size: 20px; font-weight: bold; color: #8B4513;">×2</span>
  </div>
  <div style="display: flex; align-items: center;">
    <img src="./images/conference/blank.png" alt="ICLR" style="width: 150px; height: 45px;">
    <span style="margin-left: 10px; font-size: 20px; font-weight: bold; color: #8B4513;"></span>
  </div>
  <div style="display: flex; align-items: center;">
    <img src="./images/conference/blank.png" alt="ICLR" style="width: 150px; height: 45px;">
    <span style="margin-left: 10px; font-size: 20px; font-weight: bold; color: #8B4513;"></span>
  </div>
  <div style="display: flex; align-items: center;">
    <img src="./images/conference/blank.png" alt="ICLR" style="width: 150px; height: 45px;">
    <span style="margin-left: 10px; font-size: 20px; font-weight: bold; color: #8B4513;"></span>
  </div>
  <div style="display: flex; align-items: center;">
    <img src="./images/conference/blank.png" alt="ICLR" style="width: 150px; height: 45px;">
    <span style="margin-left: 10px; font-size: 20px; font-weight: bold; color: #8B4513;"></span>
  </div>
</div>


<span class='anchor' id='conference-papers'></span>
## Conference papers

<style>
/* Conference papers section styles (scoped) */
.conference { font-family: "Times New Roman", Times, serif; font-size: 0.96em; }
.conference .bibliography { list-style: none; margin: 0; padding: 0; }
.conference .bibliography li { margin: 10px 0; }
.conference .pub-row {
  display: flex;
  gap: 12px;
  align-items: flex-start;
  background: #fff;
  border: 1px solid #eee;
  border-radius: 12px;
  padding: 14px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.06);
  max-width: 900px;
  margin-left: auto;
  margin-right: auto;
}
.conference .pub-row .abbr.pub-thumb {
  position: relative;
  flex: 0 0 320px;
  max-width: 320px;
  padding: 0 15px;
}
.conference .pub-row .abbr.pub-thumb img {
  display: block;
  width: 100%;
  height: auto;
  border-radius: 8px;
  box-shadow: 0 10px 16px rgba(0,0,0,0.12);
}
.conference .pub-row .abbr.pub-thumb .badge {
  position: absolute;
  top: -8px;
  left: -8px;
  background: #e74d3c;
  color: #fff;
  padding: 4px 8px;
  border-radius: 6px;
  font-weight: 700;
}
.conference .pub-content { flex: 1 1 auto; padding-left: 4px; }
.conference .title { font-size: 1.14rem; font-weight: 700; line-height: 1.35; }
.conference .author { font-size: 0.98rem; }
.conference .periodical { font-size: 0.96rem; }
.conference .conference-name { color: #8B0000; font-weight: bold; }
.conference .links a { font-size: 12px !important; }
.conference .links { margin-top: 10px; display: flex; gap: 10px; flex-wrap: wrap; }
.conference .pub-button {
  font-family: "Times New Roman", Times, serif;
  background: #fff;
  color: #333;
  border: 1px solid #ddd;
  border-radius: 0;
  padding: 8px 14px;
  font-size: 1rem;
  text-decoration: none;
  box-shadow: 0 4px 12px rgba(0,0,0,0.12);
  transition: transform .05s ease, box-shadow .2s ease, border-color .2s ease;
}
.conference .pub-button:hover {
  transform: translateY(-1px);
  box-shadow: 0 10px 18px rgba(0,0,0,0.16);
  border-color: #bbb;
  text-decoration: none;
}
.conference .title a { color: #2a72d4; text-decoration: none; }
.conference .title a:hover { text-decoration: underline; color: #1e5bb8; }
/* Scroll window to show only a few items initially */
.conference .scroll-window { max-height: 640px; overflow-y: auto; padding: 8px 6px; border: 1px solid #eaeaea; border-radius: 12px; background: #fff; box-shadow: inset 0 1px 0 rgba(255,255,255,0.6), 0 6px 14px rgba(0,0,0,0.04); }
.conference .scroll-window::-webkit-scrollbar { width: 8px; }
.conference .scroll-window::-webkit-scrollbar-thumb { background: #ddd; border-radius: 4px; }
@media (max-width: 640px) {
  .conference .pub-row { flex-direction: column; }
  .conference .pub-row .abbr.pub-thumb { max-width: 100%; flex-basis: auto; }
  .conference .scroll-window { max-height: 420px; }
}
</style>

<div class="conference" markdown="1">
<div class="scroll-window">
<ul class="bibliography">

{% for link in site.data.conference.main %}

<li>
<div class="pub-row">
  <div class="col-sm-3 abbr pub-thumb" style="position: relative;padding-right: 15px;padding-left: 15px;">
    {% if link.image %} 
    <img src="{{ link.image }}" class="teaser img-fluid z-depth-1" style="width: 100%; height: auto;">
    {% endif %}
    {% if link.conference_short %} 
    <abbr class="badge">{{ link.conference_short }}</abbr>
    {% endif %}
  </div>
  <div class="col-sm-9 pub-content" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title"><a href="{{ link.paper | default: '/404.html' }}">{{ link.title }}</a></div>
      <div class="author">{{ link.authors }}</div>
      <div class="periodical"><em class="conference-name">{{ link.conference }}</em>
      </div>
    <div class="links">
      {% if link.paper %}
        <a href="{{ link.paper }}" class="pub-button paper" role="button" target="_blank">Paper</a>
      {% endif %}
      {% if link.dataset %}
        <a href="{{ link.dataset }}" class="pub-button dataset" role="button" target="_blank">Dataset</a>
      {% endif %}
      {% if link.model %}
        <a href="{{ link.model }}" class="pub-button model" role="button" target="_blank">Model</a>
      {% endif %}
      {% if link.code %}
        <a href="{{ link.code }}" class="pub-button code" role="button" target="_blank">Code</a>
      {% endif %}
      {% if link.website %}
        <a href="{{ link.website }}" class="pub-button website" role="button" target="_blank">Website</a>
      {% endif %}
      {% if link.poster %}
        <a href="{{ link.poster }}" class="pub-button poster" role="button" target="_blank">Poster</a>
      {% endif %}
      {% if link.slides %}
        <a href="{{ link.slides }}" class="pub-button slides" role="button" target="_blank">Slides</a>
      {% endif %}
    </div>
</div>
</div>
</li>

{% endfor %}

</ul>
</div>
</div>

<script>
(function() {
  function setConferenceScrollWindowHeight() {
    var container = document.querySelector('.conference .scroll-window');
    if (!container) return;
    var firstLi = container.querySelector('.bibliography > li');
    var firstRow = container.querySelector('.pub-row');
    if (!firstRow || !firstLi) return;
    var rowRect = firstRow.getBoundingClientRect();
    var liStyle = window.getComputedStyle(firstLi);
    var marginTop = parseFloat(liStyle.marginTop) || 0;
    var marginBottom = parseFloat(liStyle.marginBottom) || 0;
    var perItem = rowRect.height + (marginTop + marginBottom);
  var target = perItem * 3.5; // show ~3.5 items
    container.style.maxHeight = target + 'px';
  }
  function onReady(fn) {
    if (document.readyState === 'loading') {
      document.addEventListener('DOMContentLoaded', fn, { once: true });
    } else { fn(); }
  }
  onReady(setConferenceScrollWindowHeight);
  var resizeTimeout;
  window.addEventListener('resize', function() {
    clearTimeout(resizeTimeout);
    resizeTimeout = setTimeout(setConferenceScrollWindowHeight, 150);
  });
})();
</script>


<span class='anchor' id='preprints'></span>
## Preprints

<style>
/* Section title with blue accent bar */
h2 {
  border-left: 4px solid #4285F4;
  padding-left: 12px;
  margin-left: -16px;
  color: #333;
}
/* Preprints section styles (scoped) */
.preprint { font-family: "Times New Roman", Times, serif; font-size: 0.96em; }
.preprint .bibliography { list-style: none; margin: 0; padding: 0; }
.preprint .bibliography li { margin: 10px 0; }
.preprint .pub-row {
  display: flex;
  gap: 12px;
  align-items: flex-start;
  background: #fff;
  border: 1px solid #eee;
  border-radius: 12px;
  padding: 14px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.06);
  max-width: 900px;
  margin-left: auto;
  margin-right: auto;
}
.preprint .pub-row .abbr.pub-thumb {
  position: relative;
  flex: 0 0 320px;
  max-width: 320px;
  padding: 0 15px; /* keep original padding intent */
}
.preprint .pub-row .abbr.pub-thumb img {
  display: block;
  width: 100%;
  height: auto;
  border-radius: 8px;
  box-shadow: 0 10px 16px rgba(0,0,0,0.12);
}
.preprint .pub-row .abbr.pub-thumb .badge {
  position: absolute;
  top: -8px;
  left: -8px;
  background: #e74d3c;
  color: #fff;
  padding: 4px 8px;
  border-radius: 6px;
  font-weight: 700;
}
.preprint .pub-content { flex: 1 1 auto; padding-left: 4px; }
.preprint .title { font-size: 1.14rem; font-weight: 700; line-height: 1.35; }
.preprint .author { font-size: 0.98rem; }
.preprint .periodical { font-size: 0.96rem; }
.preprint .links a { font-size: 12px !important; }
.preprint .links { margin-top: 10px; display: flex; gap: 10px; flex-wrap: wrap; }
.preprint .pub-button {
  font-family: "Times New Roman", Times, serif;
  background: #fff;
  color: #333;
  border: 1px solid #ddd;
  border-radius: 0;
  padding: 8px 14px;
  font-size: 1rem;
  text-decoration: none;
  box-shadow: 0 4px 12px rgba(0,0,0,0.12);
  transition: transform .05s ease, box-shadow .2s ease, border-color .2s ease;
}
.preprint .pub-button:hover {
  transform: translateY(-1px);
  box-shadow: 0 10px 18px rgba(0,0,0,0.16);
  border-color: #bbb;
  text-decoration: none;
}
.preprint .title a { color: #2a72d4; text-decoration: none; }
.preprint .title a:hover { text-decoration: underline; color: #1e5bb8; }
/* Scroll window to show only a few items initially */
.preprint .scroll-window { max-height: 640px; overflow-y: auto; padding: 8px 6px; border: 1px solid #eaeaea; border-radius: 12px; background: #fff; box-shadow: inset 0 1px 0 rgba(255,255,255,0.6), 0 6px 14px rgba(0,0,0,0.04); }
.preprint .scroll-window::-webkit-scrollbar { width: 8px; }
.preprint .scroll-window::-webkit-scrollbar-thumb { background: #ddd; border-radius: 4px; }
@media (max-width: 640px) {
  .preprint .pub-row { flex-direction: column; }
  .preprint .pub-row .abbr.pub-thumb { max-width: 100%; flex-basis: auto; }
  .preprint .scroll-window { max-height: 420px; }
}
</style>

<div class="preprint" markdown="1">
<div class="scroll-window">
<ul class="bibliography">

{% for link in site.data.preprint.main %}

<li>
<div class="pub-row">
  <div class="col-sm-3 abbr pub-thumb" style="position: relative;padding-right: 15px;padding-left: 15px;">
    {% if link.image %} 
    <img src="{{ link.image }}" class="teaser img-fluid z-depth-1" style="width: 100%; height: auto;">
    {% endif %}
    {% if link.conference_short %} 
    <abbr class="badge">{{ link.conference_short }}</abbr>
    {% endif %}
  </div>
  <div class="col-sm-9 pub-content" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title"><a href="{{ link.paper | default: '/404.html' }}">{{ link.title }}</a></div>
      <div class="author">{{ link.authors }}</div>
      <div class="periodical"><em class="conference-name">{{ link.conference }}</em>
      </div>
    <div class="links">
      <a href="{{ link.paper | default: '/404.html' }}" class="pub-button paper" role="button" target="_blank">Paper</a>
      <a href="{{ link.code | default: '/404.html' }}" class="pub-button code" role="button" target="_blank">Code</a>
      <a href="{{ link.website | default: '/404.html' }}" class="pub-button website" role="button" target="_blank">Website</a>
      {% if link.github_folks %} 
      <a target="_blank" href ="https://github.com/{{ link.github_stars }}"><img alt="GitHub forks" align="right" src="https://img.shields.io/github/forks/{{ link.github_folks }}?style=social"></a>
      {% endif %}
      {% if link.github_stars %} 
      <a target="_blank" href ="https://github.com/{{ link.github_stars }}"><img alt="GitHub stars" align="right" src="https://img.shields.io/github/stars/{{ link.github_stars }}?style=social"></a>
      {% endif %}
</div>
</div>
</div>
</li>



{% endfor %}

</ul>
</div>
</div>

<script>
(function() {
  function setScrollWindowHeight() {
    var container = document.querySelector('.preprint .scroll-window');
    if (!container) return;
    var firstLi = container.querySelector('.bibliography > li');
    var firstRow = container.querySelector('.pub-row');
    if (!firstRow || !firstLi) return;
    var rowRect = firstRow.getBoundingClientRect();
    var liStyle = window.getComputedStyle(firstLi);
    var marginTop = parseFloat(liStyle.marginTop) || 0;
    var marginBottom = parseFloat(liStyle.marginBottom) || 0;
    var perItem = rowRect.height + (marginTop + marginBottom);
  var target = perItem * 3.5; // show ~3.5 items
    container.style.maxHeight = target + 'px';
  }
  function onReady(fn) {
    if (document.readyState === 'loading') {
      document.addEventListener('DOMContentLoaded', fn, { once: true });
    } else { fn(); }
  }
  onReady(setScrollWindowHeight);
  var resizeTimeout;
  window.addEventListener('resize', function() {
    clearTimeout(resizeTimeout);
    resizeTimeout = setTimeout(setScrollWindowHeight, 150);
  });
})();
</script>





# 📰 Peer Review
- ICLR 2025 Workshop SSI-FM Reviewer
- ICLR 2026 Reviewer

# 🎖 Honors and Awards
- **2022.12** Typical Innovation and Entrepreneurship Models of Sichuan Agricultural University (10 students).
- **2022.11** China Telecom Scholarship · Fly Young Award.
- **2022.04** Youth May Fourth Model of Sichuan Agricultural University (10 students).
- **2021.11** National First Prize of Undergraduate Group of National Undergraduate Mathematical Modeling Contest of Gaojiaoshe Cup,team leader. 








<!-- # 💻 Internships
- **2024.08 - now**, <img src='./images/internship/bigai.png' style='width: 6em;'> the State Key Laboratory of General Artificial Intelligence(Beijing,China), **ML Lab**, Intern Researcher.
- **2024.02 - 2024.08**, <img src='./images/internship/bigai.png' style='width: 6em;'> the State Key Laboratory of General Artificial Intelligence(Beijing,China), **MAS Lab**, Algorithm Intern. -->


---
<span class='anchor' id='internships'></span>
# 💻 Internships and Work Experiences
<style>
.exp-list { list-style: none; margin: 0; padding: 0; }
.exp-item { 
  background: #fff; border: 1px solid #eee; border-radius: 12px; 
  box-shadow: 0 4px 12px rgba(0,0,0,0.06); padding: 14px; 
  display: flex; gap: 16px; align-items: center; max-width: 900px; margin: 10px auto;
}
.exp-text { flex: 1 1 auto; font-family: "Times New Roman", Times, serif; }
.exp-title { font-weight: 700; margin: 0 0 6px; }
.exp-sub { color: #555; margin: 0 0 6px; }
.exp-time { color: #777; font-size: 0.95em; }
.exp-img { flex: 0 0 200px; max-width: 200px; }
.exp-img img { width: 60%; height: auto; border-radius: 8px; box-shadow: 0 6px 14px rgba(0,0,0,0.10); background: #fff; }
@media (max-width: 640px) { .exp-item { flex-direction: column; } .exp-img { max-width: 100%; flex-basis: auto; } }
</style>

<style>
/* Experiences section scroll window styles (scoped) */
.experiences .scroll-window { max-height: 640px; overflow-y: auto; padding: 8px 6px; border: 1px solid #eaeaea; border-radius: 12px; background: transparent; box-shadow: inset 0 1px 0 rgba(255,255,255,0.6), 0 6px 14px rgba(0,0,0,0.04); }
.experiences .scroll-window::-webkit-scrollbar { width: 8px; }
.experiences .scroll-window::-webkit-scrollbar-thumb { background: #ddd; border-radius: 4px; }
</style>

<style>
/* Dark mode overrides for Internships section */
@media (prefers-color-scheme: dark) {
  .experiences .scroll-window { background: #111; border-color: #333; box-shadow: inset 0 1px 0 rgba(255,255,255,0.04), 0 6px 14px rgba(0,0,0,0.6); }
  .exp-item { background: #111; border-color: #333; box-shadow: 0 4px 12px rgba(0,0,0,0.5); }
}
</style>

<style>
/* Dark mode overrides (class/data-attribute toggles) for Internships section */
html.dark .experiences .scroll-window,
body.dark .experiences .scroll-window,
html[data-theme="dark"] .experiences .scroll-window,
:root[data-theme="dark"] .experiences .scroll-window,
[data-scheme="dark"] .experiences .scroll-window { background: #111 !important; border-color: #333 !important; box-shadow: inset 0 1px 0 rgba(255,255,255,0.04), 0 6px 14px rgba(0,0,0,0.6) !important; }

html.dark .exp-item,
body.dark .exp-item,
html[data-theme="dark"] .exp-item,
:root[data-theme="dark"] .exp-item,
[data-scheme="dark"] .exp-item { background: #111 !important; border-color: #333 !important; box-shadow: 0 4px 12px rgba(0,0,0,0.5) !important; }

html.dark .exp-img img,
body.dark .exp-img img,
html[data-theme="dark"] .exp-img img,
:root[data-theme="dark"] .exp-img img,
[data-scheme="dark"] .exp-img img { background: transparent !important; }
</style>

<div class="experiences">
<div class="scroll-window">
<ul class="exp-list">

  <li class="exp-item">
    <div class="exp-text">
      <p class="exp-title">Intern Researcher</p>
      <p class="exp-sub">AState Key Laboratory of General Artificial Intelligence (BIGAI, Beijing, China)</p>
      <ul style="margin: 6px 0 6px 18px; padding: 0; font-size: 0.96em; color: #555;">
        <li><strong>Affliation: ML Lab</strong></li>
        <li><strong>Advisor: Qing Li</strong></li>
      </ul>
      <p class="exp-time">2024.08 - now</p>
    </div>
    <div class="exp-img"><img src="images\tong.png" alt="BIGAI"></div>
  </li>
  <li class="exp-item">
    <div class="exp-text">
      <p class="exp-title">Algorithm Intern</p>
      <p class="exp-sub">State Key Laboratory of General Artificial Intelligence (BIGAI, Beijing, China)</p>
      <ul style="margin: 6px 0 6px 18px; padding: 0; font-size: 0.96em; color: #555;">
        <li><strong>Affliation: MAS Lab</strong></li>
        <li><strong>Advisor: Siyuan Qi</strong></li>
      </ul>
      <p class="exp-time">2024.02 - 2024.08</p>
    </div>
    <div class="exp-img"><img src="images\tong.png" alt="BIGAI"></div>
  </li>





 </ul>
</div>
</div>
<span class='anchor' id='person'></span>

<script>
(function() {
  function setExpScrollWindowHeight() {
    var container = document.querySelector('.experiences .scroll-window');
    if (!container) return;
    var firstLi = container.querySelector('.exp-list > li');
    if (!firstLi) return; // fallback to CSS default max-height
    var rowRect = firstLi.getBoundingClientRect();
    var liStyle = window.getComputedStyle(firstLi);
    var marginTop = parseFloat(liStyle.marginTop) || 0;
    var marginBottom = parseFloat(liStyle.marginBottom) || 0;
    var perItem = rowRect.height + (marginTop + marginBottom);
    var target = perItem * 3; // show ~3 items
    container.style.maxHeight = target + 'px';
  }
  function onReady(fn) {
    if (document.readyState === 'loading') {
      document.addEventListener('DOMContentLoaded', fn, { once: true });
    } else { fn(); }
  }
  onReady(setExpScrollWindowHeight);
  var resizeTimeout;
  window.addEventListener('resize', function() {
    clearTimeout(resizeTimeout);
    resizeTimeout = setTimeout(setExpScrollWindowHeight, 150);
  });
})();
</script>


<!-- <div style="display: flex; justify-content: center;">
  <div style="text-align: center;">
    <img src="./images/internship/bigai.png" alt="BIGAI" style="width: 200px; height: 60px;">
  </div>
</div> -->


<!-- # 📖 Educations
- **2024.06 - now**, <img src='./images/ustc.png' style='width: 2em;'> **University of Science and Technology of China (USTC), PhD student**. I am pursuing a degree in Information and Communication Engineering at USTC's School of Information Science and Technology, and the program is co-training with the State Key Laboratory of General Artificial Intelligence.

- **2020.09 - 2024.06**, **Sichuan Agricultural University (SICAU), graduate student**. I am studying for a degree in Information and Computational Science at the college of science in SICAU. -->


<span class='anchor' id='educations'></span>
# 📖 Educations

<style>
.edu-list { list-style: none; margin: 0; padding: 0; }
.edu-item { 
  background: #fff; border: 1px solid #eee; border-radius: 12px; 
  box-shadow: 0 4px 12px rgba(0,0,0,0.06); padding: 14px; 
  display: flex; gap: 16px; align-items: center; max-width: 900px; margin: 10px auto;
}
.edu-text { flex: 1 1 auto; font-family: "Times New Roman", Times, serif; }
.edu-title { font-weight: 700; margin: 0 0 6px; }
.edu-sub { color: #555; margin: 0 0 6px; }
.edu-time { color: #777; font-size: 0.95em; }
.edu-img { flex: 0 0 200px; max-width: 200px; }
.edu-img img { width: 60%; height: auto; border-radius: 8px; box-shadow: 0 6px 14px rgba(0,0,0,0.10); }
@media (max-width: 640px) { .edu-item { flex-direction: column; } .edu-img { max-width: 100%; flex-basis: auto; } }
</style>

<style>
/* Educations section scroll window styles (scoped) */
.educations .scroll-window { max-height: 640px; overflow-y: auto; padding: 8px 6px; border: 1px solid #eaeaea; border-radius: 12px; background: transparent; box-shadow: inset 0 1px 0 rgba(255,255,255,0.6), 0 6px 14px rgba(0,0,0,0.04); }
.educations .scroll-window::-webkit-scrollbar { width: 8px; }
.educations .scroll-window::-webkit-scrollbar-thumb { background: #ddd; border-radius: 4px; }
</style>

<style>
/* Dark mode overrides for Educations section */
@media (prefers-color-scheme: dark) {
  .educations .scroll-window { background: #111; border-color: #333; box-shadow: inset 0 1px 0 rgba(255,255,255,0.04), 0 6px 14px rgba(0,0,0,0.6); }
  .edu-item { background: #111; border-color: #333; box-shadow: 0 4px 12px rgba(0,0,0,0.5); }
}
</style>

<style>
/* Dark mode overrides (class/data-attribute toggles) for Educations section */
html.dark .educations .scroll-window,
body.dark .educations .scroll-window,
html[data-theme="dark"] .educations .scroll-window,
:root[data-theme="dark"] .educations .scroll-window,
[data-scheme="dark"] .educations .scroll-window { background: #111 !important; border-color: #333 !important; box-shadow: inset 0 1px 0 rgba(255,255,255,0.04), 0 6px 14px rgba(0,0,0,0.6) !important; }

html.dark .edu-item,
body.dark .edu-item,
html[data-theme="dark"] .edu-item,
:root[data-theme="dark"] .edu-item,
[data-scheme="dark"] .edu-item { background: #111 !important; border-color: #333 !important; box-shadow: 0 4px 12px rgba(0,0,0,0.5) !important; }

html.dark .edu-img img,
body.dark .edu-img img,
html[data-theme="dark"] .edu-img img,
:root[data-theme="dark"] .edu-img img,
[data-scheme="dark"] .edu-img img { background: transparent !important; }
</style>

<div class="educations">
<div class="scroll-window">
<ul class="edu-list">
  <li class="edu-item">
    <div class="edu-text">
      <p class="edu-title">Doctor of Philosophy (Ph.D)</p>
      <p class="edu-sub">University of Science and Technology of China (USTC)</p>
      <ul style="margin: 6px 0 6px 18px; padding: 0; font-size: 0.96em; color: #555;">
        <li>Key universities under the <strong>"985 Project"</strong></li>
        <li><strong>Advisor: Bin Li</strong></li>
        <li>Major: Information and Communication Engineering</li>
      </ul>
      <p class="edu-time">2024.09 - now</p>
    </div>
    <div class="edu-img"><img src="images\ustc.png" alt="USTC"></div>
  </li>
  <li class="edu-item">
    <div class="edu-text">
      <p class="edu-title">Undergraduate</p>
      <p class="edu-sub">Sichuan Agricultural University (SICAU)</p>
      <ul style="margin: 6px 0 6px 18px; padding: 0; font-size: 0.96em; color: #555;">
        <li>Key universities under the <strong>"211 Project"</strong></li>
        <li><strong>Major: Information and Computational Science, Rank: 4/152 (2.6%)</strong></li>
        <li>Finished my undergraduate in, SICAU, while the degree is offered by college of science in SICAU.</li>
      </ul>
      <p class="edu-time">2020.09 - 2024.06</p>
    </div>
    <div class="edu-img"><img src="images\sicau.png" alt="SICAU"></div>
  </li>
</ul>
</div>
</div>

<br><br><br>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Map Widget</title>
    <style>
        .map-container {
            width: 300px; 
            margin: 0 auto; 
            text-align: center; 
        }
        .map-container iframe {
            width: 100%; 
            height: 300px; 
        }
    </style>
</head>
<body>
    <div class="map-container">
<script type="text/javascript" id="mapmyvisitors" src="//mapmyvisitors.com/map.js?d=je5F_lWiCT9d_1nlJrSDAQ7oBIhafAq9Er1Q9DPpYXg&cl=ffffff&w=a"></script>
    </div>
</body>
</html>
