# 😊 About me



I am a **PhD student** in <strong><a class="entity-link" href="https://www.ustc.edu.cn/index.htm"><span class="entity-mention" style="--entity-color:#005caa; --entity-bg:#edf6fc; --entity-hover-bg:#e1f0fa; --entity-glow:rgba(0,92,170,.34); --entity-glow-soft:rgba(0,92,170,.18);"><img class="entity-logo" src="images/logos/education/USTC.svg" alt="">University of Science and Technology of China (USTC)</span></a></strong>, supervised by <a href="http://staff.ustc.edu.cn/~binli/">Bin Li (USTC, 李斌)</a>.





<!-- I am an upcoming joint **PhD student** at <img src="images/logos/organizations/bigai-mark.png" alt="BIGAI" style="height:22px; vertical-align:middle; margin-right:6px;"> **State Key Laboratory of General Artificial Intelligence** <a href='https://www.bigai.ai/'>(BIGAI)</a> and <img src="images/logos/education/USTC.svg" alt="BIGAI" style="height:28px; vertical-align:middle; margin-right:6px;">**University of Science and Technology of China** <a href='https://www.ustc.edu.cn/index.htm'>(USTC)</a>, supervised by <a href='http://staff.ustc.edu.cn/~binli/'>Bin Li (USTC, 李斌)</a>.  -->

