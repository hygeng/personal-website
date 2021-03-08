---
title: "Gated Sequential Recommendation System with Social and Textual Information under Dynamic Contexts"
authors:
- Haoyu Geng
- Shuodian Yu, Xiaofeng Gao, and Guihai Chen, , The 26th International Conference on Database Systems for Advanced Applications (DASFAA), Taipei, Taiwan, April 11-14, 2021
date: "2021-04-14T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *HISR*
publication_short: In *DASFAA*

abstract: Recommendation systems are undergoing plentiful practices in research and industry to improve consumers' satisfaction.  In recent years, many research papers leverage abundant data from heterogeneous information sources to grasp diverse preferences and improve overall accuracy. Some noticeable papers proposed to extract users' preference from information along with ratings such as reviews or social relations. However, their combinations are generally static and less expressive without considerations on dynamic contexts in users' purchases and choices. In this paper, we propose  Heterogeneous Information Sequential Recommendation System (HISR), a dual-GRU structure that builds the sequential dynamics behind the customer behaviors, and combines preference features from review text and social attentional relations under dynamics contexts.  A novel gating layer is applied to dynamically select and explicitly combine two views of data. Moreover, in social attention module, temporal textual information is brought in as a clue to dynamically select friends that are helpful for contextual purchase intentions as an implicit combination. We validate our proposed method on two large subsets of real-world local business dataset Yelp, and our method outperforms the state of the art methods on related tasks including social, sequential and heterogeneous recommendations. 

# Summary. An optional shortened abstract.
summary: Recommendation Systems , Sequential Recommendation , Gating Mechanism

tags:
- Recommendation
featured: false

links:
- name: 
  url: 
url_pdf: 
url_code: 
url_dataset: 
url_poster: 
url_project: 
url_slides: 
url_source: 
url_video: 

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).

