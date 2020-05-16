---
title: "TinyLink"
summary: "A Holistic System for Rapid Development of IoT Applications"
authors: [admin]
tags: ["TinyLink","IoT", "Rapid Development"]
categories: []
date: 2017-04-26T09:34:23+08:00

# Optional external URL for project (replaces project detail page).
external_link: ""

image_prview : "linklab1.png"
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "linklab1"
  focal_point: "Smart"
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
Rapid development is essential for IoT (Internet of Things) application developers to obtain first-mover advantages and reduce the development cost. 

We present TinyLink ([Home Page](http://tinylink.cn/TinyLink/view/en/index.html)), a holistic system for rapid development of IoT applications. 
The key idea of TinyLink is to use a top-down approach for designing both the hardware and the software of IoT applications. 
Developers write the application code in a C-like language to specify the key logic of their applications, without dealing with the details of the specific hardware components. 
Taking the application code as input, TinyLink automatically generates the hardware configuration as well as the binary program executable on the target hardware platform. 
TinyLink provides unified APIs for applications to interact with the underlying hardware components. 

We implement TinyLink and evaluate its performance using realworld IoT applications. 
Results show that: (1) TinyLink achieves rapid development of IoT applications, reducing 52.58% of lines of code in average compared with traditional approaches; (2) TinyLink searches a much larger design space and thus can generate a superior solution for the hardware configuration, compared with the state-of-the-art approach; (3) TinyLink incurs acceptable overhead in terms of execution time and program memory.