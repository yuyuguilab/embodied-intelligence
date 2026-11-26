[English](README.md) | **简体中文**

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24554632.svg)](https://doi.org/10.5281/zenodo.24554632)

# 具身智能：定义、澄清、判据与边界

[AGI 人本拟合论](https://github.com/yuyuguilab/practice-fitting-theory)系列第七篇。2024 至 2026 年间，“具身智能”从机器人学与认知科学的术语成为多国政策文件、产业宣传与学术综述共用的词。本文把该理论的概念工具延伸到这一术语：

- **定义**——具身是系统与环境之间的关系属性：系统的行动通过物理因果改变环境状态，反馈来自物理测量，响应时延小于任务相关物理过程的特征时间。具身智能是“具身”与“智能”两个独立谓词的合取：不构成新的概念类型，而是能力概念在物理环境类上的受限情形。
- **澄清**——英文与中文定义语料的普查表明，既有分歧有三个来源：合取的一支被写进定义，环境类未加声明，词的层级未加区分。三种非法滑动在该话语中各有对应形态，另有一种为该话语特有：合取混淆。
- **判据**——由两条条件推出四项可执行检测：闭环检测、换身检测、回滚检测、暂停检测；时限裕度给出“弱具身”的定量读法。
- **区别**——具身智能与机器之心、世界模型互不蕴含；“具身智能是通往通用人工智能的必由之路”作为能力主张可以成立，作为路线主张不是概念推论。
- **实证**——政策、智库与企业文本中的用例显示，具身成立而能力不足、能力成立而具身不成立的系统都被冠以该名。
- 七条证伪条款、面向新案例的准入协议与适存条款。

## 编译

```bash
tectonic paper.tex      # 英文版
tectonic paper_zh.tex   # 中文版
```

需要 [tectonic](https://tectonic-typesetting.dev/)。首次编译会经网络下载 CTAN 资源包（含两版共用的 Fandol 中文字体，以及参考文献中日文、韩文题名所用的 Harano Aji Mincho 与 UnBatang 字体）；此后可用 `tectonic --only-cached` 离线编译。

## 版本

- `paper.tex` / `paper.pdf`——英文版
- `paper_zh.tex` / `paper_zh.pdf`——中文版

## 引用

余玉桂. 具身智能：定义、澄清、判据与边界. Zenodo, v1.0.0. doi:[10.5281/zenodo.24554632](https://doi.org/10.5281/zenodo.24554632)（概念 DOI，解析到最新版本）

```bibtex
@article{yu2026embodied,
  author  = {Yugui Yu},
  title   = {Embodied Intelligence: Definition, Clarification, Criteria, and Boundaries},
  journal = {Zenodo},
  year    = {2026},
  doi     = {10.5281/zenodo.24554632},
  url     = {https://doi.org/10.5281/zenodo.24554632}
}
```

## 许可

CC BY 4.0。作者：余玉桂（余玉桂战略研究室）。
