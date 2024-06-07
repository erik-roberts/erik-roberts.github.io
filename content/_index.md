---
# Leave the homepage title empty to use the site title
title: ""
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
      button:
        text: Download CV
        url: uploads/cv.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: cvc.jpg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: 'Research Projects'
      id: 'projects'
      text: |-
        ### Chronic kidney disease progression after cardiac surgery-associated acute kidney injury
        University of Michigan, Department of Anesthesiology<br>
        Advisor: Michael Mathis, MD<br>
        Research Track Resident, 2023 – 2025<br>
        Applying machine learning to cardiac surgery-associated acute kidney injury data. Characterizing patient and perioperative features associated with progression to chronic kidney disease. Identifying recovery trajectories and morbidity risk profiles for kidney injury subtypes.


        ### Global neural rhythm control by local neuromodulation
        Boston University, Department of Mathematics & Statistics, Neural Dynamics Group<br>
        Advisor: Nancy Kopell, PhD<br>
        Graduate Research Assistant, June 2014 – May 2019<br>
        Created biophysical computational models of neural oscillations to better understand sleep architecture and general anesthesia. Utilized statistical learning and signal processing techniques to analyze brain electrical recordings. Developed software for neural simulation and data visualization.


        ### Computational Modeling of Heart Cell Molecular Signaling
        UC San Diego, Department of Bioengineering, Cardiac Mechanics Research Group<br>
        Advisor: Andrew McCulloch, PhD<br>
        Research Assistant, January 2011 – June 2012<br>
        Developed computational model of heart cell molecular signaling.


        ### Tissue Modeling in a Patient-Specific Surgical Simulator
        Stanford School of Medicine, Department of Otolaryngology Head & Neck Surgery<br>
        Advisor: Nikolas Blevins, MD<br>
        Research Intern, Summer 2009 – 2011<br>
        Designed workflow to create patient-specific virtual models for surgical simulator.

    design:
      columns: '1'
  - block: collection
    content:
      title: Publications
      text: ""
      filters:
        folders:
          - publication
    design:
      view: citation
  
---
