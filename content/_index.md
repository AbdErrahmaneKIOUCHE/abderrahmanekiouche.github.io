---
# Leave the homepage title empty to use the site title
title: "Phd. KIOUCHE"
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
      #button:
        #text: Download CV
        #url: uploads/resume.pdf
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
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |
        I am an **AI Engineer and Data Scientist** specializing in **Natural Language Processing (NLP), Generative AI, and Retrieval-Augmented Generation (RAG)**, with experience in developing AI-driven solutions for **software engineering, cybersecurity, and graph-based analytics**. 

        My work includes optimizing retrieval mechanisms, leveraging knowledge graphs for contextual accuracy, and designing **efficient, scalable algorithms** for various AI applications. I have contributed to projects such as **anti-smishing detection models** for cybersecurity and **graph-based anomaly detection** in IT systems, utilizing techniques like **Graph Neural Networks (GNNs) and streaming algorithms**.

        Additionally, I have experience in **teaching, research, and algorithm optimization**, with a focus on improving the **performance and efficiency** of AI systems.

        Please reach out to collaborate! 😃
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Last Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: My Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
---
