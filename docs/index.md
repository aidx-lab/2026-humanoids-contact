---
layout: page
title: 
---

This site complements the paper 
[**Bayesian In-Situ Joint-Torque Sensor Calibration for Robotic Hands via Self-Consistency under Contact Constraints**]() by
[Leon Sievers](https://scholar.google.com/citations?user=y-MzVoUAAAA) and 
[Berthold Bäuml](https://scholar.google.com/citations?user=fjvpDsEAAAAJ) presented at the 
_2026 IEEE-RAS International Conference on Humanoid Robots_ in 
San Jose, CA, USA.


<p align="center">
<div class="video-wrap">
  <div class="video-container">
    <iframe width="728" height="410" src="https://www.youtube.com/embed/vMVYQFsNbLg?si=lwlt9IBrGh2NmBY0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    </div>
  <style>
  .video-container {
  position: relative;
  overflow: hidden;
  height: 0;
  padding-bottom: 56.25%; /* creates a 16:9 aspect ratio */
}

.video-container iframe,
.video-container embed {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  max-width: 100%;
}

/* And set the max-width of the parent element */
.video-wrap {
  width: 100%;
  max-width: 1600px;
}
</style>
</div>
  </p>

# Abstract
---
Dexterous manipulation with multi-fingered robotic hands depends on the precise control of contact forces. For torque-controlled hands, achieving the necessary reliability and—especially for learning in simulation—successful sim-to-real transfer relies heavily on accurately calibrated torque sensing. Conventional calibration methodologies, however, are notoriously tedious, often demanding specialized external measurement hardware and partial system disassembly. This paper introduces a novel, autonomous approach that calibrates a complete multi-fingered hand in situ within minutes, simply through pairwise fingertip contacts in multiple configurations and with at most a single external reference for metric scaling. The proposed framework exploits the fact that a low-dimensional contact wrench induces a self-consistency constraint on the joint torques of the involved fingers, completely bypassing the need to know the wrench's actual value. Building on this, we present a thorough Bayesian formulation that accounts for sensor and contact-model uncertainty, integrates optional external measurements, and conduct a comprehensive observability analysis. In experiments with the DLR Hand II, our automated procedure achieves a precision on par with the manual benchmark—which requires disassembling the hand—resulting in a force error of only 0.39 N at the fingertip.


---
Cite this paper as: 

    @inproceedings{Sievers2026,
        author = {Leon Sievers and Berthold B{\"a}uml},
        title = {Bayesian In-Situ Joint-Torque Sensor Calibration for Robotic Hands via Self-Consistency under Contact Constraints},
        booktitle = {IEEE-RAS International Conference on Humanoid Robots (Humanoids)},
        year = {2026}}

[arxiv](https://arxiv.org/abs/2311.03957)
