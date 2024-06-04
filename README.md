# Associations Between Cognitive Appraisals and Emotions: A Meta-Analytic Review


This repository contains code and data to accompany the following paper:

Yeo, G. C., & Ong, D. C. (to appear). Associations Between Cognitive Appraisals and Emotions: A Meta-Analytic Review. <i>Psychological Bulletin</i>.

This GitHub repository can be found at: [https://github.com/desmond-ong/appraisal-meta-analysis](https://github.com/desmond-ong/appraisal-meta-analysis), and a persistent OSF mirror can be found here [https://osf.io/kr896](https://osf.io/kr896). A preprint can be found here: [https://osf.io/ystxc/](https://osf.io/ystxc/)


There are 2 analysis files in this repository. 

The first is an interactive R Shiny applet that allows users to interactively search for results for specific appraisal-emotion relationships, as well as to query the references of the studies that the effect sizes were extracted from. The code to run the R Shiny file (locally, if you wish), is in `meta-analysis-code.Rmd`, and a live version of the app is available at: [https://desmond-ong.shinyapps.io/meta-analysis-code/](https://desmond-ong.shinyapps.io/meta-analysis-code/)

The second, `meta-analysis-tables-figures.rmd`, contains code to reproduce all the Figures and Tables in the paper. A rendered version of this can be found at [https://desmond-ong.github.io/appraisal-meta-analysis/meta-analysis-tables-figures.html](https://desmond-ong.github.io/appraisal-meta-analysis/meta-analysis-tables-figures.html)


The main data files are:

- `meta-analysis_data.csv` : file containing all the studies and information coded from studies (e.g., study, emotion, appraisal, effect size)
- `prisma_all_articles.xlsx` : Excel file containing all the names of the articles at each step in our article screening process. See Prisma diagram (Fig 1 of paper) for numbers, and main text for exclusion criteria
- `predicted_relationships.csv` : file containing whether a particular appraisal-emotion relationship is "Predicted". (Note that the `ref` column is not filled in. Please see Supplemental Materials Table S7 for references.)


This repository is maintained by Desmond Ong. 

