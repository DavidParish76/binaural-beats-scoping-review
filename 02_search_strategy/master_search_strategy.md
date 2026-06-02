# Master Search Strategy

## Databases

- PubMed/MEDLINE
- - Embase
  - - PsycINFO
    - - Scopus or Web of Science
      - - Cochrane Library
        - - IEEE Xplore (for engineering/BCI literature)
          - - CINAHL (for rehabilitation/nursing literature)
            - - ClinicalTrials.gov (grey literature)
             
              - ## Core Concept Block
             
              -     "binaural beat*" OR "binaural auditory beat*" OR "binaural acoustic stimulation"
              -     OR "binaural beat stimulation" OR "auditory beat stimulation" OR "brainwave entrainment"
             
              - ## Mechanism Block
             
              -     EEG OR electroencephalography OR MEG OR "auditory steady state response" OR ASSR
              -     OR "frequency following response" OR FFR OR entrainment OR oscillation*
              -     OR synchronization OR "neural synchrony"
             
              - ## Outcome Block
             
              -     cognition OR attention OR memory OR anxiety OR mood OR pain OR sleep
              -     OR "motor learning" OR "motor control" OR "motor performance" OR "reaction time"
              -     OR Parkinson* OR stroke OR rehabilitation OR tremor OR autonomic
              -     OR "heart rate variability" OR HRV OR "auditory motor" OR sonification
             
              - ## Combined Search Draft
             
              -     (
              -       "binaural beat*" OR "binaural auditory beat*" OR "binaural acoustic stimulation"
              -         OR "binaural beat stimulation" OR "auditory beat stimulation" OR "brainwave entrainment"
              -         )
              -         AND
              -         (
              -           EEG OR electroencephalography OR MEG OR "auditory steady state response" OR ASSR
              -             OR "frequency following response" OR FFR OR entrainment OR oscillation*
              -               OR synchronization OR cognition OR attention OR memory OR anxiety OR mood OR pain
              -                 OR sleep OR "motor learning" OR "motor control" OR "motor performance"
              -                   OR Parkinson* OR stroke OR rehabilitation OR autonomic OR "heart rate variability"
              -                   )
             
              -               ## Filter: Humans Only
             
              -               AND (humans[MeSH] OR "human participants" OR "healthy adults" OR patients)
             
              -           ## Notes
             
              -       - No date restriction.
              -   - English language primary.
                  - - Adapt syntax for each database (see individual database search files in `02_search_strategy/`).
                    - - Gray literature: search ClinicalTrials.gov using key terms from the Core Concept Block.
                      - - Citation chaining: check references of key reviews and forward-cite using Google Scholar.
                       
                        - ## Version History
                       
                        - | Date | Change | Author |
                        - |---|---|---|
                        - | (initial) | First draft | David Parish |
                        - 
