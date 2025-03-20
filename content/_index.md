---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    id: about 
    content:
      title: |
        # Evaluating geroprotective interventions using *in vivo* medical imaging 
      image:
        filename: brain.png
      text: |
        <span style="font-size:0.9em;">  We aim to develop biomarkers and new treatments for neurodegenerative diseases. We do this by applying medical imaging techniques, such as MRI, PET and CT, to pre-clinical models of neurodegeneration, as well as human patients. Currently, we are running an academically sponsored phase IIa trial in early Alzheimer's disease, where we assess the effect of the drug sirolimus (a.k.a. rapamycin) on neurodegeneration, brain metabolism and aging processes. </span> <br>
        
        <span style="font-size:0.9em;">Our work also involves developing and validating biomarkers of aging that can be used as endpoints in clinical trials of geroprotective compounds. To this end, we apply machine learning models to large batches of multi-modal imaging data to estimate the biological age of different organ-systems in the human body.</span>

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
    id: erap
    content:
      title: ERAP
      text: |
        <br>
        "Evaluating Rapamycin in Alzheimer's disease using Positron emission tomography" (or ERAP for short) is a clinical phase IIa pilot trial. In this one-arm, open-label trial, we assess if the drug rapamycin/sirolimus can be repurposed as a treatment for dementia disorders and neurodegeneration. <br>
        <br>
        The trial is a collaboration between Karolinska Institutet and the Karolinska Hospital Memory Clinic in Solna, Sweden. It was initiated on September 1, 2023, and patients with early-stage Alzheimer's disease or mild cognitive impairment are currently being enrolled by invitation. Participants are treated for six months with a weekly dose of 7 mg sirolimus. Before and at the end of the treatment, all participants undergo a series of examinations where we quantify the change in cerebral glucose metabolism, cerebral blood flow, disease-markers in the CSF and cognition. <br>
        <br>
        In addition, all participants are examined with a set of medical imaging techniques to quatify change in heart function, bone and muscle density, retinal nerve layer thickness, as well as atherosclerotic- and periodontal inflammation. The purpose of these examinations is to assess if rapamycin affects age-related pathological processes in organs and tissues also outside the central nervous system.  <br>  
        <br>  
        clinicaltrials.gov ID: NCT06022068 <br>

  - block: collection
    id: publications
    view: citation
    content:
      title: Selected publications 
      subtitle: ''
      text:
      filters:
        tags: publication
    sort_by: date
    sort_ascending: false
      
  
---
