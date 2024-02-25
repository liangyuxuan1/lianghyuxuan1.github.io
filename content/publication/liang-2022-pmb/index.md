---
title: Phase function estimation from a diffuse optical image via deep learning
authors:
- Yuxuan Liang
- Chuang Niu
- Chen Wei
- Shenghan Ren
- Wenxiang Cong
- Ge Wang
date: '2022-03-01'
publishDate: '2023-12-23T03:46:13.858160Z'
publication_types:
- article-journal
publication: '*Physics in Medicine & Biology*'
doi: 10.1088/1361-6560/ac5b21
abstract: Objective. The phase function is a key element of a light propagation model for Monte Carlo (MC) simulation, which is usually fitted with an analytic function with associated parameters. In recent years, machine learning methods were reported to estimate the parameters of the phase function of a particular form such as the Henyey–Greenstein phase function but, to our knowledge, no studies have been performed to determine the form of the phase function. Approach. Here we design a convolutional neural network (CNN) to estimate the phase function from a diffuse optical image without any explicit assumption on the form of the phase function. Specifically, we use a Gaussian mixture model (GMM) as an example to represent the phase function generally and learn the model parameters accurately. The GMM is selected because it provides the analytic expression of phase function to facilitate deflection angle sampling in MC simulation, and does not significantly increase the number of free parameters. Main Results. Our proposed method is validated on MC-simulated reflectance   images of typical biological tissues using the Henyey–Greenstein phase function with different anisotropy factors. The mean squared error of the phase function is 0.01 and the relative error of the anisotropy factor is 3.28%. Significance. We propose the first data-driven CNN-based inverse MC model to estimate the form of scattering phase function. The effects of field of view and spatial resolution are analyzed and the findings provide guidelines for optimizing the experimental protocol in practical applications. Summary. We developed the first data-driven CNN-based inverse Monte Carlo model to estimate the form of scattering phase function. The findings provide guidelines for optimizing the experimental protocol in practical applications.

links:
- name: URL
  url: https://dx.doi.org/10.1088/1361-6560/ac5b21

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/liangyuxuan1/phasefunction2'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
