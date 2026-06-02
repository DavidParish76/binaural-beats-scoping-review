# Binaural Beats Scoping Review

## Project Overview

This repository supports a structured scoping review examining binaural auditory beat stimulation (BABS) as a noninvasive neuromodulatory tool. The review maps mechanistic evidence, stimulation parameters, and outcome domains across EEG/MEG, cognition, anxiety, mood, pain, sleep, motor performance, motor learning, rehabilitation, and autonomic regulation. A particular focus is placed on translational relevance for motor-control and rehabilitation research, and on identifying implications for a future Master's thesis involving sonification of a sine-wave visual motor template.

## Working Title

Binaural Auditory Beat Stimulation as a Noninvasive Neuromodulatory Tool: A Scoping Review of Mechanisms, Stimulation Parameters, and Translational Relevance for Motor Control and Rehabilitation

## Review Aim

To systematically map the published evidence on binaural auditory beat stimulation, characterise the range of stimulation parameters and outcome domains studied, assess the level of methodological standardisation, and identify translational implications for motor-control and rehabilitation research.

## Review Question

What stimulation parameters, mechanistic measures, and behavioral or clinical outcomes have been used in human studies of binaural auditory beat stimulation, and what evidence exists for translation into motor-control, autonomic regulation, and rehabilitation research?

See `review_question.md` for full subquestions.

## Subquestions

1. What beat frequencies, carrier frequencies, exposure durations, and delivery methods have been used?
2. 2. What control conditions have been used?
   3. 3. Do studies measure entrainment directly, or do they assume it?
      4. 4. Which neurophysiological measures are used (EEG, MEG, ASSR, FFR, spectral power, connectivity, autonomic markers)?
         5. 5. Which behavioral and clinical outcomes are studied (cognition, anxiety, mood, pain, sleep, motor performance, motor learning, tremor, rehabilitation, HRV)?
            6. 6. Which findings are most relevant to future work on sonification of a sine-wave visual motor template?
              
               7. ## Methodological Framework
              
               8. This review follows the PRISMA for Scoping Reviews (PRISMA-ScR) framework (Tricco et al., 2018) and the Joanna Briggs Institute (JBI) methodology for scoping reviews. Meta-analysis will be considered only if a sufficiently homogeneous evidence cluster emerges; the primary output is a narrative synthesis and evidence map.
              
               9. ## Repository Structure
              
               10. ```
                   binaural-beats-scoping-review/
                   |
                   +-- README.md
                   +-- LICENSE
                   +-- .gitignore
                   +-- project_overview.md
                   +-- review_question.md
                   +-- contribution_guidelines.md
                   |
                   +-- 00_admin/
                   +-- 01_protocol/
                   +-- 02_search_strategy/
                   +-- 03_screening/
                   +-- 04_data_extraction/
                   +-- 05_evidence_mapping/
                   +-- 06_risk_of_bias_or_limitations/
                   +-- 07_manuscript/
                   +-- 08_tables/
                   +-- 09_figures/
                   +-- 10_thesis_integration/
                   +-- 11_notes/
                   +-- 12_archive/
                   +-- data_dictionary/
                   ```

                   See directory-level README files or the file tree for full structure.

                   ## Current Project Status

                   Phase 1: Project Lock-In (June 1 – June 15, 2026)

                   - Protocol development in progress
                   - - Review question and eligibility criteria drafted
                     - - Search strategy under development
                      
                       - ## Target Completion Date
                      
                       - **August 26, 2026**
                      
                       - ## Key Outputs
                      
                       - 1. Scoping review manuscript draft
                         2. 2. Search strategy documentation
                            3. 3. Screening logs and PRISMA flow diagram
                               4. 4. Master extraction table
                                  5. 5. Evidence map (stimulation parameters x outcome domains)
                                     6. 6. Stimulation parameter table
                                        7. 7. Mechanistic evidence table
                                           8. 8. Motor-control relevance table
                                              9. 9. Thesis integration memo
                                                 10. 10. Advisor-ready project memo
                                                    
                                                     11. ## Rules for File Naming
                                                    
                                                     12. - Use `snake_case` for all files and folders.
                                                         - - Use ISO date format for dated files: `YYYY-MM-DD_description.md`
                                                           -   - Example: `2026-06-05_advisor_memo.md`
                                                               - - Article notes use the pattern: `author_shorttitle_year.md`
                                                                 -   - Example: `ingendoh_binaural_beats_entrain_brain_2023.md`
                                                                  
                                                                     - See `data_dictionary/file_naming_conventions.md` for full rules.
                                                                  
                                                                     - ## Notes on Thesis Integration
                                                                  
                                                                     - This scoping review is the empirical foundation for a future Master's thesis examining whether sonification of a sine-wave visual motor template can function as an auditory-motor coupling intervention. The review informs the thesis by:
                                                                  
                                                                     - - Identifying effective stimulation parameters for motor-relevant outcomes
                                                                       - - Distinguishing binaural beat neuromodulation from sonification as a data-to-sound mapping strategy
                                                                         - - Characterising existing evidence on auditory-motor coupling, motor learning, and motor performance
                                                                           - - Identifying gaps in the literature that the thesis can address
                                                                            
                                                                             - See `10_thesis_integration/` for all thesis bridge documents.
                                                                            
                                                                             - ## Note on Manuscript Reuse
                                                                            
                                                                             - Manuscript text in `07_manuscript/` is original unpublished academic writing. It should not be reproduced or reused without attribution to the author.
                                                                            
                                                                             - ## License
                                                                            
                                                                             - Code and scripts: MIT License (see `LICENSE`).
                                                                             - Manuscript text: All rights reserved by the author unless otherwise stated.
                                                                             - 
