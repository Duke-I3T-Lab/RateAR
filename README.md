<div align="center">
  
# RateAR Dataset
  
### Harnessing Vision-Language Models for Perceptual Quality Assessment and Autonomous Content Adjustment in Augmented Reality

[![Workshop](https://img.shields.io/badge/ACM%20VRST-2026-0085CA)](https://vrst.acm.org/vrst2026/)
[![DOI](https://img.shields.io/badge/DOI-10.1145%2F3822517.3848685-FAB70C)](https://doi.org/10.1145/3822517.3848685)
[![HF_Dataset](https://img.shields.io/badge/Dataset-Download-FFD21E?logo=huggingface)](https://huggingface.co/datasets/I3TDataset/RateAR)
[![I3T_Lab](https://img.shields.io/badge/-I3T%20Lab-012169?logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiPz4KPHN2ZyBpZD0ibG9nby0yIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZlcnNpb249IjEuMSIgdmlld0JveD0iMCAwIDQwMC45MyA0NTUuOTIiPgogIDwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAzMC44LjEsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiAyLjEuNCBCdWlsZCAxKSAgLS0+CiAgPGRlZnM+CiAgICA8c3R5bGU+CiAgICAgIC5zdDAgewogICAgICAgIGZvbnQtc2l6ZTogNzJweDsKICAgICAgfQoKICAgICAgLnN0MCwgLnN0MSwgLnN0MiB7CiAgICAgICAgaXNvbGF0aW9uOiBpc29sYXRlOwogICAgICB9CgogICAgICAuc3QwLCAuc3QzLCAuc3QyIHsKICAgICAgICBmaWxsOiAjZmZmOwogICAgICB9CgogICAgICAuc3QwLCAuc3QyIHsKICAgICAgICBmb250LWZhbWlseTogQXJpYWwtQm9sZE1ULCBBcmlhbDsKICAgICAgICBmb250LXdlaWdodDogNzAwOwogICAgICB9CgogICAgICAuc3QyIHsKICAgICAgICBmb250LXNpemU6IDcyLjE3cHg7CiAgICAgIH0KICAgIDwvc3R5bGU+CiAgPC9kZWZzPgogIDxwYXRoIGNsYXNzPSJzdDMiIGQ9Ik0zNDYuOTEsMjYwLjkzbC0uMDMtNjYuMjJjMC01LjA5LDMuMDctOS43LDcuODEtMTEuNTcsMTUuODYtNi4yNywyNi45My0yMi4wNCwyNi4xOS00MC4zLS44OC0yMS41Ny0xOC41OS0zOS4wOC00MC4xNy0zOS43Mi0yMy40OC0uNy00Mi43NCwxOC4xMy00Mi43NCw0MS40NXYuMDdjMCw0LjQ2LTIuMjMsOC42My02LjA2LDEwLjkybC01OS4yNywzNS41MmMtMy43NywyLjI2LTguNDgsMi40OC0xMi4zMy4zNy01LjktMy4yMy0xMi42Ni01LjA2LTE5Ljg1LTUuMDZzLTEzLjk2LDEuODQtMTkuODUsNS4wNmMtMy44NSwyLjExLTguNTYsMS44OS0xMi4zMi0uMzdsLTU5LjI5LTM1LjYzYy0zLjgyLTIuMy02LjA2LTYuNDYtNi4wNS0xMC45MnYtLjEzYzAtMi4yNi0uMTgtNC40OC0uNTMtNi42NC0uODEtNS4wNCwxLjY4LTEwLjA1LDYuMDYtMTIuNjdsNTIuODEtMzEuNTFjNC4zNi0yLjYsOS44OS0yLjMzLDEzLjkyLjc3LDcuNjIsNS44NiwxNy4zMyw5LjE0LDI3LjgyLDguNTEsMjEuNDgtMS4zLDM4LjU5LTE5LjI2LDM4LjktNDAuNzguMzQtMjMuMzQtMTguNjItNDIuMzQtNDEuOTUtNDIuMDgtMjEuNzEuMjUtMzkuOCwxNy41OC00MC45MywzOS4yNS0uMTYsMy4wMiwwLDUuOTcuNDcsOC44Mi44MSw1LjAyLTEuNTYsMTAuMDItNS45MywxMi42M2wtNTIuOTQsMzEuNTljLTQuMzYsMi42LTkuODksMi4zMy0xMy45Mi0uNzctNy42Mi01Ljg2LTE3LjMzLTkuMTQtMjcuODMtOC41MS0yMS4yNCwxLjI4LTM4LjI1LDE4Ljg3LTM4Ljg4LDQwLjEzLS43LDIzLjQ4LDE4LjEzLDQyLjczLDQxLjQ1LDQyLjczLDcuMTgsMCwxMy45My0xLjgzLDE5LjgyLTUuMDUsMy44NS0yLjEsOC41NS0xLjg4LDEyLjMxLjM4bDU5LjM0LDM1LjY2YzMuODIsMi4zLDYuMDYsNi40Niw2LjA1LDEwLjkydi4wOGMwLDE1LjIxLDguMTksMjguNDksMjAuMzksMzUuNzEsMy43OCwyLjIzLDYuMDgsNi4zMSw2LjA4LDEwLjcxdjczLjdjMCw0LjM2LTIuMjIsOC40OS01Ljk4LDEwLjctMS40My44NC0yLjgsMS43Ni00LjExLDIuNzYtNC4wNCwzLjA3LTkuNDksMy41MS0xMy44NC45bC01My4wNi0zMS44M2MtNC4zNi0yLjYyLTYuNzItNy42Mi01LjktMTIuNjQuNTUtMy4zNy42OS02Ljg5LjM3LTEwLjQ4LTEuODItMjAuNDYtMTguNzUtMzYuNjctMzkuMjctMzcuNjUtMjQuMDQtMS4xNS00My44NSwxOC4xOC00My41LDQyLjA1LjMyLDIxLjUsMTcuMzksMzkuNDUsMzguODUsNDAuNzYsMTAuNDguNjQsMjAuMTctMi42MSwyNy43OS04LjQ0LDQuMDQtMy4wOSw5LjU3LTMuMzUsMTMuOTMtLjc0bDUyLjg5LDMxLjczYzQuMzYsMi42Miw2LjcyLDcuNjIsNS45LDEyLjY0LS41NSwzLjM3LS42OSw2Ljg5LS4zNywxMC40OCwxLjc5LDIwLjE0LDE4LjI1LDM2LjI0LDM4LjQzLDM3LjYsMjQuMjEsMS42Myw0NC4zNS0xNy41Miw0NC4zNS00MS4zNywwLTE1LjIxLTguMTktMjguNDktMjAuMzktMzUuNzEtMy43OC0yLjIzLTYuMDgtNi4zMS02LjA4LTEwLjcxdi03My43NWMwLTQuMzksMi4zLTguNDcsNi4wOC0xMC43MSwxMi4yLTcuMjIsMjAuMzktMjAuNSwyMC4zOS0zNS43MXYtLjA3YzAtNC40NiwyLjIzLTguNjMsNi4wNi0xMC45Mmw1OS4zNS0zNS41N2MzLjc0LTIuMjQsOC40LTIuNDMsMTIuMjMtLjM0LDEuMzkuNzYsMi44MywxLjQ1LDQuMzIsMi4wNSw0Ljc4LDEuOTQsOCw2LjQ2LDgsMTEuNjFsLjAzLDY2LjQyYzAsNS4wOC0zLjA2LDkuNjktNy43OCwxMS41Ni0xNS44NCw2LjI5LTI2Ljg4LDIyLjA1LTI2LjEyLDQwLjMuODksMjEuNTYsMTguNiwzOS4wNSw0MC4xNiwzOS42OSwyMy40OC43LDQyLjc0LTE4LjEzLDQyLjc0LTQxLjQ1LDAtMTcuNTItMTAuODctMzIuNS0yNi4yMy0zOC41Ny00Ljc0LTEuODctNy43Ni02LjU2LTcuNzYtMTEuNjVoLS4wM1oiLz4KICA8ZyBjbGFzcz0ic3QxIj4KICAgIDx0ZXh0IGNsYXNzPSJzdDIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDExMi4zNCAyODMuMzkpIHJvdGF0ZSgzMCkgc2NhbGUoMS4xNSAuODcpIHNrZXdYKDIzLjQxKSI+PHRzcGFuIHg9IjAiIHk9IjAiPkk8L3RzcGFuPjwvdGV4dD4KICA8L2c+CiAgPGcgY2xhc3M9InN0MSI+CiAgICA8dGV4dCBjbGFzcz0ic3QwIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNzIuNjkgMTY5LjY2KSI+PHRzcGFuIHg9IjAiIHk9IjAiPjM8L3RzcGFuPjwvdGV4dD4KICA8L2c+CiAgPGcgY2xhc3M9InN0MSI+CiAgICA8dGV4dCBjbGFzcz0ic3QyIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgyNTIuNzMgMzA1Ljk2KSByb3RhdGUoLTMwKSBzY2FsZSgxLjE1IC44Nykgc2tld1goLTIzLjQxKSI+PHRzcGFuIHg9IjAiIHk9IjAiPlQ8L3RzcGFuPjwvdGV4dD4KICA8L2c+Cjwvc3ZnPg==&labelColor=555555)](https://gorlatova.pratt.duke.edu)
[![BibTeX](https://img.shields.io/badge/Citation-bibtex-FA8128)](#6)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

[**Elias Rotondo**](https://scholar.google.com/citations?user=wA64idUAAAAJ) · [**Lin Duan**](https://scholar.google.com/citations?user=3KGmyogAAAAJ) · [**Yanming Xiu**](https://ym-xiu.github.io) · [**Sangjun Eom**](https://scholar.google.com/citations?user=4CRAKIkAAAAJ) · [**Conrad Li**](https://scholar.google.com/citations?user=uFtayb4AAAAJ) · [**Maria Gorlatova**](https://maria.gorlatova.com/bio/)

<!-- [*Intelligent Interactive Internet of Things (I³T) Lab*](https://gorlatova.pratt.duke.edu) -->

</div>

## 📖 Introduction

This repository accompanies the conference paper ["_Harnessing Vision-Language Models for Perceptual Quality Assessment and Autonomous Content Adjustment in Augmented Reality_"](https://doi.org/10.1145/3822517.3848685), published in the 32nd ACM Symposium on Virtual Reality Software and Technology (VRST `26). It introduces **RateAR**, a dataset of 321 AR images and 112 AR videos collected using various hardware platforms and user scenarios.

<span id="fig1"><p align="center"><img width="600" alt="Representative examples from the RateAR dataset illustrating various quality levels across three key visual features: placement plausibility, size appropriateness, and shadow realism." src="https://github.com/Duke-I3T-Lab/RateAR/blob/main/RateAR_samples.png"></p></span>
<p align="center">Figure 1: RateAR dataset examples illustrating varying quality across three features: (a) <i>Placement plausibility:</i> virtual desk floating feet above (poor), inches above (fair), or level with the ground (good); (b) <i>Size appropriateness:</i> digital car appearing far too small (poor), slightly small (fair), or realistically sized (good); and (c) <i>Shadow realism:</i> AR noodle bowl shadow opposing the real lighting (poor), slightly misaligned (fair), or fully aligned (good).</p> 

## 📋 Outline:
* [Dataset Composition](#1)
* [Collection Process](#2)
* [RateAR Hierarchical Structure](#3)
* [Dataset Download](#4)
* [Supplemental Materials](#5)
* [Citation](#6)
* [Contacts](#7)
* [Acknowledgments](#8)

<!-- The rest of the repository is organized as follows. [**Section 1**](#1) introduces the details the collection process. [**Section 2**](#2) presents the dataset composition. [**Section 3**](#3) describes the dataset structure. [**Section 4**](#4) provides the download link to the full dataset. The citation information, author contacts, and acknowledgments are introduced in [**Section 5**](#5), [**Section 6**](#6), and [**Section 7**](#7).  -->

## 📓 <span id="1"> Dataset Composition</span>
The RateAR dataset comprises 321 AR images and 112 AR videos, curated to diversify the visual quality levels among influential user immersion properties. [Figure 1](#fig1) presents representative examples from RateAR, illustrating a range of quality levels across three key visual factors: placement plausibility, size appropriateness, and shadow realism.

## 🔎 <span id="2"> Collection Process</span> 
_AR Platforms:_ AR samples are sourced from a range of devices and scenarios. 321 AR images are collected from **DiverseAR+** [[Duan et al., 2025](https://doi.org/10.1109/MIC.2025.3622505)], selected for their varying rendering qualities in virtual content placement, shadow, and size. All RateAR image instances were captured using Android smartphones (250), Apple Vision Pro (40), and Microsoft HoloLens 2 (31). A diverse collection of environments are featured, including bedrooms, kitchens, living rooms, medical offices, reading rooms, research labs, and study rooms. The 112 AR videos were captured by us to represent a similar distribution of quality feature variations, showcasing settings such as basements, bedrooms, living rooms, and research labs. All RateAR videos are recorded using Meta Quest 3.

_Context-Dependent Scenarios:_ Alongside common settings such as bedrooms and kitchens, where assessing visual factors primarily relies on general, publicly shared knowledge, RateAR also includes scenes that require context-dependent reasoning for evaluation. For example, medical settings feature virtual organ models placed in anatomically accurate locations on human subjects or 3D-printed models (e.g., a skull). In these scenarios, the placement plausibility and size appropriateness of virtual content is most critical, while elements like shadow realism are less relevant for perceived quality. Additionally, we include scenarios that capture dynamic user interactions, such as a hand shown bouncing a virtual basketball. As a result, some examples with observed floating AR content may be contextually appropriate, therefore receiving a high placement plausibility score.

_Human Subjective Quality Score Labeling:_ Four graduate students with experience designing, developing, and evaluating AR systems rated placement plausibility, size appropriateness, and shadow realism using a Python notebook GUI. Before labeling samples, the annotators discussed the target quality features and expectations for handling nuanced edge cases, such as what score to assign when a virtual object without an accompanying shadow was visually appropriate (e.g., anatomical models). As needed, subsequent consensus meetings remediated annotator conceptual disagreements. Modeled after the International Telecommunication Union's (ITU) Absolute Category Rating guidelines, a 5-point discrete scale was employed. An assignment of $1$ signifies *poorly* rendered feature quality, while a score of $5$ indicates *good* or exceptional visual appearance. After the initial annotation period, we recruited a fifth student with a background in image analysis applications to expand the label set to five ratings per sample. The final annotator received reference materials summarizing the earlier group's discussions to align evaluation standards. All annotators assigned quality labels for each AR content factor, per sample, resulting in $6,495$ annotations. The mean opinion scores (MOSs) are reported and used as final ratings in our evaluations.

_Inter-Annotator Reliability:_ To measure inter-annotator reliability, we computed the intraclass correlation coefficients (ICC) for each labeled quality feature based on a two-way random-effects model, average measures, and absolute agreement using the `Pingouin` open-source Python package. The model for placement plausibility yielded $ICC(2,5) = .95,\ 95\%\ CI[.94, .96],\ F(432, 1728) = 22.20,\ p < .001$, supporting excellent reliability. Similarly, we observe comparable excellent reliability for the size appropriateness labels, with an $ICC(2,5) = .94,\ 95\%\ CI[.93, .95],\ F(432, 1728) = 16.55,\ p < .001$. Lastly, the shadow realism annotation analysis returns an $ICC(2,5) = .90,\ 95\%\ CI[.87, .92],\ F(432, 1728) = 11.15,\ p < .001$, indicating good to excellent reliability.

## 🏗️ <span id="3"> RateAR Hierarchical Structure</span>
The dataset follows the hierarchical file structure shown below:
```
dataset
└───rateAR_images
│   └───rateAR_image_metadata_mos.csv
│   └───AVP
│   │   └───AVP_can
│   │   │   └───AVP_can_1_ar.png
│   │   │   ...
│   │   ...
│   └───andriod
│   ...
└───rateAR_videos
│   └───rateAR_video_metadata_mos.csv
│   └───livingroom
│   │   └───livingroom_tire_1_1_1.mp4
│   │   ...
│   └───dorm
│   ...
```

## ⏬ <span id="4"> Dataset Download</span> 
The full RateAR dataset is made publicly available on [Hugging Face Datasets](https://huggingface.co/datasets/I3TDataset/RateAR).

### Download Options: 1️⃣ Python (`huggingface_hub`) 
Using a Python script, directly download the entire dataset (including all subdirectories) using the official Hugging Face Hub API:
```python
from huggingface_hub import snapshot_download

snapshot_download(
    repo_id="I3TDataset/RateAR", 
    repo_type="dataset", 
    local_dir="./RateAR", # Save dataset within working dir
)
```

### Download Options: 2️⃣ Hugging Face CLI
The RateAR dataset can also be downloaded locally using Hugging Face's official command-line interface:
1. Intall the Hugging Face Hub tool
   ```bash
   pip install huggingface_hub
   ```
2. Download the dataset to the target local directory (e.g., "./RateAR")
   ```bash
   hf download I3TDataset/RateAR --repo-type dataset --local-dir ./RateAR
   ```

## 📚 <span id="5"> Supplemental Materials</span> 

In addtion to releasing the RateAR dataset, we also make publicly available supplemental materials related to the labeling of the dataset, conducted evaluations (including the user study), and ablation study. Below, we provide short document summaries introducing such materials or references to subdirectories that address related files. 

- `rateAR_annotation_instructions.pdf`: High-level instructions provided to the final dataset annotator, reflecting the consensuses held by the initial group of labelers.
- `representative_gpt5.4_verbatim_responses.pdf`: Two representative examples demonstrating how VLMs (in this case, GPT-5.4) can contextualize AR scenes and reason about a virtual object's target feature before returning a score rating (on a 1-5 scale).
- `content_adjustment_pipeline_vlm_prompts.pdf`: The placement and size task prompts provided to the VLM model for the prototype autonomous content adjustment system.
- [user_study_resources subdirectory](https://github.com/Duke-I3T-Lab/RateAR/blob/main/user_study_resources): Files related to the conducted user study evaluating the proposed AR content adjustment pipeline.
- [ablation_study_resources subdirectory](https://github.com/Duke-I3T-Lab/RateAR/blob/main/ablation_study_resources): Prompt groupings analyzed during the prompt engineering ablation study.

## 📑 <span id="6"> Citation</span>

If you use the RateAR dataset in any capacity, please cite: 
```bibtex
@inproceedings{rotondo2026ratear,
  author = {Rotondo, Elias and Duan, Lin and Xiu, Yanming and Eom, Sangjun and Li, Conrad, and Gorlatova, Maria},
  title = {Harnessing Vision-Language Models for Perceptual Quality Assessment and Autonomous Content Adjustment in Augmented Reality},
  year = {2026},
  isbn = {9798400728112},
  publisher = {Association for Computing Machinery},
  address = {New York, NY, USA},
  url = {https://doi.org/10.1145/3822517.3848685},
  doi = {10.1145/3822517.3848685},
  booktitle = {Proceedings of the 2026 32nd ACM Symposium on Virtual Reality Software and Technology},
  location = {Sendai, Japan},
  series = {VRST '26}
}
```
## 📧 <span id="7"> Contacts</span> 
For questions relating to this repository, the associated paper, or the shared dataset, please contact:
- **Elias Rotondo** - eli [DOT] rotondo [AT] duke [DOT] edu

## ❤️ <span id="8"> Acknowledgments</span> 

We thank the participants of our user study for their invaluable help in this research and Tanish Pentakota for assistance implementing baselines.

This work was supported in part by NSF grants CSR-2312760, CNS-2112562, and IIS-2231975, NSF CAREER Award IIS-2046072, NSF NAIAD Award 2332744, a CISCO Research Award, a Meta Research Award, Defense Advanced Research Projects Agency Young Faculty Award HR0011-24-1-0001, and the Army Research Laboratory under Cooperative Agreement Number W911NF-23-2-0224. The views and conclusions contained in these works are those of the authors. They should not be interpreted as representing the official policies, either expressed or implied, of the Defense Advanced Research Projects Agency, the Army Research Laboratory, or the U.S. Government. This resource has been approved for public release; distribution is unlimited. No official endorsement should be inferred. The U.S. Government is authorized to reproduce and distribute reprints for Government purposes, notwithstanding any copyright notation herein.

## 📜 <span id="9"> License</span>
This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org).
