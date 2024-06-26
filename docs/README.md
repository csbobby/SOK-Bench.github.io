## SOK-Bench
[SOK-Bench Homepage](http://sokbench.csail.mit.edu)  
**[CVPR 2024] [SOK-Bench: A Situated Video Reasoning Benchmark with Aligned Open-World Knowledge](https://arxiv.org/abs/2405.09713)**

Our work aims to delve deeper into reasoning evaluations, specifically within dynamic, open-world, and structured context knowledge. 
We propose a new benchmark, consisting of 44K questions and 10K situations with instance-level annotations depicted in the videos. The reasoning process is required to understand and apply situated knowledge and general knowledge for problem-solving.
The task generation is facilitated through multiple dialogues as iterations and subsequently corrected and refined by our designed self-promptings and demonstrations.
With a corpus of both explicit situated facts and implicit commonsense, we generate associated question-answer pairs and reasoning processes, finally followed by manual reviews for quality assurance.

<!-- 
Reasoning from visual dynamics scenes has many real-world applications. However, existing video reasoning benchmarks are still inadequate since they were mainly designed for factual or situated reasoning and rarely involve broader knowledge in the real world.
-->

## Benchmark Overview
* 44k Situated Questions
* 12 Qutestion Types
* 10k Situation Video Clips
* Situation Commonsense Knowledge Graphs
* Reasoning Rationals

<div align="center">
<img src="../imgs/fig_overview.png" width="800" >
</div>

## Data Download

To download the dataset, please refer to the [SOK-Bench Dataset](https://github.com/csbobby/SOK-Bench?tab=readme-ov-file#data-download) 

## Citation
Please link back and cite the work if you would like to use the website template.
```BibTeX
@inproceedings{SOK_Bench,
author={Wang*, Andong and Wu*, Bo and Chen, Sunli and Chen, Zhenfang and Guan, Haotian and Lee, Wei-Ning and Li, Erran Li and Tenenbaum, Joshua B and Gan, Chuang},
title = {SOK-Bench: A Situated Video Reasoning Benchmark with Aligned Open-World Knowledge},
booktitle = {The IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
year = {2024}
}
```
