---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "0.2rem"

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: biography
    content:
      username: admin
      # Show a call-to-action button under your biography? (optional)
      # button:
      #   text: Download Résumé
      #   url: uploads/resume.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: 1.jpg
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
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: true

  - block: markdown
    content:
      title:  
      text: |
       <div style="margin-left: -7rem; padding-left: 0.5rem;">
       <h2 style="text-align: left; margin-bottom: 1rem; font-weight: bold; font-size: 0.8em">Selected Publication</h2>

       <div style="border-left: 4px solid #ff6b35; padding-left: 20px; margin-bottom: 20px; font-size: 0.6em;"> 
        
        **2025**
        
        **LSA: A Long-Short-term Aspect Interest Transformer for Aspect-Based Recommendation**  
        Le Liu, Junrui Liu⋆, Yunhan Gao, Ziheng Wang, and Tong Li  
        *The 26th International Conference on Web Information Systems Engineering (WISE), 2025.* <span style="background-color: #28a745; color: white; padding: 2px 6px; border-radius: 3px; font-size: 0.8em; font-weight: bold;">CCF C</span>
        
        </div>
       </div>
    design:
      columns: '1'
      css_style: |
        .block-markdown .block-title {
          text-align: left !important;
        }


  - block: markdown
    content:
      title: ""
      text: |
        <div style="margin-left: -9rem; padding-left: 0.5rem;">
        <h2 style="text-align: left; margin-bottom: 1rem; font-weight: bold; font-size: 0.8em;">Awards</h2>
        
        <div style="font-size: 0.6em; line-height: 1.4;">
        
        **National Second Prize, China Undergraduate Mathematical Contest in Modeling (CUMCM)**  
        *November 2024*
        
        </div>
        </div>
    design:
      columns: '1'

    
  # - block: languages
  #   content:
  #     title: Languages
  #     username: admin
---
<script type="text/javascript" id="mmvst_globe" src="//mapmyvisitors.com/globe.js?d=EfPdH0FUwHDYhRRshEWusGW0NlID5HkuVGwtjsUFIeI"></script>
