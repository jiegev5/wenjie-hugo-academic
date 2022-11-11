---
title: Physics-directed data augmentation for deep sensing model transfer in cyber-physical systems
summary: Domain shift can greatly degrade the performance of deep model. We exploit the first principle governing the domain shift to augment data for retraining the model. In the case studies of speech recognition, with 5-second unlabelled data collected from the target-domain microphones, we can recover the accuracy losses due to microphone characteristic variations by up to 72%.
tags:
  - Conference papers
date: '2021-05-20T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: PhyAug overview
  focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: 'https://github.com/jiegev5/PhyAug'
url_pdf: 'https://arxiv.org/abs/2104.01160'
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---
Run-time domain shifts from training-phase domains are common in sensing systems designed with deep learning. The shifts can be caused by sensor characteristic variations and/or discrepancies between the design-phase model and the actual model of the sensed physical process. To address these issues, existing transfer learning techniques require substantial target-domain data and thus incur high post-deployment overhead. This paper proposes to exploit the first principle governing the domain shift to reduce the demand on target-domain data. Specifically, our proposed approach called PhyAug uses the first principle fitted with few labeled or unlabeled source/target-domain data pairs to transform the existing source-domain training data into augmented data for updating the deep neural networks. In two case studies of keyword spotting and DeepSpeech2-based automatic speech recognition, with 5-second unlabeled data collected from the target microphones, PhyAug recovers the recognition accuracy losses due to microphone characteristic variations by 37% to 72%. In a case study of seismic source localization with TDoA fngerprints, by exploiting the frst principle of signal propagation in uneven media, PhyAug only requires 3% to 8% of labeled TDoA measurements required by the vanilla fingerprinting approach in achieving the same localization accuracy.

