---
permalink: /
title: ""
excerpt: "Ke Jin is a master's student in Computer Science at Washington University in St. Louis."
author_profile: true
analytics: false
redirect_from:
  - /about/
  - /about.html
---

<span class="anchor" id="about"></span>
<span class="anchor" id="about-me"></span>


<p>I am a <strong>master’s student in Computer Science</strong> at <a href="https://washu.edu/" target="_blank" rel="noopener noreferrer">Washington University in St. Louis</a>. I received my B.Eng. in Computer Science and Technology from Zhejiang A&amp;F University.</p>

<p>My research and coursework span gravitational-wave data analysis, language-model verification, reinforcement learning, and clinical and tabular prediction. Across these projects, I study how data preparation, training strategies, and evaluation design affect model behavior, predictive performance, and computational cost.</p>


<span class="anchor" id="research"></span>

# 💻 Research and Project Focus


<ul>
          <li><strong>Reliable machine learning:</strong> Synthetic-to-real transfer and evaluation on real-world data.</li>
          <li><strong>Language-model verification:</strong> Verification cost and probability-bound precision under computational constraints.</li>
          <li><strong>Reinforcement learning:</strong> Curriculum learning and reward design for navigation under disturbances.</li>
          <li><strong>Predictive modeling:</strong> Longitudinal clinical data, early-warning methods, and task-dependent model selection.</li>
        </ul>


<span class="anchor" id="projects"></span>

# 📝 Selected Projects


<span class="anchor" id="dexterous-hand-g1"></span>

<div class="paper-box">
<div class="paper-box-image"><div style="width:100%;max-width:400px"><video autoplay loop muted playsinline preload="metadata" width="1280" height="720" style="display:block;width:100%;height:auto;box-shadow:3px 3px 6px #888" aria-label="High-precision dexterous hand integration with G1 demonstration"><source src="灵巧手展示.mp4" type="video/mp4">Your browser does not support embedded video. <a href="灵巧手展示.mp4">View the demonstration</a>.</video></div></div>
<div class="paper-box-text" markdown="1">

### High-Precision Dexterous Hand Integration with G1

<p><strong>Ke Jin</strong></p>
<p>This project focuses on integrating a high-precision dexterous hand with G1. The video shows a demonstration of the project.</p>

</div>
</div>


<span class="anchor" id="uav"></span>

<div class="paper-box">
<div class="paper-box-image"><div><img src="UAV.gif" alt="Animated two-dimensional UAV navigation illustration with static and moving obstacles, wind vectors, a starting position, and a goal." width="100%"></div></div>
<div class="paper-box-text" markdown="1">

### PPO-Based UAV Navigation under Dynamic Disturbances

<p><strong>Ke Jin</strong>, Kaidi Chen</p>
<p><em>CSE 5100 Deep Reinforcement Learning · Spring 2026 · Instructor: Chongjie Zhang</em></p>
<p>We studied curriculum learning and reward shaping for PPO-based navigation in a two-dimensional UAV simulation with moving obstacles and random wind disturbances.</p>
<p>My work focused on the training pipeline, reward design, and a seven-stage curriculum. Building on a teammate-developed environment, I also worked on scenario extensions and policy evaluation. Qualitative ablations examined learning behavior and obstacle-clearance preferences.</p>

</div>
</div>


<span class="anchor" id="gw-yolo"></span>

<div class="paper-box">
<div class="paper-box-image"><div><img src="gw-yolo.png" alt="GW150914 H1 time-frequency spectrogram with a catalog-derived chirp label, showing frequency versus time relative to merger." width="100%"></div></div>
<div class="paper-box-text" markdown="1">

### GW-YOLO: Synthetic-to-Real Gravitational-Wave Segmentation

<p><strong>Ke Jin</strong> (corresponding author), Fan Zhang, Yunhan Shen</p>
<p>Building on GW-YOLO, we evaluate synthetic-to-real transfer across six YOLOv8 segmentation training strategies. We compare responses to real gravitational-wave events and false positives on continuous detector noise, examining how synthetic, semi-synthetic, and catalog-derived supervision affect model behavior.</p>
<p>The study also evaluates how background selection and preprocessing change measured false-positive rates and model rankings.</p>

</div>
</div>


<span class="anchor" id="beaver"></span>

<div class="paper-box">
<div class="paper-box-image"><div><a href="beaver-convergence.png" target="_blank" rel="noopener noreferrer"><img src="beaver-convergence.png" alt="Nine convergence plots comparing upper and lower probability bounds for Qwen2.5 14B AWQ, 7B, and 7B AWQ models at temperatures 0.01, 0.3, and 0.9." width="100%"></a></div></div>
<div class="paper-box-text" markdown="1">

