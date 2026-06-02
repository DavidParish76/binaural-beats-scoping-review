# Extraction Codebook

This codebook defines all variables for data extraction. For each included study, complete one row in `master_extraction_table.csv`.

## Citation Variables

- **study_id**: Auto-generated sequential identifier (e.g., BABS_001)
- - **author**: First author last name
  - - **year**: Publication year (integer)
    - - **title**: Full study title
      - - **journal**: Journal name
        - - **doi**: DOI string
          - - **citekey**: Reference manager citekey (e.g., ingendoh2019)
           
            - ## Study Design Variables
           
            - - **study_design**: RCT, crossover, quasi-experimental, within-subject, observational, case report
              - - **randomization**: Yes / No / Not reported
                - - **blinding**: Double-blind, single-blind, unblinded, not reported
                  - - **control_condition**: Description of control (e.g., sham, silence, pure tone, white noise, different frequency)
                    - - **within_subject_or_between_subject**: Within / Between / Mixed
                      - - **sample_size_total**: Total enrolled (integer)
                        - - **sample_size_per_group**: Per group (string if multiple groups)
                         
                          - ## Population Variables
                         
                          - - **population_type**: Healthy adults, healthy older adults, healthy children, clinical (specify), mixed
                            - - **diagnosis**: Clinical diagnosis if applicable
                              - - **age_mean**: Mean age (float)
                                - - **age_range**: Age range string
                                  - - **sex_distribution**: String (e.g., 60% female, 20F/20M)
                                    - - **inclusion_criteria**: Brief description
                                      - - **exclusion_criteria**: Brief description
                                       
                                        - ## Stimulation Variables
                                       
                                        - - **auditory_stimulation_type**: Binaural beats, binaural acoustic stimulation, brainwave entrainment, other
                                          - - **binaural_or_monaural**: Binaural / Monaural / Not specified
                                            - - **beat_frequency_hz**: Beat frequency in Hz (float)
                                              - - **frequency_band**: delta (0.5-4Hz), theta (4-8Hz), alpha (8-13Hz), beta (13-30Hz), gamma (>30Hz), not reported
                                                - - **left_carrier_frequency_hz**: Left ear carrier frequency (float)
                                                  - - **right_carrier_frequency_hz**: Right ear carrier frequency (float)
                                                    - - **carrier_frequency_notes**: Additional notes on carrier frequencies
                                                      - - **stimulation_duration_minutes**: Duration per session in minutes (float)
                                                        - - **number_of_sessions**: Total sessions (integer)
                                                          - - **sound_intensity_db**: Intensity in dB SPL (float)
                                                            - - **headphones_or_speakers**: Over-ear headphones, in-ear headphones, speakers, not reported
                                                              - - **masking_noise_used**: Yes (specify type) / No / Not reported
                                                                - - **exposure_timing**: Before task, during task, both, not reported
                                                                 
                                                                  - ## Mechanistic Variables
                                                                 
                                                                  - - **mechanism_measured_yes_no**: Yes / No
                                                                    - - **eeg_used**: Yes / No
                                                                      - - **meg_used**: Yes / No
                                                                        - - **assr_measured**: Yes / No
                                                                          - - **ffr_measured**: Yes / No
                                                                            - - **spectral_power_measured**: Yes / No
                                                                              - - **connectivity_measured**: Yes / No
                                                                                - - **entrainment_definition**: How the study defines entrainment (string)
                                                                                  - - **entrainment_assumed_or_measured**: Assumed / Measured / Both / N/A
                                                                                   
                                                                                    - ## Outcome Variables
                                                                                   
                                                                                    - - **primary_outcome_domain**: EEG, cognition, affect, pain, sleep, motor, autonomic, other
                                                                                      - - **secondary_outcome_domains**: Pipe-separated list
                                                                                        - - **cognitive_outcomes**: Specific measures (string)
                                                                                          - - **affective_outcomes**: Specific measures (string)
                                                                                            - - **pain_outcomes**: Specific measures (string)
                                                                                              - - **sleep_outcomes**: Specific measures (string)
                                                                                                - - **motor_outcomes**: Specific measures (string)
                                                                                                  - - **autonomic_outcomes**: Specific measures (string)
                                                                                                    - - **clinical_outcomes**: Specific measures (string)
                                                                                                     
                                                                                                      - ## Results Variables
                                                                                                     
                                                                                                      - - **main_result_direction**: Positive (BABS superior), Negative (BABS inferior), Null (no difference), Mixed
                                                                                                        - - **statistically_significant**: Yes / No / Mixed / Not reported
                                                                                                          - - **effect_size_reported**: Yes / No
                                                                                                            - - **effect_size_value**: Value and metric (string)
                                                                                                              - - **confidence_interval**: CI string
                                                                                                                - - **p_value**: p-value string
                                                                                                                  - - **author_conclusion**: Brief summary of authors' conclusion (string)
                                                                                                                    - - **reviewer_interpretation**: Reviewer's interpretation and caveats (string)
                                                                                                                     
                                                                                                                      - ## Methodological Limitation Variables
                                                                                                                     
                                                                                                                      - - **risk_of_bias_notes**: General bias notes
                                                                                                                        - - **sample_size_limitation**: Yes / No / Notes
                                                                                                                          - - **control_condition_limitation**: Yes / No / Notes
                                                                                                                            - - **blinding_limitation**: Yes / No / Notes
                                                                                                                              - - **outcome_measure_limitation**: Yes / No / Notes
                                                                                                                                - - **protocol_reporting_limitation**: Yes / No / Notes
                                                                                                                                  - - **adverse_events_reported**: Yes / No / Not mentioned
                                                                                                                                   
                                                                                                                                    - ## Thesis Relevance Variables
                                                                                                                                   
                                                                                                                                    - - **thesis_relevance_score**: 0-3 (see `thesis_relevance_scale.md`)
                                                                                                                                      - - **relevance_to_sonification**: Yes / No / Partial (notes)
                                                                                                                                        - - **relevance_to_sine_wave_template**: Yes / No / Partial (notes)
                                                                                                                                          - - **relevance_to_motor_control**: Yes / No / Partial (notes)
                                                                                                                                            - - **relevance_to_autonomic_regulation**: Yes / No / Partial (notes)
                                                                                                                                              - - **future_study_design_notes**: Notes on how this study informs thesis design
                                                                                                                                                - 
