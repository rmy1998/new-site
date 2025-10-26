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
      text: "[Jie Ma](http://staff.ustc.edu.cn/~jiema/)(4), [Zixiang Xu](https://www.ibs.re.kr/ecopro/zixiangxu/)(4), [Xinqi Huang](https://huangxinqi314.github.io/hxq-website/experience/)(2), Mingze Li(2), Wenchong Chen(1), Xinbu Cheng(1), Guorong Gao(1), [Hong Liu](https://www.ibs.re.kr/ecopro/hongliu/)(1), Yuzhen Qi(1), [Tuan Tran](https://tuaentran.wixsite.com/homepage)(1)."
    design:
      columns: '1'
  - block: markdown
    content:
      title: 'Useful websites'
      subtitle: 'some tools that I recommend for academic research'
      text: |
        - **[Deepseek](https://chat.deepseek.com/)**  
        - **[Inciteful](https://inciteful.xyz/)**  
        - **[Undermind](https://www.undermind.ai/home/)**  
    design:
      columns: '1'
---