Currently, I am doing my internship in <strong><a class="entity-link" href="https://yuanbao.tencent.com/"><span class="entity-mention" style="--entity-color:#00a85a; --entity-bg:#ecfaf3; --entity-hover-bg:#ddf7ea; --entity-glow:rgba(0,168,90,.34); --entity-glow-soft:rgba(0,168,90,.18);"><img class="entity-logo" src="images/logos/organizations/yuanbao-color.svg" alt="">Tencent Yuanbao AI Search Team</span></a></strong> and working on Agentic Search, LLM for Ranking. Previously, I held research intern positions at <strong><a class="entity-link" href="https://www.bigai.ai/"><span class="entity-mention" style="--entity-color:#9a4035; --entity-bg:#f9efed; --entity-hover-bg:#f4e2df; --entity-glow:rgba(154,64,53,.34); --entity-glow-soft:rgba(154,64,53,.18);"><img class="entity-logo" src="images/logos/organizations/bigai-mark.png" alt="">BIGAI MAS & ML Lab</span></a></strong>. <img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2FKailinJiang%2Fkailinjiang.github.io@google-scholar-stats%2Fgs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations"> <img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2FKailinJiang%2Fkailinjiang@google-scholar-stats%2Ftotal-stars.json%3FcacheBuster%3D1">  [![GitHub followers](https://img.shields.io/github/followers/kailinjiang)](https://github.com/kailinjiang)


**Research Interests：**
- **🧬 Continual Learning** — Enabling models to continuously acquire, update, and inject knowledge without catastrophic forgetting.
- **⚖️ LLM for Ranking** — Leveraging large language models for next-generation information retrieval and ranking.
- **🎯 MLLM Evaluation & Benchmarking** — Designing rigorous evaluation protocols to assess reasoning and reliability of foundation models.

<!-- 💬 If you are interested in collaborating with me, always feel free to contact me through e-mail or <a href="./images/contact/wechat-qr.png">Wechat</a>. -->


<!-- I am currently working on knowledge editing, knowledge injection, multimodal learning, continual learning, <a href='https://scholar.google.com/citations?user=NSHQsrAAAAAJ'><img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2FKailinJiang%2Fkailinjiang.github.io@google-scholar-stats%2Fgs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations">  -->








<!-- My huggingface at 🤗 [Huggingface home](https://huggingface.co/kailinjiang). -->


<div style="text-align: center;">
  <img 
    src="https://raw.githubusercontent.com/kailinjiang/kailinjiang/output/github-contribution-grid-snake.svg" 
    alt="github-contribution-grid-snake"
  >
</div>


# 🔥 News



<style>
/* News section scroll window styles (scoped) — 默认约 5 行，JS 会按实际行高精确设置 */
.news .scroll-window { max-height: 15em; overflow-y: auto; padding: 8px 6px; border: 1px solid #eaeaea; border-radius: 12px; background: #fff; box-shadow: inset 0 1px 0 rgba(255,255,255,0.6), 0 6px 14px rgba(0,0,0,0.04); }
.news .scroll-window::-webkit-scrollbar { width: 8px; }
.news .scroll-window::-webkit-scrollbar-thumb { background: #ddd; border-radius: 4px; }
.news .btn-link {
  display: inline-block;
  padding: 2px 9px;
  margin-right: 2px;
  font-size: 0.85em;
  font-weight: 600;
  letter-spacing: 0.02em;
  line-height: 1.55;
  border-radius: 4px;
  border-bottom: 0 !important;
  box-shadow: none !important;
  text-decoration: none !important;
  transition: filter 0.15s ease;
}
.news .btn-link:hover,
.news .btn-link:focus {
  border-bottom: 0 !important;
  box-shadow: none !important;
  text-decoration: none !important;
  filter: brightness(0.94);
}
.news .btn-blog,
.news .btn-blog:hover {
  background: #E8F5E9;
  color: #21b84c;
}
.news .btn-link img {
  height: 1.05em;
  width: auto;
  vertical-align: -0.15em;
  margin-right: 4px;
  box-shadow: none;
}
</style>






<div class="news">
<div class="scroll-window">
<ul>
{% for item in site.data.news %}
<li>{{ item.line | markdownify }}</li>
{% endfor %}
</ul>
</div>
</div>

<div style="margin-top: 5px; font-size: small; margin-bottom: 0px;">⬆ Scrollable</div> 

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
    var target = perItem * 7; // show 5 items; rest via scroll
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



<span class='anchor' id='internships'></span>
# 💻 Internship Experience



- **2026.06 – Present｜ <img src="./images/logos/organizations/tencent-brand-color.svg" alt="Tencent" style="height:18px; vertical-align:middle;"> Tencent, <img src="./images/logos/organizations/yuanbao-color.svg" alt="Tencent Yuanbao" style="height:25px; vertical-align:middle;"> Yuanbao AI Search Team. <img src="./images/logos/programs/tencent-project-up.png" alt="Tencent Project UP" style="height:22px; vertical-align:middle;"> <a href="https://join.qq.com/qingyun.html" target="_blank" rel="noopener noreferrer"><span style="color:red">(Tencent Project UP)</span></a>**
  - I work on 📊📊 LLM4Ranking for RAG & Deep Research, developing [**AdaTutoRank**](https://arxiv.org/abs/2609.32472) for adaptive tutoring optimization in document-set reranking, and [**Rubric4Setwise**](https://arxiv.org/pdf/2607.19747) for rubric-oriented document set selection and ranking.

- **2024.02 – 2026.05｜ <img src="./images/logos/organizations/bigai-all.png" alt="BIGAI" style="height:32px; vertical-align:middle;"> BIGAI, MAS & ML Lab.**
  - I worked on continual learning (knowledge injection & editing) and knowledge evaluation, developing [**KORE**](https://arxiv.org/pdf/2510.19316) and [**MMEVOKE**](https://arxiv.org/pdf/2505.24449) for 💉💉 continual knowledge injection, [**ICE**](https://arxiv.org/pdf/2406.11194) and [**MMKE-Bench**](https://arxiv.org/pdf/2502.19870) for 🩺🩺 knowledge editing, and [**MINED**](https://arxiv.org/pdf/2510.19457) for ⏱️⏱️ time-sensitive knowledge probing.
  - Mentors: [**Siyuan Qi**](https://scholar.google.com/citations?user=ePclJR4AAAAJ), [**Yuntao Du**](https://yuntaodu.github.io/), [**Qing Li**](https://liqing.io/), and [**Zhi Gao**](https://zhigao2017.github.io/).
