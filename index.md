---
layout: project_page
permalink: /

title: "HazeFlow: Revisit Haze Physical Model as ODE and Non-Homogeneous Haze Generation for Real-World Dehazing"
authors:
    Junseong Shin, Seungwoo Chung, Yunjeong Ynag, Tae Hyun Kim
affiliations:
    VILAB, Hanyang University
paper: 
code: https://github.com/cloor/HazeFlow
---

<!-- Using HTML to center the abstract -->
<div class="columns is-centered has-text-centered">
    <div class="column is-four-fifths">
        <h2>Abstract</h2>
        <div class="content has-text-justified">
Dehazing involves removing haze or fog from images to restore clarity and improve visibility by estimating atmospheric scattering effects. 
While deep learning methods show promise, the lack of paired real-world training data and the resulting domain gap hinder generalization to real-world scenarios.
In this context, physics-grounded learning becomes crucial; however, traditional methods based on the Atmospheric Scattering Model (ASM) often fall short in handling real-world complexities and diverse haze patterns.
To solve this problem, we propose HazeFlow, a novel ODE-based framework that reformulates ASM as an ordinary differential equation (ODE). 
Inspired by Rectified Flow (RF), HazeFlow learns an optimal ODE trajectory to map hazy images to clean ones, enhancing real-world dehazing performance with only a single inference step. 
Additionally, we introduce a non-homogeneous haze generation method using Markov Chain Brownian Motion (MCBM) to address the scarcity of paired real-world data. 
By simulating realistic haze patterns through MCBM, we enhance the adaptability of HazeFlow to diverse real-world scenarios. 
Through extensive experiments, we demonstrate that HazeFlow achieves state-of-the-art performance across various real-world dehazing benchmark datasets.
        </div>
    </div>
</div>

---
![](/static/image/unpaired.png)
---
## Key Ideas 
![ASM](/static/image/ASM6.png)
Illustration of dehazing trajectory of hazy image IT as transmission map T gradually increases from 0 to 1.

## Method 

## Non-Homogeneous Haze Generation

## Tables 

### Unpaired Dataset 
![](/static/image/main_table.png)

### Paired DAtaset 
![](/static/image/paired_table.png)


## Citation
```
@article{shin2025hazeflow,
    title={HazeFlow: Revisit Haze Physical Model as ODE and Realistic Non-Homogeneous Haze Generation for Real-World Dehazing},
    author={Junseong Shin and Seungwoo Chung and Yunjeong Yang and Tae Hyun Kim},
    journal={ICCV},
    year={2025}
}
```
