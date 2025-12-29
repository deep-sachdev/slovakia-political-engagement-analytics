## Dataset Overview

This project uses data from the **European Social Survey (ESS)**, a large-scale, publicly available social science dataset collected across European countries.

- **Source:** European Social Survey (ESS)
- **Survey wave:** ESS Round 10
- **Total records (after country filter):** 33,351 respondents
- **Country focus:** Slovakia
- **Data type:** Survey responses (demographic, socioeconomic, political behaviour)

## Data Access & Size Handling

The raw ESS dataset exceeds GitHub file size limits and is therefore **not stored in this repository**.

All analysis was performed on a **Slovakia-filtered subset** of the ESS data (33,351 records), derived from the official ESS release.

The dataset is publicly available and can be accessed here:
- https://www.europeansocialsurvey.org/data/

## Key Variables Used

The analysis focuses on variables related to online political engagement and demographics, including:

- Online political posting behaviour
- Age
- Education level
- Income and financial difficulty
- Gender
- Employment status
- Region (Slovakia)

Variable definitions, coding schemes, and survey methodology are documented in the official ESS codebook:
- https://www.europeansocialsurvey.org/data/documentation.html

## Reproducibility Note

This repository focuses on **analytical logic, visualisation, and insight generation** rather than data hosting.

Anyone with access to the ESS dataset can reproduce the analysis by:
1. Downloading ESS Round 10 data
2. Filtering for Slovakia
3. Applying the transformations described in the analysis workflow

