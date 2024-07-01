---
# Leave the homepage title empty to use the site title
title: "Saptarshi Chakraborty"
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
     # button:
     #   text: Download CV
     #   url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: 
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        My current research lies in the intersection of Statistics and deep learning theory. In particular, I am interestd why deep learners work from a non-parametric statistical viewpoint. I have been studying the non-parametric convergence rates for different deep learners, especially GANs, WAEs etc., under the so-called manifold hypothesis. To learn more, please see our [GAN paper](https://arxiv.org/abs/2401.15801).
    
        Prior to joing Berkeley, I explored different aspects of high-dimensional data clustering in Prof. Das's lab at the Indian Statistical Institute, Kolkata.
         
       # Please reach out to collaborate 😃
    
    design:
      columns: '1'
  - block: resume-awards
    id: awards
    content:
      title: Awards
      username: admin
    design:
      css_class: dark
      background:
        color: grey
    
 # - block: collection
 #   id: papers
 #   content:
 #     title: Featured Publications
 #     filters:
 #       folders:
 #         - publication
 #       featured_only: true
 #   design:
 #     view: article-grid
 #     columns: 2
  - block: collection
    id: papers
    content:
      title: Publications and Preprints
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation

  - block: collection
    id: teaching
    content:
      title: Teaching
      text: I served as a Graduate Student Instructor (GSI), also known as teaching assistant for the following courses at UC Berkeley.
      filters:
        folders:
          - teaching
    design:
      view: article-grid
      fill_image: false
      columns: 2
  - block: markdown
    id: contact
    content:
      title: Contact
      text: |-
        Please feel free to email me at saptarshic'at'berkeley.edu

        Address: 367 Evans Hall, University Dr., Berkeley, CA, 94703, USA.
         
---
