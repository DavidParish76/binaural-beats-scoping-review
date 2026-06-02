# Contribution Guidelines

## Overview

This repository is primarily maintained by a single researcher (David Parish, Boyle Lab). These guidelines apply to any collaborators, research assistants, or reviewers who contribute to the project.

## File Naming

- Use `snake_case` for all files and folders.
- - Date-stamped files use ISO format: `YYYY-MM-DD_description.md`
  - - Article notes use: `author_shorttitle_year.md`
    - - See `data_dictionary/file_naming_conventions.md` for full rules.
     
      - ## Commit Messages
     
      - Use meaningful commit messages with a category prefix:
     
      - - `init:` for initial setup
        - - `docs:` for documentation changes
          - - `data:` for data or log file updates
            - - `draft:` for manuscript drafts
              - - `tables:` for table files
                - - `fix:` for corrections
                  - - `protocol:` for protocol changes
                   
                    - Example: `docs: add eligibility criteria to 01_protocol`
                   
                    - ## Protocol Changes
                   
                    - All changes to inclusion/exclusion criteria, extraction schema, or evidence domain tags must be:
                   
                    - 1. Logged as a GitHub Issue before implementation.
                      2. 2. Reviewed and discussed before merging.
                         3. 3. Recorded in `00_admin/decisions_log.md` after implementation.
                           
                            4. ## What to Commit
                           
                            5. **Do commit:**
                            6. - Markdown files (.md)
                               - - CSV files for screening logs, extraction, and evidence maps
                                 - - Python and R scripts in `src/`
                                   - - Summary table outputs
                                    
                                     - **Do not commit:**
                                     - - PDF full texts
                                       - - .docx files
                                         - - .ris, .nbib, .enw reference exports (store in gitignored `/zotero_exports/`)
                                           - - .xlsx files
                                             - - Large binary files
                                              
                                               - ## Screening and Extraction
                                              
                                               - - Screening decisions must be made independently before comparison.
                                                 - - Conflicts must be documented in `03_screening/exclusion_reasons.md`.
                                                   - - Extraction decisions must be logged in `04_data_extraction/extraction_decisions_log.md`.
                                                    
                                                     - ## Questions
                                                    
                                                     - Contact David Parish or open a GitHub Issue.
                                                     - 
