---
permalink: /
title: "About Me"
excerpt: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
  - /publications/
  - /projects/
  - /services/
---

<style>
a:link, a:visited {
  text-decoration: none;
}

a:hover, a:active {
  text-decoration: underline;
}

.page__content h1.section-title {
  margin-top: 1.5em;
}

/* inset the bio and education text to line up with the work cards' content */
.page__content > p,
.page__content > ul {
  margin-left: 2.0em;
  margin-right: 1.6em;
}

/* start the bullets at the same left edge as the bio text */
.page__content > ul {
  padding-left: 0;
  list-style: none;
}

.page__content > ul > li {
  position: relative;
  padding-left: 1.1em;
}

.page__content > ul > li::before {
  content: "•";
  position: absolute;
  left: 0;
}

.work {
  display: flex;
  align-items: center;
  gap: 1.2em;
  margin: 0 0 1.2em;
  padding: 1em 1.2em;
  border: 1px solid #dfe3e8;
  border-radius: 8px;
  font-size: 0.95em;
  line-height: 1.5;
}

.work__thumb {
  flex: 0 0 32%;
}

.work__thumb img {
  display: block;
  cursor: zoom-in;
  width: 100%;
  border-radius: 4px;
}

.work-zoom:focus {
  outline: none;
}

.work-zoom:focus-visible {
  outline: 2px solid #d35400;
  outline-offset: 2px;
}

.work-zoom-popup img.mfp-img {
  max-width: 61.8vw;
  max-height: 61.8vh !important;
}

/* fade + slight scale when opening and closing the zoom */
.mfp-bg.work-zoom-popup {
  opacity: 0;
  transition: opacity 0.2s ease-out;
}

.mfp-bg.work-zoom-popup.mfp-ready {
  opacity: 0.8;
}

.mfp-bg.work-zoom-popup.mfp-removing {
  opacity: 0;
}

.work-zoom-popup .mfp-content {
  opacity: 0;
  transform: scale(0.96);
  transition: opacity 0.2s ease-out, transform 0.2s ease-out;
}

.work-zoom-popup.mfp-ready .mfp-content {
  opacity: 1;
  transform: scale(1);
}

.work-zoom-popup.mfp-removing .mfp-content {
  opacity: 0;
  transform: scale(0.96);
}

.work__body {
  flex: 1;
  min-width: 0;
}

@media (max-width: 600px) {
  .work {
    flex-direction: column;
    align-items: stretch;
  }
}

.work__title {
  font-size: 1.15em;
  font-weight: bold;
  line-height: 1.35;
  margin-bottom: 0.15em;
}

.work__authors,
.work__venue {
  color: #5c6166;
}

.work__authors b {
  text-decoration: underline;
}

.work__venue {
  font-style: italic;
}

.work__venue .highlight {
  color: #d35400;
  font-style: normal;
}

.work__desc {
  margin-top: 0.3em;
  color: #767c82;
}

.work__links {
  margin-top: 0.4em;
}

.work__links a {
  display: inline-block;
  margin: 0 0.4em 0.3em 0;
  padding: 0.1em 0.7em;
  font-size: 0.8em;
  color: #c0490a;
  background: #fdf0e6;
  border: 1px solid #f6cfae;
  border-radius: 1em;
}

.work__links a:hover {
  text-decoration: none;
  filter: brightness(0.95);
}

</style>

