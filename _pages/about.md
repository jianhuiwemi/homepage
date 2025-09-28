---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Hi! I am an undergraduate at the [University of Electronic Science and Technology of China](https://en.uestc.edu.cn/). I have worked on computer vision, exploring problems such as cross-domain material retrieval with Dr. [Jingwei Huang](https://cs.stanford.edu/~jingweih/) ([Tencent Hunyuan 3D](https://hunyuan-3d.com/)), low-light image enhancement, and generative modeling. More recently, I have expanded my interests to AI for Science, especially drug discovery, where I focus on protein–ligand binding prediction at the [THU-ATOM Lab](https://atomlab.yanyanlan.com/), [Institute for AI Industry Research, Tsinghua University](https://air.tsinghua.edu.cn/en/), advised by Prof. [Yanyan Lan](https://yanyanlan.com/).








# 🔥 News
- *2025.09*: &nbsp; <a href="https://arxiv.org/pdf/2508.15480">HypSeek</a> accepted to NeurIPS 2025 AI for Science workshop! 🎉
- *2025.09*: &nbsp; <a href="https://arxiv.org/pdf/2506.05768">AANet</a> accepted to NeurIPS 2025! 🎉
- *2025.07*: &nbsp; <a href="https://arxiv.org/pdf/2411.01819v4">Free-Mask</a> accepted to ACM MM 2025! 🎉
- *2025.07*: &nbsp; <a href="https://arxiv.org/pdf/2504.14868">Twin-Co</a> accepted to ACM MM 2025! 🎉
- *2025.06*: &nbsp; <a href="https://openreview.net/pdf?id=10Jkkqyzlw">AlphaRank</a> accepted to ICML 2025 Generative AI and Biology (GenBio) Workshop! 🎉
- *2025.06*: &nbsp; <a href="https://openreview.net/pdf?id=Pt18WpGHHn">FragCLIP</a> accepted to ICML 2025 Generative AI and Biology (GenBio) Workshop! 🎉
- *2025.03*: &nbsp; <a href="https://openaccess.thecvf.com/content/CVPR2025/papers/Wang_MaRI_Material_Retrieval_Integration_across_Domains_CVPR_2025_paper.pdf">MaRI</a> is accepted to CVPR 2025! 🎉

# 📝 Selected Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025-AI4Science</div><img src='images/hypseek.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[Learning Protein-Ligand Binding in Hyperbolic Space](https://arxiv.org/pdf/2508.15480)**

**Jianhui Wang**, Wenyu Zhu, Bowen Gao, Xin Hong, Ya-Qin Zhang, Wei-Ying Ma, Yanyan Lan

_NeurIPS 2025 AI for Science workshop_

<small>We introduce HypSeek, a hyperbolic representation learning framework that embeds ligands, protein pockets, and sequences into Lorentz-model space. By leveraging hyperbolic geometry, it better captures subtle affinity differences (e.g., activity cliffs) and unifies virtual screening with affinity ranking in a single model.</small>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/aanet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[AANet: Virtual Screening under Structural Uncertainty via Alignment and Aggregation](https://arxiv.org/pdf/2506.05768)**

Wenyu Zhu, **Jianhui Wang**, Bowen Gao, Yinjun Jia, Haichuan Tan, Ya-Qin Zhang, Wei-Ying Ma, Yanyan Lan

_NeurIPS 2025_

<small>We propose AANet, an alignment-and-aggregation framework for virtual screening under structural uncertainty. It aligns ligands, holo pockets, and geometry-detected cavities through contrastive learning, and dynamically aggregates candidate binding sites via cross-attention. This enables robust screening on apo and AlphaFold-predicted structures, where conventional methods fail.</small>
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/mari.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[MaRI: Material Retrieval Integration across Domains](https://openaccess.thecvf.com/content/CVPR2025/papers/Wang_MaRI_Material_Retrieval_Integration_across_Domains_CVPR_2025_paper.pdf)**

**Jianhui Wang**, Zhifei Yang, Yangfan He, Huixiong Zhang, Yuxuan Chen, Jingwei Huang 

_CVPR 2025_

<small>We present MaRI, a cross-domain framework that aligns images and PBR materials in a shared embedding space. Combining synthetic renderings with real-world material data, MaRI enables robust and accurate material retrieval beyond conventional image search.</small>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2025</div><img src='images/twin-co.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[Twin Co-Adaptive Dialogue for Progressive Image Generation](https://arxiv.org/pdf/2504.14868?)**

**Jianhui Wang**, Yangfan He, Yan Zhong, Xinyuan Song, Jiayi Su, Yuheng Feng, et al.

_ACM MM 2025_


<small>We propose Twin-Co, a dual-path dialogue framework combining explicit user feedback with implicit optimization, enabling multi-turn text-to-image generation that better aligns with evolving user intent.</small>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2025</div><img src='images/free-mask.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[Free-Mask: A Novel Paradigm of Integration Between the Segmentation Diffusion Model and Image Editing](https://arxiv.org/pdf/2411.01819?)**

Bo Gao, **Jianhui Wang**, Xinyuan Song, Yangfan He, Fangxu Xing, Tianyu Shi.

_ACM MM 2025_


<small>We introduce Free-Mask, a diffusion-based framework that integrates segmentation and image editing. It generates realistic single- and multi-instance images with accurate masks, while an active learning pipeline improves both dataset quality and model generalization for open-world semantic segmentation.</small>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Neurocomputing</div><img src='images/mdanet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[MDANet: A multi-stage domain adaptation framework for generalizable low-light image enhancement](https://pdf.sciencedirectassets.com/271597/1-s2.0-S0925231225X00084/1-s2.0-S0925231225002449/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJHMEUCIQDe8rOTORIOFT%2Fcak%2BJgORwmxYaFjFQ4WJybZ0wNcL7mgIgEOTv6sYAvO0u90KyuSuhmPpRQvK1MOo1%2FKNiQOwdqwQquwUIh%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAFGgwwNTkwMDM1NDY4NjUiDKyCIdDFvAljebm4IiqPBd9j1ahDBdHd%2FcklWzKbzpAcYDas0Fa%2FlQhk1AAMgiS7DRJV%2Bw2pypVgZnGpuJYTULxCCqvS4DvduVqJ0FGIbai%2F0wfxZ6WgzgzCkzCLst96J2bf%2FyYnXz7EZt4LAV0RQMk3S5KSiYSOKvk4QlbMXMKPBznJS%2BC4MCGt9Nzb2aaBhbv8M2A7I7gjvwKpkTelHLwd1C2PpOMyVUSOG7tlmQhpuex2CQ0vfMJSCgkYzDtF4MoeGkU7mc11%2B6lvc8r1m60OPsYXBdTOvKJUFyfOFICZ4oW3S2OlcdbPIikyDtBEV6uQDtWtJQm3RUMTRYEApaNIq%2FO9%2FzL3pXBxFDadJqBAowddTjZ3u7RTyCCS2g54l508KS0XawJkeU5HFr8kCiBBhdiqYuZ%2BdGNmmj65kK0u6u2FPdEHvmIUZ5FrfakAOv5WFvfMfOeyyv6UnVelF4cjn6zuKMA%2B3isFAhxshdVfkcfAv55Owv2VxU3z3NwWt5k4e9ne3pLF8JzUSWYaVifMUzFlDoRtBck1pPlB0iS2HvFKzkXhBxgfYnxgl8AGn5QJO5d5RNNXScDJ68xQ7Jz8xqh94LtqL6QX29ZQLyr6Ce4kVSIIcLsL1C8rld%2BviZNDy9JdCa82SHpGn0vZIFAAFa68hj2EIt7eGyqu5bHx8JIk4AzNzXcVG67UYlj9gqbXr3mJc04q7uqC5%2BVqbf93GMr7fVYfM3h3J3noK2FOS6qqY4suof2HRsZSW7miUoUSNh0PUpY0U04RXlPGxwcKJPkZBO%2FWaYpJ4Uuoly39oG8Eo72zgP6GRY3fG7IdZdE2bAIHXA1TWKplUudCQgKrdXfzCcExgxFue18G6wkxIGUilNk2NyVnaOH2UQUw0NnYxgY6sQFb3J2RzZelyqEK170f7Xz483d8fUVuUfW5yNgWAzRjm1BwtBHNcfZn2Nk4R9VVyihh5ATw4yzlrZQnH%2Bm8P0rYXlosgdEgwhAo%2FJHUO62kayn5G4A8MuJ2cw3XNAM%2FB6eB0%2FoLbCqcDKeqVIVppe98Qxi4aC6fXqwozvDyUKwf0mfspsb78z0%2FGucuMa4gyTh4foZ0M%2BjzESLd01Zwn4kEmFsIsyHivvG1cuFmzDKFvvc%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20250926T062800Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYUEMATO3G%2F20250926%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=e5525903424331584edb1311345703ea4f08ea66ceb7fb12fa6f8cfb525d84e3&hash=651f178dc474b240af292c712b6796ebdc4c2f0ef13af40dc9e937bda0e0983c&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0925231225002449&tid=spdf-eeb715e4-13fc-4ed5-b850-62a6eda9e911&sid=b232c3e89f17214ddf0800614fd967cd3f75gxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&rh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=0f115d5950530d5c0609&rr=9850b2dfed61ef78&cc=us&kca=eyJrZXkiOiJFd0VUYytnTTJwVHFvdUlxckcxd24ySGhTZDBoRDdzUlpsVGdmWlFCbHRWSDY3Ni93Y0ZtN2J0eUIzbmJNdHUvN2MyeWlaN1A0YXRva0p5TjhjSnc2eWh3eHUrQUg0dVlScyt0VWtJZURaSEJNZ08vRVZjTHArRmFMdFZrSjhIZlNxQS9mdERoSFdOcHJMaEFyWnlDRlFaR0pNSW5KVjk1N1VuWnVOMG5MTmlwSDdhSGxRPT0iLCJpdiI6ImQzMjU3NDlhYjYxMTExMDAxZTFiMTdlZDdjNTBjYzJiIn0=_1758868093907)**

**Jianhui Wang**, Yangfan He, Kun Li, Sida Li, Lan Zhao, Jun Yin, Miao Zhang, Tianyu Shi, Xueqian Wang.

_Neurocomputing_


<small>We propose MDANet, a domain adaptation framework that integrates lighting invariance, region-focused enhancement, and contextual adaptation. It achieves robust generalization for low-light image enhancement across diverse real-world scenarios.</small>
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Space Weather</div><img src='images/weather.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[Short‐Term Prediction of the Dst Index and Estimation of Efficient Uncertainty Using a Hybrid Deep Learning Network](https://agupubs.onlinelibrary.wiley.com/doi/epdf/10.1029/2024SW004002)**

Ruyao Wang, **Jianhui Wang**, Tuo Liang, Huixiong Zhang.

_Space Weather_


<small>We propose a hybrid deep learning model for short-term forecasting of geomagnetic activity (Dst index), integrating solar wind parameters and uncertainty estimation. The framework provides reliable and accurate probabilistic space weather predictions.</small>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/vid-tta.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[Low-Cost Test-Time Adaptation for Robust Video Editing](https://arxiv.org/pdf/2507.21858)**

**Jianhui Wang**, Yinda Chen, Yangfan He, Xinyuan Song, Yi Xin, Dapeng Zhang, Zhongwei Wan, Bin Li, Rongchao Zhang.

_arXiv_


<small>We introduce Vid-TTA, a lightweight test-time adaptation framework for video editing. By combining motion-aware masked reconstruction with prompt augmentation, it enhances temporal consistency and mitigates prompt overfitting, offering plug-and-play improvements for existing editing models.</small>
</div>
</div>

[//]: # (# 📚 Selected Projects)

# 🌍 Services

Reviewer: [ICLR 2026](https://iclr.cc/Conferences/2026), [AAAI 2026](https://aaai.org/conference/aaai/aaai-26/), [CVPR 2025](https://cvpr.thecvf.com/)

<style>
.experience-box {
  display: flex;
  align-items: flex-start;
  margin-bottom: 20px;
  border: 1px solid #e0e0e0;
  border-radius: 8px;
  overflow: hidden;
}
.experience-image {
  width: 100px;
  min-width: 100px;
  height: 100px;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #f5f5f5;
}
.experience-image img {
  max-width: 90%;
  max-height: 90%;
  object-fit: contain;
}
.experience-text {
  flex: 1;
  padding: 15px;
}
.experience-text h3 {
  margin-top: 0;
}
</style>
