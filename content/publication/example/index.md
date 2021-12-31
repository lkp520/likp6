---
title: "Hyperspectral Image Denoising Based on Multi-Resolution Dense Memory Network"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Kengpeng Li

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2022-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-11-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Wowchemy Conference*
publication_short: In *ICW*

abstract: Hyperspectral images (HSIs) denoising is a very important pre-processing step since noise will seriously degrade the HSIs quality. In this paper, we propose a multi-resolution dense memory denoising network. Speciﬁcally, in order to fully use the spatial-spectral correlation of hyperspec- tral image (HSI), target noisy band and multiple adjacent bands of HSI are extracted as our network input. After feature extraction by convolution kernels, the feature map is divided into res- olution of diﬀerent sizes through average pooling operation. For each resolution, according to the power law distribution of memory system, we design a dense connection structure in which we use weighted sum of the output feature maps for all previous layers. Then, the deconvolution is used for up sampling. Finally, dilated convolution and skip connection are utilized to obtain the denoised HSI. Our method outperforms state-of-the-art denoising algorithms in both quantitative and visual eﬀects, as demonstrated by denoising experiments on simulated and real HSI datasets.

# Summary. An optional shortened abstract.
summary: In this paper, we propose a multi-resolution dense memory network for HSI denoising. This method fully considers the spatial-spectral correlation of HSIs, introduces a dense connection structure based on power law memory to capture the feature information of multiple layers, and also designs a multi-resolution module and dilated convolution to further extract the multi-scale context informa- tion of HSIs. The proposed method outperformed other state-of-the-art methods in both simulated and real data experiments of HSI restoration. There is still large room for improvement in our approach. For example, our algorithm can only deal with the independently and identically dis- tributed (i.i.d.) noise, however, in HSIs, the noise normally diﬀers from one band to another. In our future work, we will consider extending our network to make it suitable for non-independent identically distributed (non-i.i.d.) noise. Mean- while, we will try to design a network structure with better generalization performance that is applicable for more types of HSIs.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
