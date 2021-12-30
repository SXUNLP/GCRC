# GCRC
GCRC: A New Challenging MRC Dataset from Gaokao Chinese for Explainable Evaluation

### Introduction
  Currently, machine reading comprehension models have made exciting progress, driven by a large number of publicly available data sets. However, the real language comprehension capabilities of models are far from what people expect, and most of the data sets provide black-box evaluations that fail to diagnose whether the system is based on correct reasoning processes. In order to alleviate these problems and promote machine intelligence to humanoid intelligence, Shanxi University focuses on the more diverse and challenging reading comprehension tasks of the college entrance examination, and attempts to evaluate machine intelligence effectively and practically based on standardized human tests. We collected gaokao reading comprehension test questions in the past 10 years and constructed a datasets which is GCRC(A New MRC Dataset from Gaokao Chinese for Explainable Evaluation) containing more than 5000 texts and more than 8,700 multiple-choice questions (about 15,000 options). The datasets is annotated three kinds of information: the sentence level support fact, interference item’s error cause and the reasoning skills required to answer questions. Related experiments show that this datasets is more challenging, which is very useful for diagnosing system limitations in an interpretable manner, and will help researchers develop new machine learning and reasoning methods to solve these challenging problems in the future.
  
### Paper
[GCRC: A New Challenging MRC Dataset from Gaokao Chinese for Explainable Evaluation](https://aclanthology.org/2021.findings-acl.113.pdf). ACL 2021 Findings.

### Dataset
Please see [GCRC for Explainable Evaluation](http://cuge.baai.ac.cn/#/dataset?id=22&name=GCRC) or [Github related links](https://github.com/yunxiaomr/GCRC).

### Code
Please see [GCRC for Explainable Evaluation](http://cuge.baai.ac.cn/#/dataset?id=22&name=GCRC) or [Github related links](https://github.com/yunxiaomr/GCRC) about the eval script. 
In the near future we will upload the baseline code.

### Leaderboard
Please see [GCRC Leaderboard for Explainable Evaluation](http://cuge.baai.ac.cn/#/dataset?id=22&name=GCRC)

### Author List
Hongye Tan, Xiaoyue Wang, Yu Ji, Ru Li, Xiaoli Li, Zhiwei Hu, Yunxiao Zhao, Xiaoqi Han.

### Institutions
[Shanxi University](https://github.com/SXUNLP)

### Citation
```bibtex
@inproceedings{tan-etal-2021-gcrc,
    title = "{GCRC}: A New Challenging {MRC} Dataset from {G}aokao {C}hinese for Explainable Evaluation",
    author = "Tan, Hongye  and
      Wang, Xiaoyue  and
      Ji, Yu  and
      Li, Ru  and
      Li, Xiaoli  and
      Hu, Zhiwei  and
      Zhao, Yunxiao  and
      Han, Xiaoqi",
    booktitle = "Findings of the Association for Computational Linguistics: ACL-IJCNLP 2021",
    month = aug,
    year = "2021",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.findings-acl.113",
    doi = "10.18653/v1/2021.findings-acl.113",
    pages = "1319--1330",
}
```
