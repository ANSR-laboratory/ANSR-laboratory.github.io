---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24

type: landing

sections:
  - block: hero
    content:
      title: ""
      subtitle: ""
      image:
        filename: "placeholder.png"
        focal_point: "center"
    design:
      background:
        image:
          filename: "ansrbanner.svg"
          size: cover  # Ensures full width
          position: center
          parallax: false
  - block: features
    content:
      title: 'Our Science'
      text: |
        <div style="text-align: center;">

        <span style="color:#008ab0;"><strong>We develop & apply advanced computational methods to improve neuroimaging analysis & enhance our understanding of human brain function.</strong></span>

        <br>

        <img src="/assets/media/hms_mcl.svg" alt="HMS & McLean Logo"

        <br>

        We are based in the <a href="https://www.mcleanmri.org/" target="_blank">McLean Imaging Center</a> at McLean Hospital & the <a href="https://psych.hms.harvard.edu/" target="_blank">Department of Psychiatry</a> at Harvard Medical School.

        </div>

        <br>
        <br>
      items:
        - name: "Neuroimaging Research"
          description: "Advancing neuroimaging techniques to study brain structure and function, integrating fMRI, PET, and advanced computational models."
          icon: neuroimaging
          icon_pack: custom
        - name: "Computational Methods"
          description: "Developing machine learning and statistical techniques to analyze complex neuroimaging datasets, uncovering meaningful patterns in brain function and their implications for neuropsychiatric health and disease."
          icon: computation
          icon_pack: custom
        - name: "Big Data in Neuroscience"
          description: "Leveraging large-scale datasets like HCP and ADNI to understand individual variability and brain-behavior relationships."
          icon: data
          icon_pack: custom
        - name: "Biological Psychiatry"
          description: "Investigating the biological basis of psychiatric disorders using brain imaging, computational modeling, and multi-modal data analysis to uncover brain-behavior associations and inform precision medicine approaches."
          icon: biopsych
          icon_pack: custom
        - name: "Open Science & Reproducibility"
          description: "Promoting transparency through open-source tools, data sharing, and reproducible workflows in neuroimaging research."
          icon: science
          icon_pack: custom
        - name: "Mentorship & Collaboration"
          description: "Fostering an inclusive, diverse, and supportive research environment for trainees and interdisciplinary collaborations."
          icon: mentor
          icon_pack: custom
  - block: hero
    content:
      title: Lab Values
      image:
        filename: welcome.jpg
      text: |
        <span style="color:#008ab0;">**Accessibility, Diversity, Equity, Inclusion, & Belonging**</span>
        
        At the **ANSR Lab**, we believe that **scientific discovery flourishes when all voices are heard**, and we actively work to **break down barriers** that have historically excluded underrepresented groups in STEM. Our lab is a space where **collaboration, respect, and belonging** are the foundation of both our research and mentorship.  

        Through **thoughtful mentorship, open science practices, and equitable research opportunities**, we aim to contribute to a scientific community that reflects and serves the diversity of the world around us. We **welcome scholars of all backgrounds** and strive to ensure that **our work promotes knowledge that is accessible, transparent, and impactful for all.**  

        {{% cta cta_link="./members/" cta_text="Meet the Team →" %}}
---