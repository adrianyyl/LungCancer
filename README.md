# LungCancerPrediction
Welcome to the **LungCancer** repository. This project was developed as part of the DSA312 module, with the aim to visualise and communicate key insights from the lung cancer survey.csv dataset, as well as develop a lung cancer prediction model. By analysing key characteristics and common symptoms of lung cancer, our prediction model provides users with information on their lung cancer risk levels.

## Contributors
* Abdullah Khurshid
* Adrian Yip
* Mattia Boellenruecher
* Muhammad Kareem
* Syed Muhammad Firas

## Technologies and Requirements
**Programming Langugage:** Python 3.12+

**Required Libraries:** pandas, numpy, matplotlib, sklearn, scipy.stats, plotly, tensorflow, statsmodels, among others

**Data:** Our project uses data originally retrieved from Kaggle, which was in turn retrieved from an online website on lung cancer prediction system. The dataset can be found in the following Kaggle link: [Lung Cancer Survey](https://www.kaggle.com/datasets/wajahat1064/lung-cancer-survey-data).

The data was then passed through a series of training models and a synthetic dataset of 10,000 observations was generated. This dataset is randomly divided into 2: lung cancer survey (9,000 observations) and lung cancer survey_test.csv (1,000 observations).

We also used datasets from [World Health Organisation (WHO)](https://gco.iarc.fr/tomorrow/en/dataviz/tables?populations=702&single_unit=1000&cancers=15&years=2035&types=0&key=total&show_bar_mode_prop=0&bar_mode=grouped&multiple_populations=1&sexes=0) and [Singapore Cancer Registry Annual Report 2022](https://www.nrdo.gov.sg/docs/librariesprovider3/default-document-library/scr-ar-2022_web-report.pdf?sfvrsn=a9eb8c10_1) to generate visualisations and support our findings.

## Project Workflow
Our project is structured into a series of Jupyter notebooks, each covering a specific phase of the lung cancer prediction model development process.

**1. Data Cleaning**

In this initial phase, we prepare our datasets for analysis by handling missing values, outliers, and any inconsistencies. This ensures the integrity and quality of our data, setting a strong foundation for the subsequent steps.

**2. Trend Visualisation**

In this phase, we generated figures (eg. bar charts, pie charts, etc.) to visualise the trends regarding lung cancer in Singapore. This phase results in the creation of simple and impactful diagrams for the general public to understand lung cancer trends and risks.

**3. Model Development**

This step involves developing our prediction model using machine learning algorithms.
   
