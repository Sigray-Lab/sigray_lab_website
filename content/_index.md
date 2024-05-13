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
       Plaven-Sigray Research Group <br>
       Evaluating geroprotective interventions using *in vivo* medical imaging 
      image:
        filename: 
      text: |
        <br>
       This research group aims to develop biomarkers and new treatments for neurodegenerative diseases by applying neuroimaging techniques, such as MRI and PET. We are currently running the [ERAP](https://classic.clinicaltrials.gov/ct2/show/NCT06022068) phase IIa trial, where we evaluate the effect of the drug sirolimus/rapamycin on human neurodegeneration and aging. Our work also involves creating and assessing biomarkers of aging that can be used as endpoints in clinical trials of geroprotective compounds. To this end, we apply machine learning models to large batches of multi-modal imaging data to estimate the biological age of different organ-systems in the human body.
      
  - block: people
    id: people
    content:
      title:
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Principal Investigator
          - Researchers
          - Research Support
          - Colaborators
          - Alumni
      sort_by: Params.position
      sort_ascending: true
    design:
      show_interests: true
      show_role: true
      show_social: true

  - block: markdown
    id: collaborators
    content:
      title: Key Collaborators
      text: |
        - [Pete A. Williams](https://ki.se/en/people/pete-williams ), research group leader at KI/St Eriks Eye Hospital. <br>
        - [Mikael Palner](https://portal.findresearcher.sdu.dk/da/persons/mpalner), small-animal PET imaging research group leader at the University of Southern Denmark. <br>
        - [Todd Ogden](https://www.publichealth.columbia.edu/profile/r-todd-ogden-phd), vice chair of Columbia University Department of Biostatistics, NYC, USA. <br>

Link: 
    
  - block: collection
    id: publications
    view: citation
    content:
      title: Publications 
      subtitle: ''
      text:
      filters:
        tags: publication
  
---
