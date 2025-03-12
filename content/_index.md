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
        My research primarily revolves around Machine Learning, Graph Analytics, and Pattern Recognition, with a strong emphasis on optimization and data-driven solutions. My Ph.D. thesis, completed at LIRIS, Université Claude Bernard Lyon 1, explored efficient algorithms for graph matching and large-scale data management, solving critical scalability and performance issues.

        Currently, my research includes advanced anomaly detection in dynamic graphs and deep learning techniques for graph-based data, enhancing the robustness of cybersecurity systems against advanced persistent threats.
        
        My recent contributions to conferences such as VLDB underline my commitment to graph sparsification techniques for efficient graph compression, maintaining neighborhood structures to facilitate effective graph analysis in databases.

        Additionally, my interdisciplinary approach is exemplified by my contribution to computational geometry and archaeological studies, including the analysis of ancient mega-structures through geometric graph matching techniques, as highlighted in my publication in PLOS ONE. I actively engage with optimization problems, developing hybrid multi-objective algorithms published in high-ranked journals such as Pattern Recognition Letters and Engineering Applications of Artificial Intelligence.

        I remain involved academically through peer reviews for reputable journals, mentoring master's students in Data Science and AI, and delivering specialized courses on graph neural networks and operational research.

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
