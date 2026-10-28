# 📝 Publications
*: Co-First Author, Equal Contribution

<div style="display: grid; grid-template-columns: repeat(5, max-content); justify-content: center; column-gap: 20px; row-gap: 15px;">
  <div style="display: flex; align-items: center;">
    <img src="./images/logos/conferences/ICLR.png" alt="ICLR" style="width: 150px; height: 45px;">
    <span style="margin-left: 10px; font-size: 20px; font-weight: bold; color: #8B4513;">×3</span>
  </div>
  <div style="display: flex; align-items: center;">
    <img src="./images/logos/conferences/AAAI.png" alt="AAAI" style="width: 150px; height: 45px;">
    <span style="margin-left: 10px; font-size: 20px; font-weight: bold; color: #8B4513;">×1</span>
  </div>
  <div style="display: flex; align-items: center;">
    <img src="./images/logos/conferences/ACL.png" alt="ACL" style="width: 150px; height: 45px;">
    <span style="margin-left: 10px; font-size: 20px; font-weight: bold; color: #8B4513;">×1</span>
  </div>
  <div style="display: flex; align-items: center;">
    <img src="./images/logos/conferences/ICML.png" alt="ICML" style="width: 150px; height: 45px;">
    <span style="margin-left: 10px; font-size: 20px; font-weight: bold; color: #8B4513;">×1</span>
  </div>
  <div style="display: flex; align-items: center;">
    <img src="./images/site/blank-conference-logo.png" alt="" style="width: 150px; height: 45px;">
    <span style="margin-left: 10px; font-size: 20px; font-weight: bold; color: #8B4513;"></span>
  </div>

  <div style="display: flex; align-items: center;">
    <img src="./images/logos/conferences/ACM-MM-2026.png" alt="ACM MM" style="height: 45px; width: auto;">
    <span style="margin-left: 10px; font-size: 20px; font-weight: bold; color: #8B4513;">×1</span>
  </div>
</div>

