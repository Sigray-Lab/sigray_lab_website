---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    id: about 
    content:
      title: |
        Evaluating geroprotective interventions using *in vivo* medical imaging 
      image:
        filename: 
      text: |
        <br>
        We aim to develop biomarkers and new treatments for neurodegenerative diseases. We do this by applying medical imaging techniques, such as MRI, PET and CT, to pre-clinical models of neurodegeneration, as well as human patients. Currently, we are running an academically sponsored phase IIa trial in early Alzheimer's disease, where we assess the effect of the drug sirolimus (a.k.a. rapamycin) on neurodegeneration, brain metabolism and aging processes.
         <br>
        Our work also involves developing and validating biomarkers of aging that can be used as endpoints in clinical trials of geroprotective compounds. To this end, we apply machine learning models to large batches of multi-modal imaging data to estimate the biological age of different organ-systems in the human body.

  - block: people
    id: people
    content:
      title:
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Group leader
          - Researchers and staff
          - Colaborators
          - Alumni
      sort_by: Params.position
      sort_ascending: true
    design:
      show_interests: true
      show_role: true
      show_social: true

#  - block: markdown
#    id: collaborators
#    content:
#      title: Key Collaborators
#      text: |
#        - [Mikael Palner](https://portal.findresearcher.sdu.dk/da/persons/mpalner), small-animal PET imaging research group leader at the University of Southern Denmark. <br>
#        - [Todd Ogden](https://www.publichealth.columbia.edu/profile/r-todd-ogden-phd), vice chair of Columbia University #Department of Biostatistics, NYC, USA. <br> 
#        - [Miia Kivipelto](https://ki.se/en/people/miia-kivipelto), research group leader and head of Karolinska Hospital Theme Aging R&D. <br>
#        - [Pete A. Williams](https://ki.se/en/people/pete-williams), research group leader at KI/St Eriks Eye Hospital. <br>

  - block: markdown
    id: ERAP
    content:
      title: ERAP
      text: |
        <br>
        "Evaluating Rapamycin in Alzheimer's disease using Positron emission tomography" (or ERAP for short) is a clinical phase IIa pilot trial. ...     

  - block: collection
    id: publications
    view: citation
    content:
      title: Selected publications 
      subtitle: ''
      text:
      filters:
        tags: publication
  
---
