---
title: '首页'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "4rem"

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: biography
    content:
      username: admin
      # Show a call-to-action button under your biography? (optional)
      button:
        text: 下载简历
        url: uploads/resume.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
          filename: 1.jpg
          style: 'height: 500px;'
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'
      # Avatar customization 
      avatar:
        size: large     # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: rounded  # Options: circle (default), square, rounded
  - block: experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: '2006年1月'
      # Education or Experience section first?
      is_education_first: false
  # - block: skills
  #   content:
  #     title: 技能与爱好
  #     username: admin
  - block: awards
    content:
      title: 获奖情况
      username: admin
  # - block: languages
  #   content:
  #     title: 语言能力
  #     username: admin
---
