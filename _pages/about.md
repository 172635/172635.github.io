---
layout: about
title: about
permalink: /
subtitle: ""

profile:
  align: right
  image: #prof_pic.jpg
  image_circular: true # crops the image to make it circular
  more_info: ""

selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: true
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---
<style>
  .post-title, .about h1 {
    font-size: 1.8rem !important;
    font-weight: 700 !important;
    margin-bottom: 0.3rem !important;
  }
  .profile img {
    max-width: 150px !important;
    width: 100% !important;
    height: auto !important;
  }

  :root {
    --pill-bg: #f8f9fa;
    --pill-color: #495057;
    --pill-border: #e9ecef;
    --pill-hover-bg: #e9ecef;
    --section-title-color: #6c757d;
    --section-border-color: #dee2e6;
    --text-base-color: #212529;
  }
  html[data-theme='dark'] {
    --pill-bg: #212529;
    --pill-color: #adb5bd;
    --pill-border: #343a40;
    --pill-hover-bg: #2b3035;
    --section-title-color: #8b949e;
    --section-border-color: #40454b;
    --text-base-color: #c9d1d9;
  }
  
  .profile-links {
    margin-top: 15px;
    margin-bottom: 20px;
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
  }
  .profile-links a {
    background-color: var(--pill-bg) !important;
    color: var(--pill-color) !important;
    border: 1px solid var(--pill-border) !important;
    padding: 6px 14px !important;
    border-radius: 20px !important;
    font-size: 0.85rem !important;
    font-weight: 500;
    text-decoration: none !important;
    display: inline-flex;
    align-items: center;
    gap: 6px;
    transition: all 0.2s ease;
  }
  .profile-links a:hover {
    background-color: var(--pill-hover-bg) !important;
    color: var(--text-base-color) !important;
  }

  .interest-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    margin-top: 10px;
    margin-bottom: 15px;
  }
  .interest-tag {
    background-color: var(--pill-bg) !important;
    color: var(--pill-color) !important;
    border: 1px solid var(--pill-border) !important;
    padding: 6px 14px !important;
    border-radius: 20px !important;
    font-size: 0.85rem !important;
    font-weight: 500;
  }

  .about h2, 
  .post article h2,
  .about article h2 {
    font-size: 1rem !important;
    font-weight: 600 !important;
    color: var(--section-title-color) !important;
    text-transform: uppercase !important;
    letter-spacing: 0.5px !important;
    border-top: 1px solid var(--section-border-color) !important;
    padding-top: 10px !important;
    margin-top: 20px !important;
    margin-bottom: 10px !important;
    border-bottom: none !important;
  }

  .about h2 a, .post article h2 a {
    color: var(--section-title-color) !important;
    text-decoration: none !important;
  }

  .about article p, .about article div {
    font-size: 0.95rem !important;
    line-height: 1.6 !important;
    color: var(--text-base-color);
  }
</style>

Hello, I am a fourth-year undergraduate student majoring in **Computer Science** and **Mathematical Sciences** at the Gwangju Institute of Science and Technology (GIST). I am currently working as an undergraduated researcher in the <a href="https://sundong.kim/publications/">DataScience Lab</a>, advised by Prof. Sundong Kim.

My ultimate research goal is to realize robust **Artificial General Intelligence (AGI)** capable of autonomously analyzing underlying rules and adapting to unseen out-of-distribution (OOD) environments by leveraging prior knowledge and preference/dispreference awareness. 

To achieve this, my current research interests include below two core directions:

##### 1. Autonomous Exploration & Continual Learning in RL
To maximize agent autonomy and learning efficiency, focusing on how agents can adapt smoothly with minimal data.
* **Unsupervised Environment Design (UED)**: Developing highly efficient agent architectures that autonomously generate curriculum frameworks based on environmental difficulty and data distribution.
* **Mitigating Catastrophic Forgetting**: Utilizing **Optimal Transport (OT)** theory and **Flow Policies** to enhance policy and data transfer efficiency across diverse environmental distributions, enabling sustainable knowledge expansion.

##### 2. Geometric Foundations of Latent Spaces & Explainable AI
To clarify the semantic relationships and complex rules embedded within high-dimensional data, connect linguistic/semantic consensus with the geometric structures of latent spaces.
* **Statistical Manifolds & Information Geometry**: Moving beyond Euclidean spaces, model latent representations as statistical manifolds. By applying topology and information geometry, mathematically define the curvature and metrics of probability distributions.
* **Mathematical Causality & Interpretability**: By constructing abstract semantics based on geometric structures, provide interpretability and causality for decision-making systems.

Ultimately, I aim to break through the current limitations of AI by leveraging on mathematical logic.



<p style="text-align: center;">I am always open to intellectual discussions and exchanging ideas-feel free to reach out!</p>

<div style="display: flex; justify-content: center; align-items: center;">
  <div>
    <a href="mailto:hojun172@gm.gist.ac.kr">Mail</a> &#124; 
    <a href="/assets/pdf/Hojun_Yi_CV.pdf" target="_blank">CV</a> &#124; 
    <a href="https://github.com/172635" target="_blank">GitHub</a> &#124; 
    <a href="https://scholar.google.com/citations?user=92gRj0wAAAAJ" target="_blank">Google Scholar</a>
  </div>
</div>

## Education

* **B.S. in Electrical Engineering and Computer Science** GIST(Gwangju Institute of Science and Technology) <span style="float: right;">*2023 - Present*</span>
  * Expected Cum Laude graduation in Aug 2027, Total GPA: 4.16/4.5
  * Major(EECS) GPA: 4.32, Double Major(Mathematical Sciences): 4.20

## Experience
* **Undergraduated Research Intern** - DataScience Lab (Advised by Prof. Sundong Kim) in GIST <span style="float: right;">*2025 - Present*</span>
  * Conducting Research on Open-Endedness, Unsupervised RL
  * Studied Math for ML, Probabilistic ML
  * Lightning talk about TRACED on CoRL workshop 2025

## Selected Publications
<span style="float: right; margin-top: -35px;"><a href="/publications/" class="btn btn-sm z-depth-1" role="button" style="color: var(--global-theme-color); text-transform: none; font-size: 0.85rem;">All Publications <i class="fas fa-arrow-right"></i></a></span>

* TRACED: Transition-aware Regret Approximation with Co-learnability for Environment Design
  * Authors : G. Cho, J. Im, J. Lee, ***H. Yi***, S. Kim, S. Kim
  * <a href="https://iclr.cc/virtual/2026/poster/10010241">ICLR 2026</a>, CoRL workshop 2025
  * [[Arxiv]]("https://arxiv.org/pdf/2506.19997") [[Code]]("https://github.com/Cho-Geonwoo/traced") [[Website]]("https://geonwoo.me/traced/")


## Awards and honors:
* Dean's List (GIST EECS) <span style="float: right;">*2023 - 2025*</span>
* 2024 ICPC Seoul Regional - 63rd <span style="float: right;">*2024-11*</span>
* 2024 GIST Algorithm Masters - 1st <span style="float: right;">*2024-05*</span>
* Hello, BOJ 2024! - 45th <span style="float: right;">*2024-01*</span>
* 2023 ICPC Seoul Regional - 49th <span style="float: right;">*2023-11*</span>
* Academic Excellence Scholarship (GIST) <span style="float: right;">*2023 - 2025*</span>
* Government Sponsored Scholarship (GIST) <span style="float: right;">*2023 - Present*</span>
    
