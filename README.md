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
  * [Others](#others)
* [Applications](#applications)
<!-- * [Datasets](#datasets) -->

### Methods

#### Self-supervision

* [Test-Time Training with Self-Supervision for Generalization under Distribution Shifts](http://proceedings.mlr.press/v119/sun20b.html) ICML'20
* [TTT++: When Does Self-Supervised Test-Time Training Fail or Thrive?](https://openreview.net/pdf?id=86NHK__yFDl) NeurIPS'21
* [Model Adaptation: Historical Contrastive Learning for Unsupervised Domain Adaptation without Source Data](https://openreview.net/pdf?id=0zXJRJecC_) NeurIPS'21

#### Information Entropy

* [Do We Really Need to Access the Source Data? Source Hypothesis Transfer for Unsupervised Domain Adaptation](http://proceedings.mlr.press/v119/liang20a.html) ICML'20
* [Tent: Fully Test-Time Adaptation by Entropy Minimization](https://openreview.net/forum?id=uXl3bZLkr3c) ICLR'21
* [Uncertainty Reduction for Model Adaptation in Semantic Segmentation](https://openaccess.thecvf.com/content/CVPR2021/html/S_Uncertainty_Reduction_for_Model_Adaptation_in_Semantic_Segmentation_CVPR_2021_paper.html) CVPR'21
* [Test-Time Adaptation to Distribution Shift by Confidence Maximization and Input Transformation](https://openreview.net/forum?id=uVTp9Z-IUOC) Preprint'21

#### Batch Normalization

* [Improving robustness against common corruptions by covariate shift adaptation](https://proceedings.neurips.cc/paper/2020/file/85690f81aadc1749175c187784afc9ee-Paper.pdf) NeurIPS'20
* [Tent: Fully Test-Time Adaptation by Entropy Minimization](https://openreview.net/forum?id=uXl3bZLkr3c) ICLR'21
* [Limitations of Post-Hoc Feature Alignment for Robustness
](https://openaccess.thecvf.com/content/CVPR2021/html/Burns_Limitations_of_Post-Hoc_Feature_Alignment_for_Robustness_CVPR_2021_paper.html) CVPR'21
* [Test-time Batch Statistics Calibration for Covariate Shift](https://openreview.net/forum?id=9gz8qakpyhG) Preprint'21

#### Pseudo Labeling

* [Do We Really Need to Access the Source Data? Source Hypothesis Transfer for Unsupervised Domain Adaptation](http://proceedings.mlr.press/v119/liang20a.html) ICML'20
* [Generative Pseudo-label Refinement for Unsupervised Domain Adaptation](https://www.computer.org/csdl/proceedings-article/wacv/2020/09093579/1jPbrqho82k) WACV'20
* [A Free Lunch for Unsupervised Domain Adaptive Object Detection without Source Data](https://ojs.aaai.org/index.php/AAAI/article/view/17029) AAAI'21
* [Uncertainty Reduction for Model Adaptation in Semantic Segmentation](https://openaccess.thecvf.com/content/CVPR2021/html/S_Uncertainty_Reduction_for_Model_Adaptation_in_Semantic_Segmentation_CVPR_2021_paper.html) CVPR'21
* [Adapting ImageNet-scale models to complex distribution shifts with self-learning](https://arxiv.org/abs/2104.12928) Preprint'21

#### Class Prototype

* [Model Adaptation: Unsupervised Domain Adaptation Without Source Data](https://openaccess.thecvf.com/content_CVPR_2020/html/Li_Model_Adaptation_Unsupervised_Domain_Adaptation_Without_Source_Data_CVPR_2020_paper.html) CVPR'20
* [Test-Time Classifier Adjustment Module for Model-Agnostic Domain Generalization](https://proceedings.neurips.cc/paper/2021/hash/1415fe9fea0fa1e45dddcff5682239a0-Abstract.html) NeurIPS'21

#### Feature Alignment

* [SoFA: Source-data-free Feature Alignment for Unsupervised Domain Adaptation](https://openaccess.thecvf.com/content/WACV2021/papers/Yeh_SoFA_Source-Data-Free_Feature_Alignment_for_Unsupervised_Domain_Adaptation_WACV_2021_paper.pdf) WACV'21
* [Adaptive Adversarial Network for Source-Free Domain Adaptation](https://openaccess.thecvf.com/content/ICCV2021/html/Xia_Adaptive_Adversarial_Network_for_Source-Free_Domain_Adaptation_ICCV_2021_paper.html) ICCV'21
* [TTT++: When Does Self-Supervised Test-Time Training Fail or Thrive?](https://proceedings.neurips.cc/paper/2021/hash/b618c3210e934362ac261db280128c22-Abstract.html) NeurIPS'21
* [Source-Free Adaptation to Measurement Shift via Bottom-Up Feature Restoration](https://openreview.net/forum?id=1JDiK_TbV4S) Preprint'21
* [Invariance Through Inference](https://openreview.net/forum?id=vXGcHthY6v) Preprint'21

#### Generative Modeling

* [Model Adaptation: Unsupervised Domain Adaptation without Source Data](https://openaccess.thecvf.com/content_CVPR_2020/html/Li_Model_Adaptation_Unsupervised_Domain_Adaptation_Without_Source_Data_CVPR_2020_paper.html) CVPR'20
* [Domain Impression: A Source Data Free Domain Adaptation Method](https://openaccess.thecvf.com/content/WACV2021/papers/Kurmi_Domain_Impression_A_Source_Data_Free_Domain_Adaptation_Method_WACV_2021_paper.pdf) WACV'21

#### Nearest Neighbors

* [Generalized Source-free Domain Adaptation](https://openaccess.thecvf.com/content/ICCV2021/papers/Yang_Generalized_Source-Free_Domain_Adaptation_ICCV_2021_paper.pdf) ICCV'21
* [Exploiting the Intrinsic Neighborhood Structure for Source-free Domain Adaptation](https://proceedings.neurips.cc/paper/2021/hash/f5deaeeae1538fb6c45901d524ee2f98-Abstract.html) NeurIPS'21

#### Augmentation Invariance

* [MEMO: Test Time Robustness via Adaptation and Augmentation](https://openreview.net/forum?id=vn74m_tWu8O) NeurIPS-WS'21
* [Test time Adaptation through Perturbation Robustness](https://openreview.net/forum?id=GbBeI5z86uD) NeurIPS-WS'21

#### Meta-learning

* [Test-Time Fast Adaptation for Dynamic Scene Deblurring via Meta-Auxiliary Learning](https://openaccess.thecvf.com/content/CVPR2021/html/Chi_Test-Time_Fast_Adaptation_for_Dynamic_Scene_Deblurring_via_Meta-Auxiliary_Learning_CVPR_2021_paper.html) CVPR'21
* [Adaptive Risk Minimization: Learning to Adapt to Domain Shift](https://proceedings.neurips.cc/paper/2021/hash/c705112d1ec18b97acac7e2d63973424-Abstract.html) NeurIPS'21
* [Learning to Generalize across Domains on Single Test Samples](https://openreview.net/forum?id=CIaQKbTBwtU) Preprint'21

#### Others

* [Domain Adaptation in the Absence of Source Domain Data](https://www.kdd.org/kdd2016/papers/files/adp0290-chidlovskiiA.pdf) KDD'16
* [Semantic Photo Manipulation with a Generative Image Prior](https://arxiv.org/pdf/2005.07727.pdf) SIGGRAPH'19
* [Collaborative Sampling in Generative Adversarial Networks](https://arxiv.org/pdf/1902.00813.pdf) AAAI'20
* [Universal Source-Free Domain Adaptation](https://openaccess.thecvf.com/content_CVPR_2020/papers/Kundu_Universal_Source-Free_Domain_Adaptation_CVPR_2020_paper.pdf) CVPR'20
* [Adaptive Methods for Real-World Domain Generalization](https://openaccess.thecvf.com/content/CVPR2021/papers/Dubey_Adaptive_Methods_for_Real-World_Domain_Generalization_CVPR_2021_paper.pdf) CVPR'21

### Applications
* [Self-Supervised Policy Adaptation during Deployment](https://openreview.net/forum?id=o_V-MjyyGV_) ICLR'21
* [Fully Test-Time Adaptation for Image Segmentation](https://link.springer.com/chapter/10.1007/978-3-030-87199-4_24) MICCAI'21
* [Adapting Off-the-Shelf Source Segmenter for Target Medical Image Segmentation](https://arxiv.org/pdf/2106.12497.pdf) MICCAI'21
* [Source-Free Domain Adaptation for Semantic Segmentation](https://openaccess.thecvf.com/content/CVPR2021/html/Liu_Source-Free_Domain_Adaptation_for_Semantic_Segmentation_CVPR_2021_paper.html) CVPR'21
* [Generalize Then Adapt: Source-Free Domain Adaptive Semantic Segmentation
](https://openaccess.thecvf.com/content/ICCV2021/html/Kundu_Generalize_Then_Adapt_Source-Free_Domain_Adaptive_Semantic_Segmentation_ICCV_2021_paper.html) ICCV'21
* [SS-SFDA: Self-Supervised Source-Free Domain Adaptation for Road Segmentation in Hazardous Environments](https://openaccess.thecvf.com/content/WACV2021/papers/Yeh_SoFA_Source-Data-Free_Feature_Alignment_for_Unsupervised_Domain_Adaptation_WACV_2021_paper.pdf) ICCV'21
* [Test-Time Personalization with a Transformer for Human Pose Estimation](https://proceedings.neurips.cc/paper/2021/file/1517c8664be296f0d87d9e5fc54fdd60-Paper.pdf) NeurIPS'21
* [Towards Robust and Adaptive Motion Forecasting: A Causal Representation Perspective](https://arxiv.org/abs/2111.14820) Preprint'21
  
<!-- ### Datasets -->