<style>
/* ===== Shared BibTeX drawer styles (Conference + Preprints) ===== */
.pub-button.bibtex-toggle {
  cursor: pointer;
  display: inline-flex;
  align-items: center;
  gap: 6px;
}
.pub-button.bibtex-toggle::before {
  content: "{ }";
  font-weight: 700;
  color: #6a5acd;
  letter-spacing: -1px;
  transition: color .2s ease;
}
.pub-button.bibtex-toggle.is-active {
  border-color: #4285F4;
  color: #1e5bb8;
  background: linear-gradient(180deg, #f3f7ff 0%, #eaf1ff 100%);
}
.pub-button.bibtex-toggle.is-active::before { color: #4285F4; }
.bibtex-drawer {
  display: grid;
  grid-template-rows: 0fr;
  transition: grid-template-rows .38s cubic-bezier(.16,1,.3,1);
  max-width: 900px;
  margin: 0 auto;
}
.bibtex-drawer.open { grid-template-rows: 1fr; }
.bibtex-drawer__inner { overflow: hidden; min-height: 0; }
.bibtex-card {
  margin-top: 10px;
  border: 1px solid #e2e8f4;
  border-radius: 14px;
  background: linear-gradient(180deg, #fbfcff 0%, #f4f7fd 100%);
  box-shadow: 0 10px 26px rgba(30, 55, 110, 0.10);
  overflow: hidden;
  transform: translateY(-8px);
  opacity: 0;
  transition: transform .38s cubic-bezier(.16,1,.3,1), opacity .3s ease;
}
.bibtex-drawer.open .bibtex-card { transform: translateY(0); opacity: 1; }
.bibtex-card__header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 9px 14px;
  background: linear-gradient(135deg, #4285F4 0%, #6a5acd 100%);
  color: #fff;
}
.bibtex-card__title {
  font-family: "Times New Roman", Times, serif;
  font-weight: 700;
  font-size: .96rem;
  letter-spacing: .3px;
  display: inline-flex;
  align-items: center;
  gap: 8px;
}
.bibtex-card__title svg { width: 16px; height: 16px; opacity: .95; }
.bibtex-copy {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  border: 1px solid rgba(255, 255, 255, .55);
  background: rgba(255, 255, 255, .16);
  color: #fff;
  font-family: "Times New Roman", Times, serif;
  font-size: .82rem;
  font-weight: 600;
  padding: 4px 12px;
  border-radius: 999px;
  cursor: pointer;
  transition: background .15s ease, transform .06s ease, border-color .15s ease;
}
.bibtex-copy:hover { background: rgba(255, 255, 255, .30); }
.bibtex-copy:active { transform: scale(.95); }
.bibtex-copy svg { width: 14px; height: 14px; }
.bibtex-copy.copied { background: #2ecc71; border-color: #2ecc71; }
.bibtex-card__code {
  margin: 0;
  padding: 14px 16px;
  font-family: "SFMono-Regular", Consolas, "Liberation Mono", Menlo, monospace;
  font-size: .82rem;
  line-height: 1.55;
  color: #243b53;
  white-space: pre;
  overflow-x: auto;
  background: transparent;
  tab-size: 2;
}
.bibtex-card__code code {
  font-family: inherit;
  background: transparent;
  padding: 0;
  border: 0;
  color: inherit;
  white-space: pre;
}
.bibtex-card__code::-webkit-scrollbar { height: 8px; }
.bibtex-card__code::-webkit-scrollbar-thumb { background: #cdd7e6; border-radius: 4px; }
@media (prefers-color-scheme: dark) {
  .bibtex-card { background: #14171c; border-color: #2c313a; box-shadow: 0 10px 26px rgba(0,0,0,0.55); }
  .bibtex-card__code { color: #cdd7e6; }
  .pub-button.bibtex-toggle.is-active { background: #1b2536; color: #9cc0ff; }
}

/* ===== Preprint BibTeX drawer: warm tone to match the "Preprint" badge ===== */
.preprint .pub-button.bibtex-toggle::before { color: #ff8a5b; }
.preprint .pub-button.bibtex-toggle.is-active {
  border-color: #ff8c42;
  color: #d2541f;
  background: linear-gradient(180deg, #fff6ef 0%, #ffe9d6 100%);
}
.preprint .pub-button.bibtex-toggle.is-active::before { color: #ff6b6b; }
.preprint .bibtex-card {
  border-color: #f6dcc7;
  background: linear-gradient(180deg, #fffaf6 0%, #fdf1e7 100%);
  box-shadow: 0 10px 26px rgba(200, 90, 40, 0.12);
}
.preprint .bibtex-card__header {
  background: linear-gradient(135deg, #ff6b6b 0%, #ffb14e 100%);
}
.preprint .bibtex-copy {
  background: rgba(120, 55, 20, .30);
  border-color: rgba(255, 255, 255, .85);
  color: #fff;
}
.preprint .bibtex-copy:hover { background: rgba(120, 55, 20, .45); }
.preprint .bibtex-card__code { color: #5a3a26; }
.preprint .bibtex-card__code::-webkit-scrollbar-thumb { background: #f0cdae; }
@media (prefers-color-scheme: dark) {
  .preprint .bibtex-card { background: #1c1712; border-color: #3a2b1e; box-shadow: 0 10px 26px rgba(0,0,0,0.55); }
  .preprint .bibtex-card__code { color: #e6cbb0; }
  .preprint .pub-button.bibtex-toggle.is-active { background: #2a1f16; color: #ffb27a; }
}
</style>

<span class='anchor' id='conference-papers'></span>
<h2 style="display: flex; align-items: center; justify-content: flex-start; border-left: 4px solid #4285F4; padding-left: 12px; margin-left: -16px; color: #333; flex-wrap: wrap; gap: 12px;">
  <span style="display: flex; align-items: center;">
    <span>Conference papers</span>
    <span style="color: #8B4513; font-weight: bold; margin-left: 0.6em;">{{ site.data.conference.main.size }}</span>
  </span>
  <span style="display: flex; align-items: center; gap: 6px; font-size: 0.85em; color: #666; font-weight: normal; margin-left: 1.25em;">
    <span style="white-space: nowrap;">If you find our work interesting, please help us by</span>
    <span style="display: inline-flex; align-items: center; color: #FFA500;">
      <span style="font-size: 16px;">🤗</span>
      <span style="margin-left: 2px;">Upvoting,</span>
    </span>
    <span style="display: inline-flex; align-items: center; color: #24292e;">
      <svg width="16" height="16" viewBox="0 0 24 24" fill="currentColor" style="margin-right: 4px;">
        <path d="M12 .297c-6.63 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23A11.509 11.509 0 0112 6.27c1.02 0 2.04.138 3 .404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576C20.566 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12"/>
      </svg>
      <span>Starring</span>
    </span>
    <span>and</span>
    <span style="display: inline-flex; align-items: center; color: #4285F4;">
      <svg width="16" height="16" viewBox="0 0 24 24" fill="currentColor" style="margin-right: 4px;" role="img" aria-label="Google Scholar">
        <path d="M5.242 13.769L0 9.5 12 0l12 9.5-5.242 4.269C17.548 11.249 14.978 9.5 12 9.5c-2.977 0-5.548 1.748-6.758 4.269zM12 10a7 7 0 1 0 0 14 7 7 0 0 0 0-14z"/>
      </svg>
      <span>Citing!</span>
    </span>
  </span>
</h2>

<!-- ## Conference papers -->

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
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: #fff;
  padding: 6px 10px;
  border-radius: 6px;
  font-weight: 700;
  font-size: 0.95rem;
}
.conference .pub-metrics-inline {
  display: flex;
  flex-direction: column;
  gap: 6px;
  align-items: flex-start;
}
.conference .pub-metrics-inline img { height: 20px; width: auto; max-width: none; }
.conference .pub-metrics-inline .paper-badge {
  display: inline-flex;
  align-items: center;
  height: 20px;
  padding: 0 10px;
  border-radius: 999px;
  background: #FFF3B0;
  border: 1px solid #E5B800;
  color: #222 !important;
  font-size: 0.78rem;
  font-weight: 600;
  line-height: 1;
  text-decoration: none !important;
  white-space: nowrap;
  transition: filter 0.15s ease;
}
.conference .pub-metrics-inline .paper-badge:hover { filter: brightness(0.95); }
.conference .pub-content { flex: 1 1 auto; padding-left: 4px; }
.conference .title { font-size: 1.14rem; font-weight: 700; line-height: 1.35; }
.conference .author { font-size: 0.98rem; }
.conference .periodical { font-size: 0.96rem; }
.conference .conference-name { color: #8B0000; font-weight: bold; }
.conference .conference-icon { display: inline-block; font-style: normal; }
.conference .links a { font-size: 13.5px !important; }
.conference .links-row { margin-top: 10px; display: flex; gap: 12px; align-items: center; }
.conference .links { display: flex; gap: 6px; flex-wrap: wrap; align-items: center; }
.conference .pub-button {
  display: inline-flex;
  align-items: center;
  gap: 4px;
  padding: 3px 11px;
  border: 0;
  border-radius: 4px;
  font-family: inherit;
  font-size: 0.92em !important;
  font-weight: 600;
  letter-spacing: 0.02em;
  line-height: 1.55;
  text-decoration: none !important;
  box-shadow: none !important;
  cursor: pointer;
  transition: filter 0.15s ease;
}
.conference .pub-button:hover,
.conference .pub-button:focus {
  filter: brightness(0.94);
  text-decoration: none !important;
}
.conference .pub-button.arxiv { background: #E8F0FE; color: #1A73E8; }
.conference .pub-button.huggingface-paper { background: #FEEFE3; color: #B06000; }
.conference .pub-button.code { background: #E8EAED; color: #3C4043; }
.conference .pub-button.website { background: #EDE7F6; color: #7B61C9; }
.conference .pub-button.bibtex-toggle { background: #E8EAF6; color: #3F51B5; }
.conference .pub-button i { font-size: 1em; }
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
      <div class="title">{% if link.internship and link.internship.size > 0 %}{% assign intern_items = link.internship | split: "," %}{% for intern_item in intern_items %}{% assign intern_name = intern_item | strip %}{% if intern_name == "bigai" %}<img src="images/logos/organizations/bigai-mark.png" alt="BIGAI" style="height:22px; vertical-align:middle; margin-right:6px;">{% elsif intern_name == "yuanbao" %}<img src="images/logos/organizations/yuanbao-color.svg" alt="Yuanbao" style="height:24px; vertical-align:middle; margin-right:6px;">{% elsif intern_name == "tencent" %}<img src="images/logos/organizations/tencent-color.svg" alt="Tencent" style="height:24px; vertical-align:middle; margin-right:6px;">{% elsif intern_name == "ali" %}<img src="images/logos/organizations/alibaba.svg" alt="Alibaba" style="height:24px; vertical-align:middle; margin-right:6px;">{% elsif intern_name == "qwen" %}<img src="images/logos/organizations/qwen.svg" alt="Qwen" style="height:24px; vertical-align:middle; margin-right:6px;">{% endif %}{% unless forloop.last %} {% endunless %}{% endfor %}{% endif %}<a href="{{ link.arxiv | default: '/404.html' }}">{{ link.title }}</a></div>
      <div class="author">{{ link.authors }}</div>
      <div class="periodical"><em class="conference-name">{{ link.conference }}</em>
      </div>
    <div class="links-row">
    <div class="links">
      {% if link.arxiv and link.arxiv.size > 0 %}
        <a href="{{ link.arxiv }}" class="pub-button arxiv" role="button" target="_blank"><i class="fas fa-file-alt" aria-hidden="true"></i> Paper</a>
      {% endif %}
      {% if link.huggingface_paper and link.huggingface_paper.size > 0 %}
        <a href="{{ link.huggingface_paper }}" class="pub-button huggingface-paper" role="button" target="_blank"><span aria-hidden="true">🤗</span> HF Paper</a>
      {% endif %}
      {% if link.code and link.code.size > 0 %}
        <a href="{{ link.code }}" class="pub-button code" role="button" target="_blank"><i class="fab fa-github" aria-hidden="true"></i> Code</a>
      {% endif %}
      {% if link.website and link.website.size > 0 %}
        <a href="{{ link.website }}" class="pub-button website" role="button" target="_blank"><i class="fas fa-link" aria-hidden="true"></i> Website</a>
      {% endif %}
      {% if link.dataset and link.dataset.size > 0 %}
        <a href="{{ link.dataset }}" class="pub-button dataset" role="button" target="_blank">Dataset</a>
      {% endif %}
      {% if link.model and link.model.size > 0 %}
        <a href="{{ link.model }}" class="pub-button model" role="button" target="_blank">Model</a>
      {% endif %}
      {% if link.poster and link.poster.size > 0 %}
        <a href="{{ link.poster }}" class="pub-button poster" role="button" target="_blank">Poster</a>
      {% endif %}
      {% if link.slides and link.slides.size > 0 %}
        <a href="{{ link.slides }}" class="pub-button slides" role="button" target="_blank">Slides</a>
      {% endif %}
      <button type="button" class="pub-button bibtex-toggle" aria-expanded="false">BibTeX</button>
    </div>
    {% assign github_repo = link.github_repo | default: '' | strip %}
    {% assign citations = link.citations | default: '' | append: '' | strip %}
    {% assign citations_href = link.citations_url | default: link.arxiv | default: '/404.html' %}
    {% assign hf_daily_rank = link.hf_daily_rank | default: '' | append: '' | strip %}
    {% assign hf_daily_url = link.hf_daily_url | default: link.huggingface_paper | default: '' | strip %}
    {% if github_repo != '' or (citations != '' and citations != '0') or hf_daily_rank != '' %}
    <div class="pub-metrics-inline">
      {% if github_repo != '' %}
      <a href="https://github.com/{{ github_repo }}" target="_blank" rel="noopener noreferrer">
        <img alt="Code Stars" src="https://img.shields.io/github/stars/{{ github_repo }}?style=social&label=Code+Stars">
      </a>
      {% endif %}
      {% if citations != '' and citations != '0' %}
      <a href="{{ citations_href }}" target="_blank" rel="noopener noreferrer">
        <img alt="Google Scholar Citations" src="https://img.shields.io/badge/Google%20Scholar-{{ citations }}-4285F4?style=flat&logo=googlescholar&logoColor=white">
      </a>
      {% endif %}
      {% if hf_daily_rank != '' %}
      <a class="paper-badge" href="{{ hf_daily_url }}" target="_blank" rel="noopener noreferrer">🤗 #{{ hf_daily_rank }} Paper of the day</a>
      {% endif %}
    </div>
    {% endif %}
    </div>
</div>
</div>
{% include paper_bibtex.html link=link type="inproceedings" %}
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
  var target = perItem * 2.5; // show 3 items
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


{% if site.data.preprint.main and site.data.preprint.main.size > 0 %}
<span class='anchor' id='preprints'></span>
<h2 style="display: flex; align-items: center; justify-content: flex-start; border-left: 4px solid #4285F4; padding-left: 12px; margin-left: -16px; color: #333; flex-wrap: wrap; gap: 12px;">
  <span style="display: flex; align-items: center;">
    <span>Preprints</span>
    <span style="color: #8B4513; font-weight: bold; margin-left: 0.6em;">{{ site.data.preprint.main.size }}</span>
  </span>
  <span style="display: flex; align-items: center; gap: 6px; font-size: 0.85em; color: #666; font-weight: normal; margin-left: 1.25em;">
    <span style="white-space: nowrap;">If you find our work interesting, please help us by</span>
    <span style="display: inline-flex; align-items: center; color: #FFA500;">
      <span style="font-size: 16px;">🤗</span>
      <span style="margin-left: 2px;">Upvoting,</span>
    </span>
    <span style="display: inline-flex; align-items: center; color: #24292e;">
      <svg width="16" height="16" viewBox="0 0 24 24" fill="currentColor" style="margin-right: 4px;">
        <path d="M12 .297c-6.63 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23A11.509 11.509 0 0112 6.27c1.02 0 2.04.138 3 .404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576C20.566 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12"/>
      </svg>
      <span>Starring</span>
    </span>
    <span>and</span>
    <span style="display: inline-flex; align-items: center; color: #4285F4;">
      <svg width="16" height="16" viewBox="0 0 24 24" fill="currentColor" style="margin-right: 4px;" role="img" aria-label="Google Scholar">
        <path d="M5.242 13.769L0 9.5 12 0l12 9.5-5.242 4.269C17.548 11.249 14.978 9.5 12 9.5c-2.977 0-5.548 1.748-6.758 4.269zM12 10a7 7 0 1 0 0 14 7 7 0 0 0 0-14z"/>
      </svg>
      <span>Citing!</span>
    </span>
  </span>
</h2>


<!-- 
## Preprints -->

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
  background: linear-gradient(135deg, #ff6b6b 0%, #feca57 100%);
  color: #fff;
  padding: 6px 10px;
  border-radius: 6px;
  font-weight: 700;
  font-size: 0.95rem;
}
.preprint .pub-metrics-inline {
  display: flex;
  flex-direction: column;
  gap: 6px;
  align-items: flex-start;
}
.preprint .pub-metrics-inline img { height: 20px; width: auto; max-width: none; }
.preprint .pub-metrics-inline .paper-badge {
  display: inline-flex;
  align-items: center;
  height: 20px;
  padding: 0 10px;
  border-radius: 999px;
  background: #FFF3B0;
  border: 1px solid #E5B800;
  color: #222 !important;
  font-size: 0.78rem;
  font-weight: 600;
  line-height: 1;
  text-decoration: none !important;
  white-space: nowrap;
  transition: filter 0.15s ease;
}
.preprint .pub-metrics-inline .paper-badge:hover { filter: brightness(0.95); }
.preprint .pub-content { flex: 1 1 auto; padding-left: 4px; }
.preprint .title { font-size: 1.14rem; font-weight: 700; line-height: 1.35; }
.preprint .author { font-size: 0.98rem; }
.preprint .periodical { font-size: 0.96rem; }
.preprint .links a { font-size: 13.5px !important; }
.preprint .links-row { margin-top: 10px; display: flex; gap: 12px; align-items: center; }
.preprint .links { display: flex; gap: 6px; flex-wrap: wrap; align-items: center; }
.preprint .pub-button {
  display: inline-flex;
  align-items: center;
  gap: 4px;
  padding: 3px 11px;
  border: 0;
  border-radius: 4px;
  font-family: inherit;
  font-size: 0.92em !important;
  font-weight: 600;
  letter-spacing: 0.02em;
  line-height: 1.55;
  text-decoration: none !important;
  box-shadow: none !important;
  cursor: pointer;
  transition: filter 0.15s ease;
}
.preprint .pub-button:hover,
.preprint .pub-button:focus {
  filter: brightness(0.94);
  text-decoration: none !important;
}
.preprint .pub-button.arxiv { background: #E8F0FE; color: #1A73E8; }
.preprint .pub-button.huggingface-paper { background: #FEEFE3; color: #B06000; }
.preprint .pub-button.code { background: #E8EAED; color: #3C4043; }
.preprint .pub-button.website { background: #EDE7F6; color: #7B61C9; }
.preprint .pub-button.bibtex-toggle { background: #E8EAF6; color: #3F51B5; }
.preprint .pub-button i { font-size: 1em; }
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
      <div class="title">{% if link.internship and link.internship.size > 0 %}{% assign intern_items = link.internship | split: "," %}{% for intern_item in intern_items %}{% assign intern_name = intern_item | strip %}{% if intern_name == "bigai" %}<img src="images/logos/organizations/bigai-mark.png" alt="BIGAI" style="height:22px; vertical-align:middle; margin-right:6px;">{% elsif intern_name == "yuanbao" %}<img src="images/logos/organizations/yuanbao-color.svg" alt="Yuanbao" style="height:24px; vertical-align:middle; margin-right:6px;">{% elsif intern_name == "tencent" %}<img src="images/logos/organizations/tencent-color.svg" alt="Tencent" style="height:24px; vertical-align:middle; margin-right:6px;">{% elsif intern_name == "ali" %}<img src="images/logos/organizations/alibaba.svg" alt="Alibaba" style="height:24px; vertical-align:middle; margin-right:6px;">{% elsif intern_name == "qwen" %}<img src="images/logos/organizations/qwen.svg" alt="Qwen" style="height:24px; vertical-align:middle; margin-right:6px;">{% endif %}{% unless forloop.last %} {% endunless %}{% endfor %}{% endif %}<a href="{{ link.arxiv | default: '/404.html' }}">{{ link.title }}</a></div>
      <div class="author">{{ link.authors }}</div>
      <div class="periodical"><em class="conference-name">{{ link.conference }}</em>
      </div>
    <div class="links-row">
    <div class="links">
      {% if link.arxiv and link.arxiv.size > 0 %}
        <a href="{{ link.arxiv }}" class="pub-button arxiv" role="button" target="_blank"><i class="fas fa-file-alt" aria-hidden="true"></i> Paper</a>
      {% endif %}
      {% if link.huggingface_paper and link.huggingface_paper.size > 0 %}
        <a href="{{ link.huggingface_paper }}" class="pub-button huggingface-paper" role="button" target="_blank"><span aria-hidden="true">🤗</span> HF Paper</a>
      {% endif %}
      {% if link.code and link.code.size > 0 %}
        <a href="{{ link.code }}" class="pub-button code" role="button" target="_blank"><i class="fab fa-github" aria-hidden="true"></i> Code</a>
      {% endif %}
      {% if link.website and link.website.size > 0 %}
        <a href="{{ link.website }}" class="pub-button website" role="button" target="_blank"><i class="fas fa-link" aria-hidden="true"></i> Website</a>
      {% endif %}
      <button type="button" class="pub-button bibtex-toggle" aria-expanded="false">BibTeX</button>
</div>
    {% assign github_repo = link.github_repo | default: '' | strip %}
    {% assign citations = link.citations | default: '' | append: '' | strip %}
    {% assign citations_href = link.citations_url | default: link.arxiv | default: '/404.html' %}
    {% assign hf_daily_rank = link.hf_daily_rank | default: '' | append: '' | strip %}
    {% assign hf_daily_url = link.hf_daily_url | default: link.huggingface_paper | default: '' | strip %}
    {% if github_repo != '' or (citations != '' and citations != '0') or hf_daily_rank != '' %}
    <div class="pub-metrics-inline">
      {% if github_repo != '' %}
      <a href="https://github.com/{{ github_repo }}" target="_blank" rel="noopener noreferrer">
        <img alt="Code Stars" src="https://img.shields.io/github/stars/{{ github_repo }}?style=social&label=Code+Stars">
      </a>
      {% endif %}
      {% if citations != '' and citations != '0' %}
      <a href="{{ citations_href }}" target="_blank" rel="noopener noreferrer">
        <img alt="Google Scholar Citations" src="https://img.shields.io/badge/Google%20Scholar-{{ citations }}-4285F4?style=flat&logo=googlescholar&logoColor=white">
      </a>
      {% endif %}
      {% if hf_daily_rank != '' %}
      <a class="paper-badge" href="{{ hf_daily_url }}" target="_blank" rel="noopener noreferrer">🤗 #{{ hf_daily_rank }} Paper of the day</a>
      {% endif %}
    </div>
    {% endif %}
</div>
</div>
</div>
{% include paper_bibtex.html link=link type="preprint" %}
</li>



{% endfor %}

</ul>
</div>
</div>

<div style="margin-top: 5px; font-size: small; margin-bottom: 0px;">⬆ Scrollable</div>

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
  var target = perItem * 2.5; // show 3 items
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
{% endif %}

<script>
/* BibTeX drawer: toggle expand/collapse + copy-to-clipboard (event delegation) */
(function() {
  document.addEventListener('click', function(e) {
    var toggle = e.target.closest ? e.target.closest('.bibtex-toggle') : null;
    if (toggle) {
      var li = toggle.closest('li');
      if (!li) return;
      var drawer = li.querySelector('[data-bibtex-drawer]');
      if (!drawer) return;
      var isOpen = drawer.classList.toggle('open');
      toggle.classList.toggle('is-active', isOpen);
      toggle.setAttribute('aria-expanded', isOpen ? 'true' : 'false');
      return;
    }
    var copyBtn = e.target.closest ? e.target.closest('.bibtex-copy') : null;
    if (copyBtn) {
      var card = copyBtn.closest('.bibtex-card');
      if (!card) return;
      var codeEl = card.querySelector('code');
      if (!codeEl) return;
      var text = codeEl.innerText;
      var label = copyBtn.querySelector('.bibtex-copy__label');
      var done = function() {
        copyBtn.classList.add('copied');
        if (label) { label.dataset.orig = label.dataset.orig || label.textContent; label.textContent = 'Copied!'; }
        setTimeout(function() {
          copyBtn.classList.remove('copied');
          if (label && label.dataset.orig) label.textContent = label.dataset.orig;
        }, 1600);
      };
      if (navigator.clipboard && navigator.clipboard.writeText) {
        navigator.clipboard.writeText(text).then(done).catch(function() { fallbackCopy(text, done); });
      } else {
        fallbackCopy(text, done);
      }
    }
  });
  function fallbackCopy(text, done) {
    var ta = document.createElement('textarea');
    ta.value = text;
    ta.style.position = 'fixed';
    ta.style.opacity = '0';
    document.body.appendChild(ta);
    ta.select();
    try { document.execCommand('copy'); done(); } catch (err) {}
    document.body.removeChild(ta);
  }
})();
</script>

{% include paper_image_hover_zoom.html %}
