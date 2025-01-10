---
# Leave the homepage title empty to use the site title
title: "SihaoHan"
date: 2025-01-01
type: landing

design:
  # Default section spacing
  spacing: "4rem"

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
          
  - block: markdown
    # block: collection
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        <style>
          .custom-block {
            font-size: 14pt;
            text-align: justify; /* 设置两端对齐 */
            margin: 0 -100px; /* 负外边距扩展超出容器 */
            padding: 20px; /* 设置内边距 */
            background-color: #f9f9f9; /* 背景颜色 */
            border: 1px solid #ddd; /* 添加边框 */
            border-radius: 8px; /* 圆角 */
            font-family: Arial, sans-serif; /* 自定义字体 */
            line-height: 1.4; /* 调整行高 */
          }
        </style>
        <div class="custom-block">
          My research focuses on the wave characteristics and impact behavior of elastic and mechanical metamaterials, with a particular interest in multifunctional metamaterials. I am using advanced numerical simulation and machine learning techniques to enable multi-performance prediction, optimization, and on-demand customization of advanced materials and structures, in an attempt to push the frontier of combining artificial intelligence and solid mechanics. The architected structures I have studied include honeycombs, kiri/origamis, pixelated topologies, and acoustic black holes. To date, I have published 9 journal papers as the (co-)first author, with an additional 1 currently under review.

          I have earned my bachelor's degree from Southwest Jiaotong University in 2021. I am a student in a successive postgraduate and doctoral program, and expect to receive my PhD in the summer of 2027.  My PhD thesis is **_Machine learning‑based performance prediction and topology customization of multifunctional metamaterials_** under the supervision of  [Prof. Qiang Han](https://www2.scut.edu.cn/jtxy/2023/0430/c35044a500284/page.htm) and [A/Prof. Chunlei Li](https://www2.scut.edu.cn/jtxy/2023/0430/c35045a500283/page.htm). 

          If you have any questions or are interested in collaborating, feel free to contact me at ct_hansihao@mail.scut.edu.cn. I look forward to connecting with you 😃 !!!
        </div>
    design:
      columns: '1'
      # spacing:
      #   padding: [0, '-100px', 0, '-100px']      

  # - block: resume-experience
  #   content:
  #     username: admin
  #   design:
  #     # Hugo date format
  #     date_format: 'January 2006'
  #     # Education or Experience section first?
  #     is_education_first: false

  # - block: collection
  #   # id: papers
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - first_author_publication
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2


  - block: collection
    id: papers  
    content:
      title: First Author Publications
      text: ""
      count: 0
      filters:
        folders:
          - first_author_publication
        exclude_featured: false
    design:
      view: citation


  # - block: collection
  #   content:
  #     title: Full Publications
  #     text: ""
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: false
  #   design:
  #     view: citation

  - block: collection
    id: talks
    content:
      title: Oral presentation
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1

  # - block: collection
  #   id: news
  #   content:
  #     title: Full Publications
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: publication
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 0
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]


  - block: resume-awards
    content:
      title: Awards
      username: admin

  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!
        
        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
