# Analysis Plan

For each question, try and record:
1. Variables, files, respondents
2. Data preparation
3. Summaries, plots, models to try and what their output would tell you
4. Key choices to check
5. One limitation


Is there a relation between people's domains of interest (like biology, technology, AI, etc.) and the areas of data science that they prefer?
Motivation: Each domain utilizes a different subset of data science skills. It is possible that there is a relation there.
- IV: domains of interest (Environmental science, Social or political science, Ecology, Biology, Public health, Neuroscience, Technology, Software development, Other:)
- DV: preferred areas of data science (Analysis or classification of images, Deep learning and neural networks, Spatial statistics or time series analysis, Data acquisition and engineering, Natural language processing and analysis of text, Model deployment and software or web integrations, Data visualization and interactive dashboards, Predictive modeling, generally, Statistical models and inference, generally, Databases, Algorithms, Other:)
- files: interest-clean.csv
- data preparation: 
    - convert responses into binary (1=selected, 0=not selected) since multiple domains and areas can be chosen
    - what should we do with ppl who chose "Other" for both questions?
- summaries, plots, models:
    - frequency tables
    - heatmap
    - X^2-test


Is there a relation between the classes people have taken and their preference for certain areas of data science?
- IV: classes taken
- DV: preferred areas of data science (Analysis or classification of images, Deep learning and neural networks, Spatial statistics or time series analysis, Data acquisition and engineering, Natural language processing and analysis of text, Model deployment and software or web integrations, Data visualization and interactive dashboards, Predictive modeling, generally, Statistical models and inference, generally, Databases, Algorithms, Other:)
- files: background-clean.csv for classes taken; interest-clean.csv for ds areas
- data preparation:
    - convert responses into binary (1=selected, 0=not selected) since multiple domains and areas can be chosen
    - group classes into subject categories and have a pre-req category too
    - what should we do with ppl who chose "Other" for ds areas questions?
- summaries, plots, models:
    - frequency tables
    - heatmap
    - X^2-test
    
    
Is there a relation between the classes people have taken and their comfort level with math/stats/programming?
- IV: classes taken
- DV: self-reported comfort level w math/stats/programming (scale of 1-5)
- data preparation:
    - group classes into subject categories and have a pre-req category too
- summaries, plots, models:
    - descriptive statistics of comfort scores
    - correlation heatmap
