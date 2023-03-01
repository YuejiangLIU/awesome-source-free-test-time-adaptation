## Awesome Source-free Test-time Adaptation &nbsp; [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)

This is a curated list of research papers in `Test-time Adaptation` (**TTA**), which also goes by other names, such as `Test-time Training` (**TTT**), `Source-free Domain Adaptation` (**SFDA**) and `Unsupervised Model Adaptation` (**UMA**).

The repository is actively maintained. Pull requests or direct messages are welcome.

### Table of Contents

* [Methods](#methods)
  * [Self-supervision](#self-supervision)
  * [Information Entropy](#information-entropy)
  * [Batch Normalization](#batch-normalization)
  * [Pseudo Labeling](#pseudo-labeling)
  * [Class Prototype](#class-prototype)
  * [Feature Alignment](#feature-alignment)
  * [Generative Modeling](#generative-modeling)
  * [Nearest Neighbors](#nearest-neighbors)
  * [Augmentation Invariance](#augmentation-invariance)
  * [Meta-learning](#meta-learning)
  * [Time-varying](#time-varying)
  * [Others](#others)
* [Applications](#applications)
<!-- * [Datasets](#datasets) -->

### Methods

#### Self-supervision

* [Test-Time Training with Self-Supervision for Generalization under Distribution Shifts](http://proceedings.mlr.press/v119/sun20b.html) ICML'20
* [TTT++: When Does Self-Supervised Test-Time Training Fail or Thrive?](https://openreview.net/pdf?id=86NHK__yFDl) NeurIPS'21
* [Model Adaptation: Historical Contrastive Learning for Unsupervised Domain Adaptation without Source Data](https://openreview.net/pdf?id=0zXJRJecC_) NeurIPS'21
* [Contrastive Test-Time Adaptation](https://openaccess.thecvf.com/content/CVPR2022/papers/Chen_Contrastive_Test-Time_Adaptation_CVPR_2022_paper.pdf) CVPR'22
* [Divide and Contrast: Source-free Domain Adaptation via Adaptive Contrastive Learning](https://openreview.net/forum?id=NjImFaBEHl) NeurIPS'22
* [Test-Time Training with Masked Autoencoders](https://openreview.net/forum?id=SHMi1b7sjXk) NeurIPS'22

#### Information Entropy

* [Do We Really Need to Access the Source Data? Source Hypothesis Transfer for Unsupervised Domain Adaptation](http://proceedings.mlr.press/v119/liang20a.html) ICML'20
* [Tent: Fully Test-Time Adaptation by Entropy Minimization](https://openreview.net/forum?id=uXl3bZLkr3c) ICLR'21
* [Uncertainty Reduction for Model Adaptation in Semantic Segmentation](https://openaccess.thecvf.com/content/CVPR2021/html/S_Uncertainty_Reduction_for_Model_Adaptation_in_Semantic_Segmentation_CVPR_2021_paper.html) CVPR'21
* [Bayesian Adaptation for Covariate Shift](https://openreview.net/forum?id=15HPeY8MGQ) NeurIPS'21
* [Test-Time Adaptation to Distribution Shift by Confidence Maximization and Input Transformation](https://openreview.net/forum?id=uVTp9Z-IUOC) Preprint'21
* [Efficient Test-Time Model Adaptation without Forgetting](https://arxiv.org/abs/2204.02610) ICML'22
* [Confidence Score for Source-Free Unsupervised Domain Adaptation](https://arxiv.org/abs/2206.06640) ICML'22
* [Towards Stable Test-time Adaptation in Dynamic Wild World](https://openreview.net/forum?id=g2YraF75Tj) ICLR'23

#### Batch Normalization

* [Improving robustness against common corruptions by covariate shift adaptation](https://proceedings.neurips.cc/paper/2020/file/85690f81aadc1749175c187784afc9ee-Paper.pdf) NeurIPS'20
* [Tent: Fully Test-Time Adaptation by Entropy Minimization](https://openreview.net/forum?id=uXl3bZLkr3c) ICLR'21
* [Limitations of Post-Hoc Feature Alignment for Robustness
](https://openaccess.thecvf.com/content/CVPR2021/html/Burns_Limitations_of_Post-Hoc_Feature_Alignment_for_Robustness_CVPR_2021_paper.html) CVPR'21
* [TTN: A Domain-Shift Aware Batch Normalization in Test-Time Adaptation](https://openreview.net/forum?id=EQfeudmWLQ) ICLR'23
* [Delta: Degradation-Free Fully Test-Time Adaptation](https://openreview.net/forum?id=eGm22rqG93) ICLR'23
* [Towards Stable Test-time Adaptation in Dynamic Wild World](https://openreview.net/forum?id=g2YraF75Tj) ICLR'23

#### Pseudo Labeling

* [Do We Really Need to Access the Source Data? Source Hypothesis Transfer for Unsupervised Domain Adaptation](http://proceedings.mlr.press/v119/liang20a.html) ICML'20
* [Generative Pseudo-label Refinement for Unsupervised Domain Adaptation](https://www.computer.org/csdl/proceedings-article/wacv/2020/09093579/1jPbrqho82k) WACV'20
* [A Free Lunch for Unsupervised Domain Adaptive Object Detection without Source Data](https://ojs.aaai.org/index.php/AAAI/article/view/17029) AAAI'21
* [Uncertainty Reduction for Model Adaptation in Semantic Segmentation](https://openaccess.thecvf.com/content/CVPR2021/html/S_Uncertainty_Reduction_for_Model_Adaptation_in_Semantic_Segmentation_CVPR_2021_paper.html) CVPR'21
* [Adapting ImageNet-scale models to complex distribution shifts with self-learning](https://arxiv.org/abs/2104.12928) Preprint'21
* [Continual Test-Time Domain Adaptation](https://arxiv.org/abs/2203.13591) CVPR'22
* [Contrastive Test-Time Adaptation](https://openaccess.thecvf.com/content/CVPR2022/papers/Chen_Contrastive_Test-Time_Adaptation_CVPR_2022_paper.pdf) CVPR'22
* [Test-Time Adaptation via Conjugate Pseudo-labels](https://openreview.net/forum?id=2yvUYc-YNUH) NeurIPS'22
* [Towards Understanding GD with Hard and Conjugate Pseudo-labels for Test-Time Adaptation](https://openreview.net/forum?id=FJXf1FXN8C) ICLR'23

#### Class Prototype

* [Model Adaptation: Unsupervised Domain Adaptation Without Source Data](https://openaccess.thecvf.com/content_CVPR_2020/html/Li_Model_Adaptation_Unsupervised_Domain_Adaptation_Without_Source_Data_CVPR_2020_paper.html) CVPR'20
* [Test-Time Classifier Adjustment Module for Model-Agnostic Domain Generalization](https://proceedings.neurips.cc/paper/2021/hash/1415fe9fea0fa1e45dddcff5682239a0-Abstract.html) NeurIPS'21
* [Revisiting Realistic Test-Time Training: Sequential Inference and Adaptation by Anchored Clustering](https://openreview.net/forum?id=W-_4hgRkwb) NeurIPS'22
* [Attracting and Dispersing: A Simple Approach for Source-free Domain Adaptation](https://openreview.net/forum?id=ZlCpRiZN7n) NeurIPS'22

#### Feature Alignment

* [SoFA: Source-data-free Feature Alignment for Unsupervised Domain Adaptation](https://openaccess.thecvf.com/content/WACV2021/papers/Yeh_SoFA_Source-Data-Free_Feature_Alignment_for_Unsupervised_Domain_Adaptation_WACV_2021_paper.pdf) WACV'21
* [Adaptive Adversarial Network for Source-Free Domain Adaptation](https://openaccess.thecvf.com/content/ICCV2021/html/Xia_Adaptive_Adversarial_Network_for_Source-Free_Domain_Adaptation_ICCV_2021_paper.html) ICCV'21
* [TTT++: When Does Self-Supervised Test-Time Training Fail or Thrive?](https://proceedings.neurips.cc/paper/2021/hash/b618c3210e934362ac261db280128c22-Abstract.html) NeurIPS'21
* [Source-Free Adaptation to Measurement Shift via Bottom-Up Feature Restoration](https://openreview.net/forum?id=1JDiK_TbV4S) ICLR'22
* [Invariance Through Inference](https://openreview.net/forum?id=vXGcHthY6v) Preprint'21
* [Source-Free Domain Adaptation via Distribution Estimation](https://openaccess.thecvf.com/content/CVPR2022/papers/Ding_Source-Free_Domain_Adaptation_via_Distribution_Estimation_CVPR_2022_paper.pdf) CVPR'22

#### Generative Modeling

* [Model Adaptation: Unsupervised Domain Adaptation without Source Data](https://openaccess.thecvf.com/content_CVPR_2020/html/Li_Model_Adaptation_Unsupervised_Domain_Adaptation_Without_Source_Data_CVPR_2020_paper.html) CVPR'20
* [Domain Impression: A Source Data Free Domain Adaptation Method](https://openaccess.thecvf.com/content/WACV2021/papers/Kurmi_Domain_Impression_A_Source_Data_Free_Domain_Adaptation_Method_WACV_2021_paper.pdf) WACV'21
* [Back to the Source: Diffusion-Driven Test-Time Adaptation](https://arxiv.org/abs/2207.03442) Preprint'22

#### Nearest Neighbors

* [Generalized Source-free Domain Adaptation](https://openaccess.thecvf.com/content/ICCV2021/papers/Yang_Generalized_Source-Free_Domain_Adaptation_ICCV_2021_paper.pdf) ICCV'21
* [Exploiting the Intrinsic Neighborhood Structure for Source-free Domain Adaptation](https://proceedings.neurips.cc/paper/2021/hash/f5deaeeae1538fb6c45901d524ee2f98-Abstract.html) NeurIPS'21
* [Test-Time Adaptation via Self-Training with Nearest Neighbor Information](https://openreview.net/forum?id=EzLtB4M1SbM) ICLR'23

#### Augmentation Invariance

* [MEMO: Test Time Robustness via Adaptation and Augmentation](https://openreview.net/forum?id=vn74m_tWu8O) NeurIPS'22
* [Test time Adaptation through Perturbation Robustness](https://openreview.net/forum?id=GbBeI5z86uD) NeurIPS-WS'21
* [Balancing Discriminability and Transferability for Source-Free Domain Adaptation](https://arxiv.org/abs/2206.08009?context=cs.LG) ICML'22

#### Meta-learning

* [Test-Time Fast Adaptation for Dynamic Scene Deblurring via Meta-Auxiliary Learning](https://openaccess.thecvf.com/content/CVPR2021/html/Chi_Test-Time_Fast_Adaptation_for_Dynamic_Scene_Deblurring_via_Meta-Auxiliary_Learning_CVPR_2021_paper.html) CVPR'21
* [Adaptive Risk Minimization: Learning to Adapt to Domain Shift](https://proceedings.neurips.cc/paper/2021/hash/c705112d1ec18b97acac7e2d63973424-Abstract.html) NeurIPS'21
* [Learning to Generalize across Domains on Single Test Samples](https://openreview.net/forum?id=CIaQKbTBwtU) ICLR'22
* [Meta-DMoE: Adapting to Domain Shift by Meta-Distillation from Mixture-of-Experts](https://openreview.net/forum?id=_ekGcr07Dsp) NeurIPS'22

#### Time-varying
* [Continual Test-Time Domain Adaptation](https://arxiv.org/abs/2203.13591) CVPR'22
* [NOTE: Robust Continual Test-time Adaptation Against Temporal Correlation](https://openreview.net/forum?id=E9HNxrCFZPV) NeurIPS'22
* [Extrapolative Continuous-time Bayesian Neural Network for Fast Training-free Test-time Adaptation](https://openreview.net/forum?id=wiHzQWwg3l) NeurIPS'22
* [Decorate the Newcomers: Visual Domain Prompt for Continual Test Time Adaptation](https://arxiv.org/pdf/2212.04145.pdf) AAAI'23

#### Others

* [Domain Adaptation in the Absence of Source Domain Data](https://www.kdd.org/kdd2016/papers/files/adp0290-chidlovskiiA.pdf) KDD'16
* [Semantic Photo Manipulation with a Generative Image Prior](https://arxiv.org/pdf/2005.07727.pdf) SIGGRAPH'19
* [Collaborative Sampling in Generative Adversarial Networks](https://arxiv.org/pdf/1902.00813.pdf) AAAI'20
* [Universal Source-Free Domain Adaptation](https://openaccess.thecvf.com/content_CVPR_2020/papers/Kundu_Universal_Source-Free_Domain_Adaptation_CVPR_2020_paper.pdf) CVPR'20
* [Adaptive Methods for Real-World Domain Generalization](https://openaccess.thecvf.com/content/CVPR2021/papers/Dubey_Adaptive_Methods_for_Real-World_Domain_Generalization_CVPR_2021_paper.pdf) CVPR'21
* [Parameter-free Online Test-time Adaptation](https://arxiv.org/abs/2201.05718) CVPR'22
* [Visual Prompt Tuning for Test-time Domain Adaptation](https://arxiv.org/abs/2210.04831) Preprint'22
* [Evaluating the Adversarial Robustness of Adaptive Test-time Defenses](https://proceedings.mlr.press/v162/croce22a/croce22a.pdf) ICML'22
* [MECTA: Memory-Economic Continual Test-Time Model Adaptation](https://openreview.net/forum?id=N92hjSf5NNh) ICLR'23

### Applications
* [Self-Supervised Policy Adaptation during Deployment](https://openreview.net/forum?id=o_V-MjyyGV_) ICLR'21
* [Source-Free Domain Adaptation for Image Segmentation](https://arxiv.org/pdf/2108.03152.pdf) MICCAI'20
* [Fully Test-Time Adaptation for Image Segmentation](https://link.springer.com/chapter/10.1007/978-3-030-87199-4_24) MICCAI'21
* [Adapting Off-the-Shelf Source Segmenter for Target Medical Image Segmentation](https://arxiv.org/pdf/2106.12497.pdf) MICCAI'21
* [Source-Free Domain Adaptation for Semantic Segmentation](https://openaccess.thecvf.com/content/CVPR2021/html/Liu_Source-Free_Domain_Adaptation_for_Semantic_Segmentation_CVPR_2021_paper.html) CVPR'21
* [Generalize Then Adapt: Source-Free Domain Adaptive Semantic Segmentation
](https://openaccess.thecvf.com/content/ICCV2021/html/Kundu_Generalize_Then_Adapt_Source-Free_Domain_Adaptive_Semantic_Segmentation_ICCV_2021_paper.html) ICCV'21
* [SS-SFDA: Self-Supervised Source-Free Domain Adaptation for Road Segmentation in Hazardous Environments](https://openaccess.thecvf.com/content/WACV2021/papers/Yeh_SoFA_Source-Data-Free_Feature_Alignment_for_Unsupervised_Domain_Adaptation_WACV_2021_paper.pdf) ICCV'21
* [Test-Time Personalization with a Transformer for Human Pose Estimation](https://proceedings.neurips.cc/paper/2021/file/1517c8664be296f0d87d9e5fc54fdd60-Paper.pdf) NeurIPS'21
* [Towards Robust and Adaptive Motion Forecasting: A Causal Representation Perspective](https://arxiv.org/abs/2111.14820) CVPR'22
* [Ev-TTA: Test-Time Adaptation for Event-Based Object Recognition](https://arxiv.org/abs/2203.12247) CVPR'22
* [MM-TTA: Multi-Modal Test-Time Adaptation for 3D Semantic Segmentation](https://arxiv.org/abs/2204.12667) CVPR'22
* [Source-Free Object Detection by Learning to Overlook Domain Style](https://openaccess.thecvf.com/content/CVPR2022/html/Li_Source-Free_Object_Detection_by_Learning_To_Overlook_Domain_Style_CVPR_2022_paper.html) CVPR'22
* [Test-Time Prompt Tuning for Zero-Shot Generalization in Vision-Language Models](https://openreview.net/forum?id=e8PVEkSa4Fq) NeurIPS'22
* [Test-Time Training Can Close the Natural Distribution Shift Performance Gap in Deep Learning Based Compressed Sensing](https://proceedings.mlr.press/v162/darestani22a/darestani22a.pdf) ICML'22 
* [The Dual Form of Neural Networks Revisited: Connecting Test Time Predictions to Training Patterns via Spotlights of Attention
](https://proceedings.mlr.press/v162/irie22a/irie22a.pdf) ICML'22
* [AuxAdapt: Stable and Efficient Test-Time Adaptation for Temporally Consistent Video Semantic Segmentation](https://openaccess.thecvf.com/content/WACV2022/papers/Zhang_AuxAdapt_Stable_and_Efficient_Test-Time_Adaptation_for_Temporally_Consistent_Video_WACV_2022_paper.pdf) WACV'22
* [On the Road to Online Adaptation for Semantic Image Segmentation](https://openaccess.thecvf.com/content/CVPR2022/papers/Volpi_On_the_Road_to_Online_Adaptation_for_Semantic_Image_Segmentation_CVPR_2022_paper.pdf) CVPR'22

<!-- ### Datasets -->
