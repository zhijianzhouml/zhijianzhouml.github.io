---
layout: about
title: About
permalink: /
subtitle: PhD Candidate in Machine Learning

profile:
  align: right
  image: image202401.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
#    <p>555 your office number</p>
#    <p>123 your address street</p>
#    <p>Your City, State 12345</p>

news: true  # includes a list of news items
latest_posts: false  # includes a list of the newest posts
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---

Hi, there! I am a second-year PhD candidate at <a href="https://github.com/tmlr-group">TMLR Group</a> in the <a href="https://eng.unimelb.edu.au/">Faculty of Engineering and Information Technology, the University of Melbourne</a>, advised by <a href="https://scholar.google.com.au/citations?user=eqe3JS8AAAAJ&hl=en&oi=ao">Dr. Feng Liu</a> and <a href="https://sites.google.com/view/liuhua-peng">Dr. Liuhua Peng</a>. I received my Master's degree from the <a href="https://ai.nju.edu.cn/">School of Artificial Intelligence</a> at <a href="https://www.nju.edu.cn/en/">Nanjing University</a> in 2024, where I was supervised by <a href="https://www.lamda.nju.edu.cn/gaow/">Dr. Wei Gao</a> and was a member of the <a href="https://www.lamda.nju.edu.cn/MainPage.ashx">LAMDA Group</a>, led by Professor <a href="https://cs.nju.edu.cn/zhouzh/">Zhihua Zhou</a>. Prior to that, I received my B.Eng. degree in Transportation Engineering from <a href="https://en.dlut.edu.cn/">Dalian University of Technology</a> in 2021. 

My research interests focus on making hypothesis testing usable for modern machine learning problems:
<ul>
  <li>
    <strong>Single-example testing for probabilistic ML outputs.</strong>
    Most classical statistical tests are designed for batch samples, while many ML applications require decisions on individual examples with probabilistic outputs. This motivates my research on single-example testing methods that provide per-example statistical significance and theoretical false-alarm control.
  </li>
  <li>
    <strong>Data-adaptive, learnable testing beyond rigid hypothesis specification.</strong>
    Conventional hypothesis testing requires specifying formal hypotheses in advance and then designing a test statistic, which often forces ML problems into restrictive statistical formulations and limits practical adoption. My research aims to build learnable testing frameworks in which both the test statistic and the testing procedure are constructed from data, enabling rigorous evaluation of a broader class of questions.
  </li>
  <li>
    <strong>Certified LLM safety and evaluation.</strong>
    Modern LLM safety and evaluation often rely on empirical pipelines without rigorous finite-sample guarantees, particularly in adaptive and label-efficient settings. My current research focuses on certified and cost-efficient LLM evaluation and certified detection of training data contamination, aiming to develop theory-driven methods with finite-sample validity and provable error control for LLM evaluation and safety assessment.
  </li>
</ul>