Qixiang Chen is a second-year Ph.D. student in the Department of Data Science and AI at [Monash University](https://www.monash.edu/), supervised by [Prof. Jianfei Cai](https://jianfei-cai.github.io/) and [Dr. Jingwen Ye](https://jngwenye.github.io/). Before that, he received his Bachelor of Advanced Computing (Honours), majoring in Computer Vision and Machine Learning, from the [Australian National University](https://www.anu.edu.au/).

His research interests include multimodal learning, 3D spatial reasoning, vision-language models, and video understanding.


<h1 class="section-title">Education</h1>

- **Ph.D. in Information Technology**, Monash University, *Aug 2025 – Present*

- **Bachelor of Advanced Computing (Honours)**, The Australian National University, *Jul 2022 – Jul 2025*

<h1 id="publications" class="section-title">Publications</h1>

<div class="work">
  <div class="work__thumb"><a class="work-zoom" href="/images/works/full/seek-and-view.jpg" title="Seek-and-View reasoning overview"><img src="/images/works/seek-and-view.jpg" alt="Seek-and-View reasoning overview"></a></div>
  <div class="work__body">
    <div class="work__title">Seek-and-View Reasoning for Multi-View Spatial Understanding</div>
    <div class="work__authors"><b>Qixiang Chen</b>, Cheng Zhang, Fucai Ke, Chi-Wing Fu, Jianfei Cai, Jingwen Ye</div>
    <div class="work__venue">arXiv preprint, 2026</div>
    <div class="work__desc">A Seek-and-View reasoning paradigm that seeks a question-relevant view to make the spatial evidence directly observable, realized by Vantage, a training-free and model-agnostic framework coupling VLM reasoning with a 3D foundation model.</div>
    <div class="work__links">
      <a href="https://arxiv.org/abs/2610.11810">Paper</a>
      <a href="https://seekandview2026.github.io">Project Page</a>
      <a href="https://github.com/q1xiangchen/Vantage">Code</a>
    </div>
  </div>
</div>

<div class="work">
  <div class="work__thumb"><a class="work-zoom" href="/images/works/full/openview.jpg" title="OpenView: out-of-view VQA"><img src="/images/works/openview.jpg" alt="OpenView: out-of-view VQA"></a></div>
  <div class="work__body">
    <div class="work__title">OpenView: Empowering MLLMs with Out-of-view VQA</div>
    <div class="work__authors"><b>Qixiang Chen</b>, Cheng Zhang, Chi-Wing Fu, Jingwen Ye, Jianfei Cai</div>
    <div class="work__venue">The 40th Conference on Neural Information Processing Systems (NeurIPS 2026), Evaluations &amp; Datasets Track</div>
    <div class="work__desc">Out-of-view (OOV) VQA asks MLLMs to reason about objects, activities, and scenes beyond the visible frame of an image. We build a VQA synthesis pipeline to construct OpenView-Dataset, and a human-annotated OpenView-Bench for evaluation.</div>
    <div class="work__links">
      <a href="https://arxiv.org/abs/2512.18563">Paper</a>
      <a href="https://github.com/openview-2026/code">Code</a>
      <a href="https://huggingface.co/datasets/openview2026/OpenView_data">Data</a>
    </div>
  </div>
</div>

<div class="work">
  <div class="work__thumb"><a class="work-zoom" href="/images/works/full/vau-r1.jpg" title="VAU-R1 overview"><img src="/images/works/vau-r1.jpg" alt="VAU-R1 overview"></a></div>
  <div class="work__body">
    <div class="work__title">VAU-R1: Advancing Video Anomaly Understanding via Reinforcement Fine-Tuning</div>
    <div class="work__authors">Liyun Zhu, <b>Qixiang Chen</b>, Xi Shen, Xiaodong Cun</div>
    <div class="work__venue">arXiv preprint, 2025</div>
    <div class="work__desc">A reinforcement fine-tuning framework that strengthens MLLM reasoning for video anomaly understanding, together with VAU-Bench, the first large-scale Chain-of-Thought benchmark for anomaly reasoning.</div>
    <div class="work__links">
      <a href="https://arxiv.org/abs/2505.23504">Paper</a>
      <a href="https://q1xiangchen.github.io/VAU-R1/">Project Page</a>
      <a href="https://github.com/GVCLab/VAU-R1">Code</a>
      <a href="https://huggingface.co/datasets/7xiang/VAU-Bench">Data</a>
    </div>
  </div>
</div>

<div class="work">
  <div class="work__thumb"><a class="work-zoom" href="/images/works/full/motion-prompts.jpg" title="Video motion prompts pipeline"><img src="/images/works/motion-prompts.jpg" alt="Video motion prompts pipeline"></a></div>
  <div class="work__body">
    <div class="work__title">Motion meets Attention: Video Motion Prompts</div>
    <div class="work__authors"><b>Qixiang Chen</b>, Lei Wang, Piotr Koniusz, Tom Gedeon</div>
    <div class="work__venue">The 16th Asian Conference on Machine Learning (ACML 2024) <br> <span class="highlight">Long Presentation (5.67%)</span></div>
    <div class="work__desc">A plug-and-play motion prompt layer that turns frame differencing maps into attention maps, so video models focus on the motion that matters for fine-grained action recognition.</div>
    <div class="work__links">
      <a href="https://arxiv.org/abs/2407.03179">Paper</a>
      <a href="https://q1xiangchen.github.io/motion-prompts/">Project Page</a>
      <a href="https://github.com/q1xiangchen/VMPs">Code</a>
    </div>
  </div>
</div>

<h1 id="projects" class="section-title">Projects</h1>

<div class="work">
  <div class="work__thumb"><a class="work-zoom" href="/images/works/full/painterapp.jpg" title="PainterApp 2D and 3D canvas results"><img src="/images/works/painterapp.jpg" alt="PainterApp 2D and 3D canvas results"></a></div>
  <div class="work__body">
    <div class="work__title">PainterApp: Stroke Painting Algorithms with Shader Enhancements</div>
    <div class="work__venue">Course Project, COMP4610 Computer Graphics, ANU, 2024</div>
    <div class="work__desc">Stroke-based painting algorithms with shader enhancements that render photographs as realistic digital paintings, in both 2D and 3D.</div>
    <div class="work__links">
      <a href="/files/cg_report.pdf">Report</a>
      <a href="https://github.com/huilchen/paintercpp">Code</a>
    </div>
  </div>
</div>

<div class="work">
  <div class="work__thumb"><a class="work-zoom" href="/images/works/full/vehicle-translation.jpg" title="Vehicle-X to VeRi translation results"><img src="/images/works/vehicle-translation.jpg" alt="Vehicle-X to VeRi translation results"></a></div>
  <div class="work__body">
    <div class="work__title">Vehicle Image Translation: Adapting Synthetic Styles to Real-World Scenarios</div>
    <div class="work__venue">Course Project, COMP4660 Neural Networks, Deep Learning and Bio-inspired Computing, ANU, 2023</div>
    <div class="work__desc">CycleGAN-based translation of synthetic Vehicle-X images into the style of the real-world VeRi dataset, improving domain adaptation for vehicle recognition.</div>
    <div class="work__links">
      <a href="/files/I2I_report.pdf">Report</a>
      <a href="https://github.com/q1xiangchen/CycleGAN_vehicle">Code</a>
    </div>
  </div>
</div>

<script>
/* Single-image zoom for work previews. The theme turns every .jpg link into a gallery (.image-popup), so rebind these after its ready handler has run. */
document.addEventListener('DOMContentLoaded', function () {
  $(function () {
    var links = $('.work-zoom').removeClass('image-popup');
    links.magnificPopup({
      type: 'image',
      gallery: { enabled: false },
      closeOnContentClick: true,
      closeBtnInside: false,
      removalDelay: 200,
      mainClass: 'work-zoom-popup',
      callbacks: {
        afterClose: function () { document.activeElement.blur(); }
      }
    });
  });
  /* fetch the full-size images once the page has loaded, so zooming is instant */
  window.addEventListener('load', function () {
    document.querySelectorAll('.work-zoom').forEach(function (a) { new Image().src = a.href; });
  });
});
</script>
