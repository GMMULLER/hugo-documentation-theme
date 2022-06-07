---
# An instance of the Blank widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: blank

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 15

# Section title
title: Description

# Section subtitle
subtitle:

# Section design
design:
  # Use a 1-column layout
  columns: "1"
  background:
    color: 'white'
    text_color_light: false

advanced:
  css_style: 'border-bottom: 1px dotted lightgrey; text-align: justify; padding-left: 10px; padding-right: 10px'
---

DeepShadow is a framework that can automatically predict shadow casting in a city from building height information. Its underlying technology is based in a Generative Adversarial Network (GAN), more specifically the Pix2Pix architecture (with some small modifications). DeepShadow's primary motivation is the impact that shadow management can have in people's quality of live, since it can affect levels of comfort, heat distribution, public parks, and so on.

While other frameworks that work with shadow determination exist, they commonly use computationally expensive techniques such as Shadow Maps and Ray Tracing, limiting its utilization to small and punctual areas. On the other hand, DeepShadow can be used to apply the already trained Neural Network to a new city in much simpler, bigger and faster way.

