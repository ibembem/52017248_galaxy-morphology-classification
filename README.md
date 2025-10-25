# 52017248_galaxy-morphology-classification
Applied deep learning for classification of images. Assignment 1.

# Galaxy Morphology Classification

## 1. Topic 

In this project I aim to classify galaxies based on their morphological type (spiral, elliptical, irregular) using deep learning methods. 

## 2. Project type

Bring your own method - the focus is on implementing and refining an architecture that extends an existing model.

## 3. Reference papers

1. **Kim & Brunner, 2017 – *Star–galaxy classification using deep convolutional neural networks* (MNRAS, 464(4), 4463–4475)**
   One of the earliest applications of CNNs to astronomical imaging. This work focused on distinguishing stars from galaxies in SDSS data, showing that even shallow convolutional architectures can outperform traditional SExtractor and Random Forest pipelines. It established CNNs as a reliable tool for astronomical image classification.

2. **Dieleman et al., 2015 – *Rotation-invariant convolutional neural networks for galaxy morphology prediction* (MNRAS, 450(2))**
   Introduced CNNs with rotation-invariant filters for Galaxy Zoo images, demonstrating that rotational symmetry encoding improves classification accuracy and model robustness for galaxy morphologies. This work forms the baseline reference for orientation-aware models.

3. **Cheng et al., 2020 – *Galaxy Morphology Classification with Deep Learning and the Sloan Digital Sky Survey* (MNRAS, 491(1))**
   Applied a deep CNN (based on ResNet) to large-scale SDSS imaging and showed that deep learning can reproduce expert classifications with high reliability. Provides a strong CNN baseline and demonstrates large-scale preprocessing and label curation methods.

4. **Lin et al., 2023 – *Galaxy Morphological Classification with Efficient Vision Transformers***
   Applied Vision Transformers (ViT) to large astronomical image sets, showing that attention mechanisms capture long-range structural dependencies more effectively than pure CNNs. Provides a foundation for exploring hybrid CNN–ViT architectures.

5. **Cao et al., 2024 – *Galaxy morphology classification based on Convolutional Vision Transformer (CvT)* (Astronomy & Astrophysics, 683, A42)**
   The finalized peer-reviewed publication presenting CvT-13 architecture for galaxy morphology classification. Integrates convolutional layers within a transformer backbone to combine local and global feature representations, achieving improved accuracy and efficiency compared to pure ViT or ResNet models.

6. **Hayat et al., 2022 – *Self-Supervised Representation Learning for Astronomical Images***
   Demonstrated that contrastive self-supervised pretraining on unlabeled sky surveys yields rich representations transferable to galaxy morphology tasks. Suggests a strategy for boosting performance when labeled data are limited.

7. **Walmsley et al., 2023 – *Zoobot: Adaptable Deep Learning Models for Galaxy Morphology***
   Presented a flexible framework with pretrained models trained on millions of Galaxy Zoo classifications. Zoobot enables fine-tuning and transfer learning across surveys, providing a strong practical baseline and open-source tools.

8. **Galaxy10 DECaLS Dataset Documentation – astroNN Project (Li et al.)**
   Supplies 17 000 DECam Legacy Survey images labeled by morphological type and standardized preprocessing scripts. This dataset offers high-quality input for supervised training and fair benchmarking across methods.

## 4. Project summary

### 4.1 Project description.

Galaxies come in many fascinating shapes, astronomers have classified galaxies by their morphology for over a century, but doing this manually for millions of images from modern telescopes is no longer feasible. The goal of this project is to build a deep learning model that can automatically classify galaxies by their visual type and perform recognition of structural patterns that define different galaxy morphologies.

### 4.2

**Dataset:** [Galaxy10 DECals Dataset](https://paperswithcode.com/dataset/galaxy10-decals) – 17,000 labeled images of galaxies from the DECam Legacy Survey, curated for morphology classification.
**Classes:** Elliptical, Spiral, Edge-on Spiral, Merging, and others.

### 4.3 Work breakdown structure

| Task                                          | Estimated Hours |
| --------------------------------------------- | --------------- |
| Dataset collection and preprocessing          | 15              |
| Designing and building an appropriate network | 12              |
| Training and fine-tuning                      | 20              |
| Additional fixes                              | 12              |
| Application for results presentation          | 10              |
| Final report                                  | 8               |
| Presentation preparation                      | 8               |
| **Total**                                     | **85**          |

## 5. Contact

For any questions regarding this project:
**Student:** Iana Bembeeva
**TU email:** e52017248@student.tuwien.ac.at
**Course:** Applied Deep Learning, TU Wien (Winter 2025)
