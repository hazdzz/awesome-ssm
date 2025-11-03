# SSMs and related works list
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![forks](https://img.shields.io/github/forks/hazdzz/awesome-ssm)](https://github.com/hazdzz/awesome-ssm/network/members)
[![stars](https://img.shields.io/github/stars/hazdzz/awesome-ssm)](https://github.com/hazdzz/awesome-ssm/stargazers)
[![License](https://img.shields.io/github/license/hazdzz/awesome-ssm)](./LICENSE)

## About
A list for SSMs, linear RNNs, and linear attention-based Transformers. The differences between SSMs, linear RNNs, and linear attention-based Transformers are very small. Unless specifically indicated in the papers, the divisions in this list are not rigorous and are for academic reference only.

## List for SSMs
| Number | SSM | Paper | Code | Conference or Journal | URL |
|:------:|:--------------------------:|-------|------|:-------:|----------------------------------------|
| 1 | HiPPO | HiPPO: Recurrent Memory with Optimal Polynomial Projections | https://github.com/state-spaces/s4 | NeurIPS 2020 | https://proceedings.neurips.cc/paper/2020/hash/102f0bb6efb3a6128a3c750dd16729be-Abstract.html |
| 2 | LSSL | Combining Recurrent, Convolutional, and Continuous-time Models with Linear State-Space Layers | https://github.com/state-spaces/s4 | NeurIPS 2021 | https://openreview.net/forum?id=yWd42CWN3c |
| 3 | S4 | Efficiently Modeling Long Sequences with Structured State Spaces | https://github.com/state-spaces/s4 | ICLR 2022 | https://openreview.net/forum?id=uYLFoz1vlAC |
| 4 | DSS | Diagonal State Spaces are as Effective as Structured State Spaces | https://github.com/ag1988/dss | NeurIPS 2022 | https://openreview.net/forum?id=RjS0j6tsSrf |
| 5 | S4D | On the Parameterization and Initialization of Diagonal State Space Models | https://github.com/state-spaces/s4 | NeurIPS 2022 | https://openreview.net/forum?id=yJE7iQSAep |
| 6 | Generalized HiPPO | How to Train your HIPPO: State Space Models with Generalized Orthogonal Basis Projections | https://github.com/state-spaces/s4 | ICLR 2023 | https://openreview.net/forum?id=klK17OQ3KB |
| 7 | GSS | Long Range Language Modeling via Gated State Spaces | | ICLR 2023 | https://openreview.net/forum?id=5MkYIYCbva |
| 8 | Liquid S4 | Liquid Structural State-Space Models | https://github.com/raminmh/liquid-s4 | ICLR 2023 | https://openreview.net/forum?id=g4OTKRKfS7R |
| 9 | S5 | Simplified State Space Layers for Sequence Modeling | https://github.com/lindermanlab/S5 | ICLR 2023 | https://openreview.net/forum?id=Ai8Hw3AXqks |
| 10 | H3 | Hungry Hungry Hippos: Towards Language Modeling with State Space Models | https://github.com/HazyResearch/H3 | ICLR 2023 | https://openreview.net/forum?id=COZDy0WYGg |
| 11 | S4-PTD and S5-PTD | Robustifying State-space Models for Long Sequences via Approximate Diagonalization | | ICLR 2024 | https://openreview.net/forum?id=DjeQ39QoLQ |
| 12 | S6 | Mamba: Linear-Time Sequence Modeling with Selective State Spaces | https://github.com/state-spaces/mamba | | https://arxiv.org/abs/2312.00752 |
| 13 | STU | Spectral State Space Models | https://github.com/catid/spectral_ssm | | https://arxiv.org/abs/2312.06837 |
| 14 | Mamba 2 | Transformers are SSMs: Generalized Models and Efficient Algorithms with Structured State Space Duality | https://github.com/state-spaces/mamba | ICML 2024 | https://arxiv.org/abs/2405.21060 |
| 15 | RTF | State-Free Inference of State-Space Models: The Transfer Function Approach | https://github.com/ruke1ire/RTF | ICML 2024 | https://openreview.net/forum?id=DwwI9L67B5 |
| 16 | Longhorn | Longhorn: State Space Models are Amortized Online Learners | https://github.com/Cranial-XIX/Longhorn | ICLR 2025 | https://openreview.net/forum?id=8jOqCcLzeO |

## List for Linear RNNs (LRNNs)
| Number | LRNN | Paper | Code | Conference or Journal | URL |
|:------:|:--------------------------:|-------|------|:-------:|----------------------------------------|
| 1 | CKConv | CKConv: Continuous Kernel Convolution For Sequential Data | https://github.com/dwromero/ckconv | ICLR 2021 | https://openreview.net/forum?id=8FhxBtXSl0 |
| 2 | FlexConv | FlexConv: Continuous Kernel Convolutions With Differentiable Kernel Sizes | https://github.com/rjbruin/flexconv | ICLR 2022 | https://openreview.net/forum?id=3jooF27-0Wy |
| 3 | Momentum Transformer and Adaptive Momentum Transformer | Momentum Transformer: Closing the Performance Gap Between Self-attention and Its Linearization | | PMLR 2022 | https://proceedings.mlr.press/v190/nguyen22a.html |
| 4 | DLR | Simplifying and Understanding State Space Models with Diagonal Linear RNNs | https://github.com/ag1988/dlr | | https://arxiv.org/abs/2212.00768 |
| 5 | CCNN | Modelling Long Range Dependencies in \$N\$D: From Task-Specific to a General Purpose CNN | https://github.com/david-knigge/ccnn | ICLR 2023 | https://openreview.net/forum?id=ZW5aK4yCRqU |
| 6 | SGConv | What Makes Convolutional Models Great on Long Sequence Modeling? | https://github.com/ctlllll/SGConv | ICLR 2023 | https://openreview.net/forum?id=TGJSPbRpJX- |
| 7 | Mega | Mega: Moving Average Equipped Gated Attention | https://github.com/facebookresearch/mega | ICLR 2023 | https://openreview.net/forum?id=qNLe3iq2El |
| 8 | TNN | Toeplitz Neural Network for Sequence Modeling | https://github.com/Doraemonzzz/tnn-pytorch | ICLR 2023 | https://openreview.net/forum?id=IxmWsm4xrua |
| 9 | Hyena | Hyena Hierarchy: Towards Larger Convolutional Language Models | https://github.com/hazyresearch/safari | ICML 2023 | https://proceedings.mlr.press/v202/poli23a.html |
| 10 | MultiresNet | Sequence Modeling with Multiresolution Convolutional Memory | https://github.com/thjashin/multires-conv | ICML 2023 | https://proceedings.mlr.press/v202/shi23f.html |
| 11 | LRU | Resurrecting Recurrent Neural Networks for Long Sequences | | ICML 2023 | https://proceedings.mlr.press/v202/orvieto23a.html |
| 12 | RWKV v4 (Dove) | RWKV: Reinventing RNNs for the Transformer Era | https://github.com/BlinkDL/RWKV-LM | EMNLP 2023 | https://aclanthology.org/2023.findings-emnlp.936/ |
| 13 | RetNet | Retentive Network: A Successor to Transformer for Large Language Models | https://github.com/microsoft/torchscale | | https://arxiv.org/abs/2307.08621 |
| 14 | MultiHyena | Laughing Hyena Distillery: Extracting Compact Recurrences From Convolutions | | NeurIPS 2023 | https://openreview.net/forum?id=OWELckerm6 |
| 15 | Monarch Mixer | Monarch Mixer: A Simple Sub-Quadratic GEMM-Based Architecture | https://github.com/HazyResearch/m2 | NeurIPS 2023 | https://openreview.net/forum?id=cB0BImqSS9 |
| 16 | SeqBoat | Sparse Modular Activation for Efficient Sequence Modeling | https://github.com/renll/SeqBoat | NeurIPS 2023 | https://openreview.net/forum?id=TfbzX6I14i |
| 17 | HGRN | Hierarchically Gated Recurrent Neural Network for Sequence Modeling | https://github.com/OpenNLPLab/HGRN | NeurIPS 2023 | https://openreview.net/forum?id=P1TCHxJwLB |
| 18 | GLA Transformer | Gated Linear Attention Transformers with Hardware-Efficient Training | https://github.com/sustcsonglin/flash-linear-attention | ICML 2024 | https://proceedings.mlr.press/v235/yang24ab.html |
| 19 | Orchid | Orchid: Flexible and Data-Dependent Convolution for Sequence Modeling | | NeurIPS 2024 | https://proceedings.neurips.cc/paper_files/paper/2024/hash/8ccc5ec30a8d46793d790e2216efd40d-Abstract-Conference.html |
| 20 | RWKV v5 (Eagle) and v6 (Finch) | Eagle and Finch: RWKV with Matrix-Valued States and Dynamic Recurrence | https://github.com/BlinkDL/RWKV-LM | COLM 2024 | https://openreview.net/forum?id=soz1SEiPeq |
| 21 | HGRN2 | HGRN2: Gated Linear RNNs with State Expansion | https://github.com/OpenNLPLab/HGRN2 | COLM 2024 | https://openreview.net/forum?id=y6SqbJfCSk |
| 22 | | Parallelizing Linear Transformers with the Delta Rule over Sequence Length | https://github.com/fla-org/flash-linear-attention | NeurIPS 2024 | https://openreview.net/forum?id=y8Rm4VNRPH |
| 23 | RWKV v7 (Goose) | RWKV-7 "Goose" with Expressive Dynamic State Evolution | https://github.com/BlinkDL/RWKV-LM | | https://arxiv.org/abs/2503.14456 |

## List for Surveys
| Number | Paper | Journal or Conference | URL |
|:------:|--------------------------|:-------:|----------------------------------------|
| 1 | Modeling sequences with structured state spaces | | https://purl.stanford.edu/mb976vf9362 |
| 2 | A Unified View of Long-Sequence Models towards Modeling Million-Scale Dependencies | | https://arxiv.org/abs/2302.06218 |
| 3 | State Space Model for New-Generation Network Alternative to Transformers: A Survey | | https://arxiv.org/abs/2404.09516 |
| 4 | Understanding Transformer from the Perspective of Associative Memory | | https://arxiv.org/abs/2505.19488 |
| 5 | Test-time regression: a unifying framework for designing sequence models with associative memory | | https://arxiv.org/abs/2501.12352 |
