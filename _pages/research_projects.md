---
title: "PHD Research Projects"
permalink: /research_projects/
author_profile: true
---

## ![](https://img.shields.io/badge/Date-2016/07–2019/12-{green}.svg) **Robust text detection**

**Mentor: MSRA Researcher [Qiang Huo](https://www.microsoft.com/en-us/research/people/qianghuo/) and [Lei Sun](https://www.microsoft.com/en-us/research/people/lsun/)**   
* The first to propose to use Faster R-CNN and Mask R-CNN to address the text detection problem 
* Proposed **a novel anchor-free region proposal network (AF-RPN)** that can generate high-quality proposals of various shapes in an anchor-free manner to get rid of hand-crafted anchor design for Faster/Mask R-CNN framework; **The idea of anchor-free is also propular in the field of generic object detection recently**
* Proposed **a novel Relation Network based line grouping approach** to grouping text primitives effectively and detecting text instances with large inter-character spaces robustly
* Proposed **a new region-wise adaptive scaling approach** to detecting small text efficiently on high resolution images (Achieved a competitive F-measure of 77.49% by only processing 896x896 pixels on average for each image on ICDAR-2017 MLT dataset)
* Achieved **state-of-the-art results** on horizontal (ICDAR-2013), multi-oriented (ICDAR-2017 MLT, ICDAR-2015 and MSRA-TD500) and curved (Total-Text and SCUT-CTW1500) text detection benchmarks
* Deployed in the industry-leading [Microsoft’s new-generation OneOCR engine](https://azure.microsoft.com/en-us/services/cognitive-services/computer-vision/?from=timeline&isappinstalled=0#text) in [Microsoft Cognitive Services](https://azure.microsoft.com/en-us/services/cognitive-services/), outperforming [Google Vision API](https://cloud.google.com/vision/) significantly on the challenging indoor dataset including 11 scenarios (e.g., “document”, “receipt”, “invoice”, “street view”, and “product label”, etc.)

## ![](https://img.shields.io/badge/Date-2015/09–2016/07-{green}.svg) **High performance Chinese font recognition**

**Mentor: [Prof. Lianwen Jin](http://www.hcii-lab.net/lianwen/)**

* Proposed **a new data augmentation and regularization technique**, namely DropRegion, to generate a large number of stochastic variant font samples by selectively disrupting local regions of characters; 
* The similar idea can be found in the paper entitled [“DropBlock: A regularization method for convolutional networks”](https://arxiv.org/pdf/1810.12890.pdf) proposed by Google Brain
* Achieved high performance on Chinese font recognition with only a few real character training samples

## ![](https://img.shields.io/badge/Date-2014/09–2015/07-{green}.svg) **Offline handwritten Chinese character recognition**

**Mentor: [Prof. Lianwen Jin](http://www.hcii-lab.net/lianwen/)**

* The first to propose to incorporate directional features (e.g., Gabor, HoG and gradient feature) as domain knowledge into deep convolutional neural network to boost performance on offline HCCR
*	Achieved **a new state-of-the-art result** on ICDAR-2013 offline HCCR competition dataset; 
* Source code of our approach has been publicly available on [GitHub](https://github.com/zhongzhuoyao/HCCR-GoogLeNet)
