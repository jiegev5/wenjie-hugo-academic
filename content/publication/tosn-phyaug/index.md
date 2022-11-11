---
title: 'Physics-directed data augmentation for deep model transfer to specific sensor'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Wenjie Luo
  - Zhenyu Yan
  - Qun Song
  - Rui Tan

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-05-20T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-05-20T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: "*ACM Transactions on Sensor Networks*"
publication_short: "*ACM TOSN*"

abstract: Run-time domain shifts from the training phase caused by sensor characteristic variation incur performance drops of the deep learning-based sensing systems. To address this problem, existing transfer learning techniques require substantial target-domain data and incur high post-deployment overhead. Differently, we propose to exploit the first principle governing the domain shift to reduce the demand for target-domain data. Specifically, our proposed approach called PhyAug uses the first principle fitted with few labeled or unlabeled data pairs collected by the source sensor and the target sensor to transform the existing source-domain training data into the augmented target-domain data for calibrating the deep neural networks. In two audio sensing case studies of keyword spotting and automatic speech recognition, PhyAug recovers the recognition accuracy losses due to microphones' characteristic variations by 37% to 72% with 5-second unlabeled data collected from the target microphones. In a case study of acoustics-based room recognition, PhyAug recovers the recognition accuracy loss caused by smartphone microphone variation by 33% to 80%. In the last case study of fisheye image recognition, PhyAug reduces the image recognition error due to the camera-induced distortions by 72%.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags: []
tags:
  - Conference papers
# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2104.01160'
url_code: 'https://github.com/jiegev5/PhyAug'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_video: https://www.youtube.com/watch?v=LcIVBRx4x-o&ab_channel=CPS-IoTWeek-IPSN

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'PhyAug Overview'
  focal_point: ''
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - phyaug

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
