---
title: 'Indoor Smartphone SLAM with Learned Echoic Location Features'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Wenjie Luo
  - Qun Song
  - Zhenyu Yan
  - Rui Tan
  - Guosheng Lin

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-11-06T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-11-06T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: "In *The 20th ACM Conference on Embedded Networked Sensor Systems*"
publication_short: "In *SenSys'22*"

abstract: Indoor self-localization is a highly demanded system function for smartphones. The current solutions based on inertial, radio frequency, and geomagnetic sensing may have degraded performance when their limiting factors take effect. In this paper, we present a new indoor simultaneous localization and mapping (SLAM) system that utilizes the smartphone's built-in audio hardware and inertial measurement unit (IMU). Our system uses a smartphone's loudspeaker to emit near-inaudible chirps and then the microphone to record the acoustic echoes from the indoor environment. Our profiling measurements show that the echoes carry location information with sub-meter granularity. To enable SLAM, we apply contrastive learning to construct an echoic location feature (ELF) extractor, such that the loop closures on the smartphone's trajectory can be accurately detected from the associated ELF trace. The detection results effectively regulate the IMU-based trajectory reconstruction. Extensive experiments show that our ELF-based SLAM achieves median localization errors of 0.1m, 0.53m, and 0.4m on the reconstructed trajectories in a living room, an office, and a shopping mall, and outperforms the Wi-Fi and geomagnetic SLAM systems.


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

url_pdf: 'https://arxiv.org/abs/2210.08493'
# url_code: 'https://github.com/jiegev5/PhyAug'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_video: https://www.youtube.com/watch?v=5BVTtu-Nfko&ab_channel=WenjieLuo

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Overview'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - acoustic-echo

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
