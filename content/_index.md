---
# Leave the homepage title empty to use the site title
title: "Rong's homepage"
date: 2025-01-07
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
      button:
        text: Download CV
        url: uploads/resume.pdf
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
  - block: collection
    content:
      title: Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: markdown
    content:
      title: 'Co-authors'
      subtitle: ''
      text: "[Jie Ma](http://staff.ustc.edu.cn/~jiema/)(2), Xinqi Huang(1), Xinbu Cheng(1), Guorong Gao(1), Mingze Li(1), [Tuan Tran](https://tuaentran.wixsite.com/homepage)(1), [Zixiang Xu](https://www.ibs.re.kr/ecopro/zixiangxu/)(1), [Hong Liu](https://www.ibs.re.kr/ecopro/hongliu/)(0)."
    design:
      columns: '1'
  - block: markdown
    content:
      title: 'Useful websites'
      subtitle: 'Recommended resources for academic research'
      text: |
        - **[Deepseek](https://chat.deepseek.com/)**  
          AI-powered research assistant for technical queries
        - **[Inciteful](https://inciteful.xyz/)**  
          Literature discovery tool to find related academic papers
        - **[Undermind](https://www.undermind.ai/home/)**  
          Advanced AI paper search engine with deep analysis capabilities
    design:
      columns: '1'
---
