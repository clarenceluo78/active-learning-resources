# active-learning-resources

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of repositories and papers of active learning in various fields (anomaly detection, computer vision, etc.)

## Tabel of Contents
- [Papers](#papers)
  - [Survey](#survey)
  - [Active Anomaly Detection](#active-anomaly-detection)
  - [Active Learning for Computer Vision](#active-learning-for-computer-vision)
- [Code Resources](#code-resources)
  <!-- - [Active Learning in Natural Language Processing](#natural-language-processing) -->



## Papers
- The paper list aims to provide an up-to-date active learning research direction for various fields.
---
### Survey
This is a collection of active learning survey:
| paper | abbr. | publication                | Year                 | Citations |
| ------ | ---- | ------------------------------------------------------------ | -------------------- | ------------------------------------------------------------ |
| [A Survey of Deep Active Learning](https://arxiv.org/pdf/2009.00236) |  |  |          2020        | 232 |
| [A Comparative Survey of Deep Active Learning](https://arxiv.org/pdf/2203.13450) |  |  |          2022        | 8 |

### Active Anomaly Detection
| paper | abbr. | publication                | Year                 | Citations |
| ------ | ---- | ------------------------------------------------------------ | -------------------- | ------------------------------------------------------------ |
| [Active learning for anomaly and rare-category detection](https://proceedings.neurips.cc/paper/2004/file/8c59fd6fbe0e9793ec2b27971221cace-Paper.pdf) | RCD | NIPS | 2004                 | 208 |
| [Incorporating expert feedback into active anomaly discovery](https://web.engr.oregonstate.edu/~tgd/publications/das-wong-dietterich-fern-emmott-incorporating-expert-feedback-into-active-anomaly-discovery-icdm2016.pdf) | LODA-AAD | ICDM | 2016                 | 144 |
| [Incorporating feedback into tree-based anomaly detection](https://arxiv.org/pdf/1708.09441) | AAD | IDEA (KDD Workshop) | 2017                 | 46 |
| [Feedback-Guided Anomaly Discovery via Online Optimization](https://web.engr.oregonstate.edu/~afern/papers/kdd18-siddiqui.pdf) | FIF | KDD | 2018                 | 60 |
| [Deep Active Learning for Anomaly Detection](https://arxiv.org/pdf/1805.09411) | UAI |  | 2018                 | 17 |
| [Interactive anomaly detection on attributed networks](https://dl.acm.org/doi/pdf/10.1145/3289600.3290964) | GraphUCB | WSDM | 2019                 | 75 |
| [Meta-AAD: Active Anomaly Detection with Deep Reinforcement Learning](https://arxiv.org/abs/2009.07415) | Meta-AAD | ICDM | 2020                 | 22 |
---


### Active Learning for Computer Vision
| paper | abbr. | publication                | Year                 | Citations |
| ------ | ---- | ------------------------------------------------------------ | -------------------- | ------------------------------------------------------------ |
| [Mind your outliers! investigating the negative impact of outliers on active learning for visual question answering](https://arxiv.org/abs/2107.02331) |  |  | 2021                 |  |
| [PT4AL: Using Self-Supervised Pretext Tasks for Active Learning](https://arxiv.org/pdf/2201.07459v3.pdf) | PT4AL | ECCV | 2022                 |  |
| [Active Learning on a Budget: Opposite Strategies Suit High and Low Budgets](https://arxiv.org/pdf/2202.02794v4.pdf) | TypiClust | ICML | 2022                 |  |


## Code Resources
- *General*
  - [**[List] Awesome Active Learning**](https://github.com/SupeRuier/awesome-active-learning) ![](https://img.shields.io/github/stars/SupeRuier/awesome-active-learning?style=social)
    - Previous works of active learning were categorized.
  - [**[List] Awesome Active Learning\***](https://github.com/baifanxxx/awesome-active-learning) ![](https://img.shields.io/github/stars/baifanxxx/awesome-active-learning?style=social)
    - A curated list of awesome Active Learning.
  - [**[List] Awesome Active Learning\*\***](https://github.com/yongjin-shin/awesome-active-learning) ![](https://img.shields.io/github/stars/yongjin-shin/awesome-active-learning?style=social)
    - A list of resources related to Active learning in machine learning.

- *Practice*
  - [**[Library] modAL**](https://github.com/modAL-python/modAL) ![](https://img.shields.io/github/stars/modAL-python/modAL?style=social)
      - A modular active learning framework for Python.
  - [**[Library] libact**](https://github.com/ntucllab/libact) ![](https://img.shields.io/github/stars/ntucllab/libact?style=social)
      - libact: Pool-based Active Learning in Python
  - [**[Library] pytorch_active_learning**](https://github.com/rmunro/pytorch_active_learning) ![](https://img.shields.io/github/stars/rmunro/pytorch_active_learning?style=social)
      - PyTorch Library for Active Learning to accompany Human-in-the-Loop Machine Learning book.
  - [**[Code Collection] deep-active-learning**](https://github.com/ej0cl6/deep-active-learning) ![](https://img.shields.io/github/stars/ej0cl6/deep-active-learning?style=social)
      - Python implementations of several active learning algorithms.
  - [**[Code Collection] Active Learning Playground**](https://github.com/google/active-learning) **[⚠️Inactive]** ![](https://img.shields.io/github/stars/google/active-learning?style=social)
      - A python module for experimenting with different active learning algorithms.

<!-- ### Setup
Conda environment: Install [conda](https://docs.conda.io/en/latest/miniconda.html)
```bash
export PROJECT_DIR=<ABSOLUTE path to the repository root>
# example: export PROJECT_DIR=/home/myusername/repositories/aad
cd $PROJECT_DIR
conda create -n aad python=3.8
conda activate aad
conda install pytorch==1.10.0 torchvision==0.11.1 -c pytorch -y
conda install scikit-learn pandas
pip install -r requirements.txt

# if the following commands do not succeed, update conda
conda env config vars set PYTHONPATH=${PYTHONPATH}:${PROJECT_DIR}
conda env config vars set PROJECT_DIR=${PROJECT_DIR}
conda env config vars set LD_LIBRARY_PATH=${CONDA_PREFIX}/lib:${LD_LIBRARY_PATH}
conda env config vars set CUDA_HOME=${CONDA_PREFIX}
conda env config vars set CUDA_ROOT=${CONDA_PREFIX}
conda deactivate
conda activate aad -->





