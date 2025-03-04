---
# Leave the homepage title empty to use the site title
title: About
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
        color: "transparent"  # Makes the background behind the image transparent
        video: 
          filename: "ansrbanner.mp4"
          size: cover # Ensures full width
          type: local
          loop: true  # Ensures the video loops continuously
          autoplay: true  # Automatically plays when the page loads
          muted: true  # Mutes the video (recommended for UX)
          position: center
  - block: features
    content:
      title: 'Our Science'
      text: |
        <div style="text-align: center; font-size: 1.2em;"> <!-- Adjust the size as needed -->

        <span style="color:#008ab0; font-size: 1.5em;"><strong>We develop & apply advanced computational methods to improve neuroimaging analysis & enhance our understanding of human brain function.</strong></span>

        <br>

        <img src="https://raw.githubusercontent.com/ANSR-laboratory/ANSR-laboratory.github.io/main/assets/media/full-logo.svg" 
        alt="ANSR Logo"
        style="width: 100%; max-width: 400px; margin: 10px auto; display: block;">

        <br>

        <span style="font-size: 1.2em;">We are based in the <a href="https://www.mcleanmri.org/" target="_blank">McLean Imaging Center</a> at McLean Hospital & the <a href="https://psych.hms.harvard.edu/" target="_blank">Department of Psychiatry</a> at Harvard Medical School.</span>

        </div>
        <br>
        <br>
      items:
        - name: "Neuroimaging Statistics"
          description: "Advancing neuroimaging statistical techniques to study brain structure and function, integrating fMRI, PET, and advanced computational models."
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
        - name: "Psychiatric Neuroimaging of Addiction"
          description: "Using advanced neuroimaging techniques to investigate the neural mechanisms underlying substance use and addiction, with a focus on brain connectivity, cognitive function, and treatment response."
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