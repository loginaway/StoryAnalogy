<h1 align="center">StoryAnalogy: Deriving Story-level Analogies from Large Language Models to Unlock Analogical Understanding</h1>
<p align="center">
    <a href="https://huggingface.co/datasets/JoeyCheng/story_analogy"> <img src="https://img.shields.io/badge/%F0%9F%A4%97-Datasets-green"> </a>
    <a href="https://arxiv.org/abs/2310.12874"><img src="https://img.shields.io/badge/arXiv-2310.12874-b31b1b.svg" alt="Paper"></a>
    <a href="https://aclanthology.org/2023.emnlp-main.706/"> <img alt="License" src="https://img.shields.io/static/v1?label=Pub&message=EMNLP%2723&color=blue"> </a>
    <a href="https://github.com/LFhase/PAIR"><img src="https://img.shields.io/badge/-Github-grey?logo=github" alt="Github"></a>
    <!-- <a href="https://colab.research.google.com/drive/1t0_4BxEJ0XncyYvn_VyEQhxwNMvtSUNx?usp=sharing"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Colab"></a> -->
    <a href="https://github.com/LFhase/PAIR/blob/main/LICENSE"> <img alt="License" src="https://img.shields.io/github/license/LFhase/PAIR?color=blue"> </a>
    <!-- <a href="https://neurips.cc/virtual/2022/poster/54643"> <img src="https://img.shields.io/badge/Video-grey?logo=Kuaishou&logoColor=white" alt="Video"></a> -->
    <!-- <a href="https://lfhase.win/files/slides/PAIR.pdf"> <img src="https://img.shields.io/badge/Slides-grey?&logo=MicrosoftPowerPoint&logoColor=white" alt="Slides"></a> -->
    <a href="https://github.com/loginaway/StoryAnalogy/blob/main/raw/Poster%20-%20StoryAnalogy%20Deriving%20Story-level%20Analogies%20from%20Large%20Language%20Models%20to%20Unlock%20Analogical%20Understanding.pdf"> <img src="https://img.shields.io/badge/Poster-grey?logo=airplayvideo&logoColor=white" alt="Poster"></a>
</p>


This repo contains the dataset and code in the EMNLP'23 paper: *[StoryAnalogy: Deriving Story-level Analogies from Large Language Models to Unlock Analogical Understanding](https://arxiv.org/abs/2310.12874)*.


<!-- In this work, we built a story level analogy dataset (**StoryAnalogy**), which could be accessed at `src/data`. -->

<div style="width:60%; text-align:center; float: center;">
    <figure >
        <img src="raw/Analogy.png">
        <figcaption>
            An example analogy between story S1 and S2.
            </figcaption>
    </figure>
</div>

## Use StoryAnalogy
We recommend using Hugging Face's `datasets` to load the story analogy dataset:
```Python
from datasets import load_dataset

dataset = load_dataset("JoeyCheng/story_analogy")
```

## Reproduce the results

We are currently actively preparing the presentation materials and will update the code shortly.

TODO-list

[x] Reframe the dataset with huggingface datasets and present a dataset card.

[ ] Organize & release code for the experiments.
 <!-- A quick-start demo.  -->



## Misc

If you have any questions related to the code or the paper, please feel free to email us at `jchengaj@cse.ust.hk`.

If you use this research, please cite us:
```bibtex
@inproceedings{jiayang2023storyanalogy,
  title={StoryAnalogy: Deriving Story-level Analogies from Large Language Models to Unlock Analogical Understanding},
  author={Jiayang, Cheng and Qiu, Lin and Chan, Tsz and Fang, Tianqing and Wang, Weiqi and Chan, Chunkit and Ru, Dongyu and Guo, Qipeng and Zhang, Hongming and Song, Yangqiu and others},
  booktitle={Proceedings of the 2023 Conference on Empirical Methods in Natural Language Processing},
  pages={11518--11537},
  year={2023}
}
```
