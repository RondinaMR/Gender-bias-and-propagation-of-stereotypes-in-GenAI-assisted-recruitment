# Gender bias and propagation of stereotypes in GenAI-assisted recruitment
Supplementary material for the paper "Gender bias and propagation of stereotypes in GenAI-assisted recruitment"

## Dataset description

This repository contains the spreadsheets supporting the empirical analysis presented in the paper “Extended Gender Bias in Generative AI-Assisted Recruitment Processes”.
The files document the full analytical pipeline of the study, including raw model outputs, qualitative coding, descriptive statistics, and inferential analyses, ensuring transparency and replicability.

The dataset is organised around the two experimental phases described in the paper.

### Candidate-driven experiment

This part of the dataset reports the results of the interaction between the generative AI model and 24 synthetic job-seeker profiles (12 female and 12 male), each prompted three times (72 observations).

- Table 1
Raw dataset containing all model outputs for the candidate-driven experiment. Variables include candidate gender, age, professional macro-area, seniority level, suggested job title and generated descriptive adjectives.
- Analysis table 1
Intermediate analysis sheet used for open coding and categorisation. Job titles and adjectives are normalised and grouped into homogeneous semantic and occupational classes. Frequency counts by gender are reported.
- Results table 1
Statistical analysis supporting RQ1.1 and RQ1.2, including observed and expected frequencies and χ² tests of independence assessing the impact of gender on job suggestions and descriptive adjectives.
- Descriptive table 1
Description overview of the variables, categories and elements included in the main Table 1.

### Job-driven experiment

This part of the dataset is based on 114 real job advertisements collected from LinkedIn, used as prompts to generate textual and visual representations of ideal candidates.

- Table 2
Raw dataset containing, for each job advertisement, the job title, seniority level, AI-assigned gender, textual adjectives describing the ideal candidate and visual descriptors (posture, facial expression, clothing style), as well as the manual annotation of smiling presence.
- Analysis and Results table 2 text
Main analytical sheet for the job-driven experiment, reporting frequency tables and χ² tests evaluating the overall gender distribution, the association between gender job titles and adjectives. 
- Normalized Results table 2 text
Normalised percentage distributions used to produce the comparative charts included in the paper for the overall gender distribution, job titles and adjectives.
- Analysis and Results table 2 visual
Main analytical sheet for the job-driven experiment, reporting frequency tables and χ² tests evaluating the association between gender and posture, facial expression, smiling presence and clothing style descriptors.
- Normalized Results table 2 visual
Normalised percentage distributions used to produce the comparative charts included in the paper for posture, facial expression, smiling presence and clothing style descriptors.
- Descriptive table 2
Descriptive distributions of AI-assigned gender and associated textual and visual traits.
