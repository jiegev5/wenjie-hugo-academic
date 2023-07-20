---
title: 'PhD Thesis: Exploiting sensor and process characteristics to tackle label scarcity in AIoT sensing'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin


# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-06-25T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-06-25T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: "In *NTU SCSE*"
publication_short: "In *NTU SCSE*"

abstract: "The Internet of Things (IoT) is a global cyber network that consists of trillions of smart objects, edge devices, fogs, and cloud computing systems. It is a fabrication of data generation infrastructures and computing infrastructures. It is estimated that there will be more than 50 billion edge devices connected to the IoT by 2025. Artificial intelligence (AI), on the other hand, is the driving force that unleashes the full potential of IoT. Recent advances in machine learning, especially in deep learning, have inspired the development of deep neural network (DNN)-based smart sensing applications in IoT. The integration of AI and IoT gives rise to the paradigm of Artificial Intelligence of Things (AIoT). AIoT has paved its way in reshaping smart wearables, smart homes, smart cities, and smart industries. The effectiveness of DNN models hinges on the availability of large, labeled datasets that can unveil valuable feature representations. The widespread use of DNN models in computer vision (CV), natural language processing (NLP), and voice sensing can be attributed to the abundance of labeled training datasets. However, in the domain of AIoT sensing, the availability of such high-quality datasets is limited. The fundamental reason arises from two aspects of AIoT sensing data. Firstly, the annotation of IoT sensing data by humans is a challenging task. Despite the abundance of IoT sensing data, the human-uninterpretable nature of AIoT sensing data makes it difficult for human assistants to understand the meaning behind it if the labeling process is separated from the data collection. Consequently, constructing labeled datasets for AIoT applications demands significant human effort. Secondly, the heterogeneity of IoT sensor hardware and/or the deployment environments of DNN models introduce domain shifts. The domain shifts cause the deviation in data distribution between the testing and training data. It leads to label scarcity for the target-domain dataset, posing challenges for domain adaptation. In summary, label scarcity stands out as a primary challenge in developing effective AIoT sensing applications. Existing solutions for addressing the label scarcity rely on machine learning techniques, such as self-supervised learning, few-shot learning, or transfer learning. These approaches are data-driven and fall short of exploiting the underlying first principles that govern data generation. This thesis proposes to utilize prior knowledge governing data generation to address the label scarcity in the development of machine learning algorithms for AIoT sensing applications. Specifically, it exploits the sensor and process characteristics to develop efficient machine learning models such that the demand for the labeled data can be reduced. The problems to be addressed and the proposed approaches are presented in two studies forming the main technical development of this thesis. The first study targets the run-time domain shift phenomenon in AIoT sensing applications. It utilizes both the sensor and process characteristics to address the label scarcity for target domains where massive labeled datasets are not available. In physics-rich AIoT, the domain shifts are often governed by certain physical laws. For instance, the distribution of indoor temperature is governed by the ﬂuid dynamics model and the microphone data received is determined by its frequency response curve. A comprehension of these physical laws can aid in the creation of more efficient and generalized machine learning models by incorporating physical laws as additional information during the model training. This study proposes an approach called physics-directed data augmentation (PhyAug) to address the run-time domain shifts caused by the sensor and/or process characteristics. Different sensors can respond to the same excitation differently, which results in data distribution deviations. The sensed data is often determined by the hardware characteristics of the sensors and can be described by certain parametric models. PhyAug leverages such parametric models for DNN model transfer. In addition, the process of sensed data collection can exhibit certain characteristics. For example, the sensor readings mounted on human bodies are often correlated with the human body's movement. PhyAug exploits the process characteristics to augment the training data. PhyAug has the following two key features. First, PhyAug augments the training data strategically by following the physical law to transfer DNNs instead of using ad-hoc perturbations or transformations like conventional data augmentation does. Second, PhyAug only requires a small amount of target domain data for law fitting. This data requirement is less than the competing baselines that use transfer learning techniques. The study applies PhyAug to a series of case studies and compares its performance with other possible approaches. The superior performance achieved by PhyAug highlights the potential of PhyAug in addressing a range of physics-governed domain shifts for various AIoT sensing applications. The second study utilizes the process characteristics of data collection to improve the effectiveness of the machine learning algorithm. It addresses the label scarcity in developing DNN-based systems for new AIoT applications. Despite the limited availability of labeled training data, AIoT sensing applications are featured in a wealth of unlabeled data gathered by billions of devices. In machine learning, self-supervised learning is a new technique that can effectively extract feature representations from unlabeled sensing data. Self-supervised learning has found many successful applications in the field of CV, NLP, voice sensing, etc. Nevertheless, using machine learning techniques directly without taking into account the specific characteristics of the sensing data may result in the suboptimal performance of DNN models. This study considers the process characteristics of the sensing data collection and utilizes it to design customized machine learning algorithms. Specifically, it designs ELF-SLAM, a smartphone-based simultaneous localization and mapping (SLAM) system using the learned echoic location features (ELFs). The following challenges are tackled during the design of the system. First, to alleviate the data labeling effort, ELF-SLAM uses a smartphone to collect both inertial moving unit (IMU) data and acoustic data simultaneously. The IMU data is used to estimate user trajectory and provide label information for acoustic data. Due to the long-run drifting issue of IMU data, acoustic echoes are used to detect the loop closures for trajectory regularization. However, conventional acoustic features are ineffective for loop closure detection. To overcome this challenge, this study opts to learn an effective embedding using a DNN model. Second, to address the ineffectiveness of the machine learning algorithm on unlabeled acoustic data, this study exploits the process characteristics of acoustic data collection to design a customized contrastive learning procedure to learn ELFs that can be used to signal loop closures. The customization includes the use of the acoustic simulator for model pre-training, an effective positive/negative data pairing approach based on the spatial-temporal relationship of acoustic data and a new model finetuning based on unlabeled data for target room adaptation. ELF-SLAM exhibits satisfactory performance in both mapping and localization. This study demonstrates the necessity and effectiveness of integrating process characteristics of sensing data collection in machine learning algorithms for AIoT sensing applications. In summary, this thesis targets the label scarcity challenge in developing machine learning algorithms for AIoT sensing applications. It identifies the two fundamental factors contributing to this label scarcity, namely, uninterpretability of sensed data and run-time domain shifts. This thesis proposes to exploit the sensor and process characteristics to address the domain shifts and reduces the machine learning algorithm's reliability on the labeled data. The effectiveness of the proposed approach is demonstrated in a set of distinct AIoT applications. Future research will continue to explore more approaches in combining prior knowledge with machine learning algorithms to develop more efficient DNN models for AIoT sensing applications."


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags: []
tags:
  - Journal articles
# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: './mythesis.pdf'
# url_code: 'https://github.com/jiegev5/PhyAug'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: ''
# url_project: ''
# url_slides: ''
url_source: 'https://dr.ntu.edu.sg/handle/10356/169116'
#　url_video: https://www.youtube.com/watch?v=5BVTtu-Nfko&ab_channel=WenjieLuo

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'PhD Thesis'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - piml

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
<!-- 
{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
