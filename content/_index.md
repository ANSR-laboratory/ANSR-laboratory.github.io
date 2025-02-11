---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: home_banner.png
          filters:
            brightness: 1
          parallax: true
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['10px', '0', '10px', '0']
      css_class: fullscreen
  - block: hero
    content:
      title: |
        We develop and apply advanced statistical and machine learning methods to improve neuroimaging analysis and enhance our understanding of brain function in health and disease.
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The Applied Neuroimaging Statistics Research Laboratory is an academic research group dedicated to improving statistical methodologies for analyzing functional magnetic resonance imaging (fMRI) data. Our research spans multiple domains, including the development of novel computational tools for studying the brain's structural and functional connectome. We leverage state-of-the-art techniques such as multi-modal data fusion and machine learning to address fundamental questions in neuroimaging and to enhance our understanding of neurological and psychiatric disorders. 
        
        Our work bridges theory and application, combining methodological innovation with empirical investigations in neuroimaging. By integrating advanced statistical approaches with neurobiological data, we aim to refine how we study brain networks, mental illness, and cognitive function.

        We are based in the <a href="https://www.mcleanmri.org/" target="_blank">McLean Imaging Center</a> at McLean Hospital & the <a href="https://psych.hms.harvard.edu/" target="_blank">Department of Psychiatry</a> at Harvard Medical School. 
        
        {{% cta cta_link="./members/" cta_text="Meet the Team →" %}}

#  - block: markdown
#    content:
#      title:
#      subtitle:
#      text: |
#        {{% cta cta_link="./members/" cta_text="Meet the Team →" %}}
#    design:
#      columns: '1'
    
# - block: collection
#   content:
#     title: Latest News
#     subtitle:
#     text:
#     count: 5
#     filters:
#       author: ''
#       category: ''
#       exclude_featured: false
#       publication_type: ''
#       tag: ''
#     offset: 0
#     order: desc
#     page_type: post
#   design:
#     view: card
#     columns: '1'

# - block: markdown
#   content:
#     title:
#     subtitle: ''
#     text:
#   design:
#     columns: '1'
#     background:
#       image: 
#         filename: coders.jpg
#         filters:
#           brightness: 1
#         parallax: false
#         position: center
#         size: cover
#         text_color_light: true
#     spacing:
#       padding: ['20px', '0', '20px', '0']
#     css_class: fullscreen

# - block: collection
#   content:
#     title: Latest Preprints
#     text: ""
#     count: 5
#     filters:
#       folders:
#         - publication
#       publication_type: 'article'
#   design:
#     view: citation
#     columns: '1'
---
