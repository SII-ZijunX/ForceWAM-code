# ForceWAM

**Decoupling Future and Response Learning from Demo and Play Data for Contact-Rich Manipulation**

[Paper](https://arxiv.org/abs/2610.18852) · [Project page](https://force-wam.github.io/)

## Release status

**Code coming soon.** This repository will host the ForceWAM implementation. We are preparing the code for release; implementation files and usage instructions will be added here.

## Overview

ForceWAM decomposes contact-rich manipulation into two complementary learning problems: predicting task-compatible interaction futures and learning the actions that realize those interactions.

- **Future learning:** ForceWM learns from successful task demonstrations to predict visual–wrench futures.
- **Response learning:** An inverse dynamics model (IDM) learns from demonstrations and task-agnostic play, using recorded futures and their corresponding actions.
- **Online execution:** The IDM combines ForceWM-generated futures with fresh measured-wrench feedback to update robot actions.

See the [project page](https://force-wam.github.io/) for the method, real-robot demonstrations, and experimental results.

## Citation

```bibtex
@misc{xu2026forcewamdecouplingfutureresponse,
  title = {ForceWAM: Decoupling Future and Response Learning from Demo and Play Data for Contact-Rich Manipulation},
  author = {Zijun Xu and Wendi Chen and Xinkai Wang and Jiachen Zou and Hongjin Chen and Hairuo Liu and Bokai Lin and Shihao Ma and Ke Ma and Zhiwei Zhang and Zhuohao Yan and Ke Wu and Haoming Song and Xueqi Li and Chuan Wen and Jieru Zhao and Wenchao Ding and Cewu Lu and Lixin Yang},
  year = {2026},
  eprint = {2610.18852},
  archivePrefix = {arXiv},
  primaryClass = {cs.RO},
  url = {https://arxiv.org/abs/2610.18852},
}
```
