---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Research Scientist
    company: Siemens
    company_url: 'www.siemens.com'
    # company_logo: org-gc
    location: Princeton, New Jersey
    date_start: '2020-08-03'
    date_end: ''

    description: |2-
        Responsibilities include:
        * Developing Physics-Informed Neural networks  to accelerate scientific discovery and design
        * Optimization of code for GPUs
        * Tools used: PyTorch, TensorFlow
        
  - title: Research \& Development Engineer II
    company: Ansys, Inc.
    company_url: 'www.ansys.com'
    # company_logo: channels4_profile
    location: Pittsburgh, PA
    date_start: '2019-03-25'
    date_end: '2020-07-31'
    description: |2-
        Responsibilities include:
        * Developed and Maintain solver for the Ansys Twinbuilder       product
        * Tools used: C++, Python
    # description: Taught electronic engineering and researched semiconductor physics.

design:
  columns: '2'
---