### Resource-Constrained Verification of Language-Model Outputs

<p><strong>Ke Jin</strong>, Mingqi Zhang</p>
<p><em>CSE 5370 Trustworthy Autonomy · Spring 2026 · Instructor: Hussein Sibai</em></p>
<p>Using the BEAVER branch-and-bound framework, we examined how sampling temperature, model size, and AWQ quantization affect verification cost and probability-bound precision.</p>
<p>I primarily handled single-GPU deployment, inference-backend configuration, batch experiments, and log organization, and contributed to the analysis of search behavior under limited computational budgets.</p>

</div>
</div>


<span class="anchor" id="aki"></span>

<div class="paper-box">
<div class="paper-box-image"><div><a href="aki-monitoring.png" target="_blank" rel="noopener noreferrer"><img src="aki-monitoring.png" alt="AKI patient monitoring prototype with synthetic demo patient cards, longitudinal observation charts, and prediction displays." width="100%"></a></div></div>
<div class="paper-box-text" markdown="1">

### Dynamic Early Warning of Acute Kidney Injury

<p><strong>Ke Jin</strong>, Brian Du, Jiaju Zheng</p>
<p><em>Fall 2026 · Instructor: Chenyang Lu</em></p>
<p>We are exploring dynamic AKI risk prediction using longitudinal vital signs and laboratory measurements from MIMIC-III. The project considers warning lead time, prediction reliability, and false-alarm burden.</p>
<p>Current work includes experimental design, data preparation, and a local prototype for viewing patient observations and replaying longitudinal records. Predictive modeling remains in development.</p>

</div>
</div>


<span class="anchor" id="bank-marketing"></span>

<div class="paper-box">
<div class="paper-box-image"><div><a href="bank-marketing.png" target="_blank" rel="noopener noreferrer"><img src="bank-marketing.png" alt="Histograms and density curves showing the distributions of ten numerical features in the Bank Marketing dataset." width="100%"></a></div></div>
<div class="paper-box-text" markdown="1">

### Task-Dependent Model Selection for Bank Marketing Data

<p>Kaidi Chen, <strong>Ke Jin</strong>, Yiding Yang</p>
<p><em>CSE 5104 Data Mining · Spring 2026 · Instructor: Cynthia Zhou Ma</em></p>
<p>We compared six classification models across subscription prediction and occupation classification, examining predictive performance alongside training and inference costs.</p>
<p>I primarily worked on exploratory analysis, preprocessing, task definition, feature availability at prediction time, and evaluation splits. The comparisons highlighted task-dependent model selection and the limitations of accuracy under class imbalance.</p>

</div>
</div>



<span class="anchor" id="honors"></span>

# 🎖 Selected Honors and Awards


<ul>
          <li><strong>Third Prize, National Finals</strong>, RoboCom CAIP Programming Competition, 2022.</li>
          <li><strong>Provincial Second Prize</strong>, Lanqiao Cup, 2022, 2023, and 2024.</li>
          <li><strong>Provincial Second Prize</strong>, RoboCom CAIP Programming Competition, 2022.</li>
          <li><strong>Provincial Team Second Prize</strong>, Group Programming Ladder Tournament, 2023.</li>
          <li><strong>Provincial Third Prize</strong>, RAICOM CAIP Programming Competition, 2023.</li>
          <li><strong>Outstanding Graduate</strong>, Zhejiang A&amp;F University, 2025.</li>
          <li><strong>Second-Class Scholarship</strong>, Zhejiang A&amp;F University, 2023 and 2024.</li>
          <li><strong>Research Innovation Award</strong>, Zhejiang A&amp;F University, 2022, 2023, and 2024.</li>
        </ul>


<span class="anchor" id="education"></span>

# 📖 Education


<ul class="education-list">
          <li><strong>Washington University in St. Louis</strong><br>M.S. in Computer Science — currently pursuing</li>
          <li><strong>Zhejiang A&amp;F University</strong><br>B.Eng. in Computer Science and Technology</li>
        </ul>


<span class="anchor" id="additional"></span>

# Additional Information


<p><strong>Programming:</strong> Python, C++, Java.<br><strong>Outside research:</strong> Badminton and swimming.</p>




# Contact


<p><strong>Email:</strong> <a href="mailto:jke@wustl.edu">jke@wustl.edu</a><br><strong>GitHub:</strong> <a href="https://github.com/kejin-cs" target="_blank" rel="noopener noreferrer">github.com/kejin-cs</a></p>
