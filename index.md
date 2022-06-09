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
    src="Figures/PDV_overview.png" align="center">
</p>

## Abstract
Maintaining an up-to-date map to reflect recent changes in the scene is very important, particularly in situations involving repeated traversals by a robot operating in an environment over an extended period. Undetected changes may cause a deterioration in map quality, leading to poor localization, inefficient operations, and lost robots. Volumetric methods, such as truncated signed distance functions (TSDFs), have quickly gained traction due to their real-time production of a dense and detailed map, though map updating in scenes that change over time remains a challenge. We propose a framework that introduces a novel probabilistic object state representation to track object pose changes in semi-static scenes. The representation jointly models a stationarity score and a TSDF change measure for each object. A Bayesian update rule that incorporates both geometric and semantic information is derived to achieve consistent online map maintenance. To extensively evaluate our approach alongside the state-of-the-art, we release a novel real-world dataset in a warehouse environment. We also evaluate on the public ToyCar dataset. Our method outperforms state-of-the-art methods on the reconstruction quality of semi-static environments. The dataset is available [here](https://github.com/TRAILab/PDV).

---
## Paper
**[POCD: Probabilistic Object-Level Change Detection and Volumetric Mapping in Semi-Static Scenes](https://arxiv.org/abs/2205.01202)**\
[Veronica Chatrath](https://scholar.google.com/citations?user=aPx2zd8AAAAJ&hl=en), [Tianshu Kuai](https://scholar.google.com/citations?user=mFQ8ICgAAAAJ&hl=en), and [Steven L. Waslander](https://scholar.google.com/citations?user=jY_Bcd8AAAAJ&hl=en)\
CVPR 2022
```
@article{PDV,
    title={Point Density-Aware Voxels for LiDAR 3D Object Detection},
    author={Jordan S. K. Hu and
            Tianshu Kuai and
            Steven L. Waslander},
    journal={CVPR},
    year={2022}
}
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
