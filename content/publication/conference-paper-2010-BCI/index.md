---
title: "Performance analysis of LDA, QDA and KNN algorithms in left-right limb movement classification from EEG data"
authors:
- Saugat Bhattacharyya
- Anwesha Khasnobish
- admin
- Amit Konar
- DN Tibarewala
date: "2010-12-16T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2010 International Conference on Systems in Medicine and Biology* at IIT Kharagpur
publication_short: In *ICSMB 2010*

abstract: Brain Computer Interface (BCI) improve the lifestyle of the normal people by enhancing their performance levels. It also provides a way of communication for the disabled people with their surrounding who are otherwise unable to physically communicate. BCI can be used to control computers, robots, prosthetic devices and other assistive technologies for rehabilitation. The dataset used for this study has been obtained from the BCI competition II 2003 databank provided by the University of Technology, Graz. After pre-processing of the signals from their electrodes (C3 & C4), the wavelet coefficients, Power Spectral Density of the alpha and the central beta band and the average power of the respective bands have been employed as features for classification. In one of the approaches we fed all the extracted features individually and in the other approach we considered all features together and submitted them to LDA, QDA and KNN algorithms distinctly to classify left and right limb movement. The aim of this study is to analyze the performance of linear discriminant analysis (LDA), quadratic discriminant analysis (QDA) and K-nearest neighbor (KNN) algorithms in differentiating the raw EEG data obtained, into their associative movement, namely, left-right movement. Also the importance of the feature vectors selected is highlighted in this study. The total set to feature vector comprising all the features (i.e., wavelet coefficients, PSD and average band power estimate) performed better with the classifiers without much deviation in the classification accuracy, i.e., 80%, 80% and 75.71% with LDA, QDA and KNN respectively. Wavelet coefficients performed best with QDA classifier with an accuracy of 80%. PSD vector resulted in superior performance of 81.43% with both QDA and KNN. Average band power estimate vector showed highest accuracy of 84.29% with KNN algorithm. Our approach presented in this paper is quite simple, easy to execute and is validated robustly with a large dataset.

# Summary. An optional shortened abstract.
summary: Brain Computer Interface (BCI) improve the lifestyle of the normal people by enhancing their performance levels. It also provides a way of communication for the disabled people with their surrounding who are otherwise unable to physically communicate. BCI can be used to control computers, robots, prosthetic devices and other assistive technologies for rehabilitation.

tags:
- BCI
- Machine Learning
- Rehabilitative Engineering
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://ieeexplore.ieee.org/abstract/document/5735358
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://scienews.com/)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- HRV

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
