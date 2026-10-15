I created a csv file `cleaned_combined_data.csv` in the `data` folder where it hopefully is useful for analysis for all 3 questions. This is a description of the columns.

# Identifier
- response_id: ID of a unique respondent

# Comfort Levels
- prog.comf: Programming comfort
- math.comf: Math comfort
- stat.comf: Statistics comfort

# Areas (of Data Science)
### Coded as TRUE or FALSE depending on whether the respondent marked the area as of interest to them
- image_analysis: Analysis or classification of images
- neural_networks: Deep learning and neural networks
- time_series: Spatial statistics or time series analysis
- data_engineering: Data acquisition and engineering
- text_analysis: Natural language processing and analysis of text
- software_integration: Model deployment and software or web integrations
- data_visualization: Data visualization and interactive dashboards
- predictive_modeling: Predictive modeling, generally
- statistical_modeling: Statistical models and inference, generally
- databases: Databases
- algorithms: Algorithms

# Domains
### Coded as TRUE or FALSE depending on whether the respondent marked the area as of interest to them
### Note: There were 7 unique self-reported domains of interest: AI, Financial Markets, Quantitative Finance, Economics, Defense, Sports/Economics/Finance, Music. 
### All of them had 1 response (except Economics which had 2). Since those groups are too small, I ignore them in that I don't give them their own group.
- envi_sci: Environmental science
- soc_poli_sci: Social or political science
- ecology: Ecology
- biology: Biology
- health: Public health
- neurosci: Neuroscience
- tech: Technology
- software_dev: Software development

# Classes
All classes that had at least 1 response are put in here. They are coded as TRUE/FALSE depending on whether the respondent has taken that class.

# Class Groups
From Lily's work. Counts the number of classes taken from a specific group of classes.
- prereq_core: PSTAT 120, PSTAT 122, PSTAT 126
- intro_ds: PSTAT 100
- programming: CS 5, CS 9, CS 16, CS 130
- adv_stat_ml: PSTAT 115, PSTAT 127, PSTAT 131, PSTAT 134
- time_series_stoch: PSTAT 160, PSTAT 174, PSTAT 175
- other_dept: LING 104, LING 110, GEOG 186
