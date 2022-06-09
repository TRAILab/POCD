---
title: POCD: Probabilistic Object-Level Change Detection and Volumetric Mapping in Semi-Static Scenes
---

<style>
.row {
  display: flex;
}

/* Create three equal columns that sits next to each other */
.column {
  flex: 33.33%;
  padding: 0px;
}
</style>

## Overview
<p style="text-align:center;"><img
    src="Figures/POCD_pipeline.pdf" align="center">
</p>

## Abstract
Maintaining an up-to-date map to reflect recent changes in the scene is very important, particularly in situations involving repeated traversals by a robot operating in an environment over an extended period. Undetected changes may cause a deterioration in map quality, leading to poor localization, inefficient operations, and lost robots. Volumetric methods, such as truncated signed distance functions (TSDFs), have quickly gained traction due to their real-time production of a dense and detailed map, though map updating in scenes that change over time remains a challenge. We propose a framework that introduces a novel probabilistic object state representation to track object pose changes in semi-static scenes. The representation jointly models a stationarity score and a TSDF change measure for each object. A Bayesian update rule that incorporates both geometric and semantic information is derived to achieve consistent online map maintenance. To extensively evaluate our approach alongside the state-of-the-art, we release a novel real-world dataset in a warehouse environment. We also evaluate on the public ToyCar dataset. Our method outperforms state-of-the-art methods on the reconstruction quality of semi-static environments. The dataset is available [here](https://github.com/Viky397/TorWICDataset).

---
## Paper
**[POCD: Probabilistic Object-Level Change Detection and Volumetric Mapping in Semi-Static Scenes](https://arxiv.org/abs/2205.01202)**\
[Jingxing Qian](https://scholar.google.com/citations?user=OZk7X80AAAAJ&hl=en&authuser=1), [Veronica Chatrath](https://scholar.google.com/citations?user=yRjO8GYAAAAJ&hl=en&authuser=1), [Jun Yang](https://scholar.google.com/citations?user=kf0gAOAAAAAJ&hl=en), [James Servos](https://scholar.google.com/citations?hl=en&authuser=1&user=S-cpmfYAAAAJ), [Angela P. Schoellig](https://scholar.google.com/citations?user=QMfeRz0AAAAJ&hl=en&authuser=1), and [Steven L. Waslander](https://scholar.google.com/citations?user=jY_Bcd8AAAAJ&hl=en)\
RSS 2022

```bibtex
@INPROCEEDINGS{QianChatrathPOCD,
  author={Qian, Jingxing and Chatrath, Veronica and Yang, Jun and Servos, James and Schoellig, Angela and Waslander, Steven L.},
  booktitle={2022 Robotics: Science and Systems (RSS)}, 
  title={{POCD: Probabilistic Object-Level Change Detection and Volumetric Mapping in Semi-Static Scenes}}, 
  year={2022},
  volume={},
  number={},
  pages={},
  doi={}}
```
```

---
## Affiliations
<div class="row">
  <div class="column">
    <a href="https://robotics.utoronto.ca/">
        <img src="Figures/UofT.png" alt="Snow" style="width:80%; align:left">
    </a>
  </div>
  <div class="column">
    <a href="https://www.trailab.utias.utoronto.ca/">
        <img src="Figures/trailab.svg" alt="Forest" style="width:75%">
    </a>
  </div>
</div>
<hr style="height:60px; visibility:hidden;" />
