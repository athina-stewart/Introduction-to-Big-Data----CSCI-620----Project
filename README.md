# CSCI620 - Introduction to Big Data
## Project Repository, Spring 2023

### Authors/Collaborators:

Athina Stewart<br>
Archit Joshi<br>
Chengzi Cao<br>
Parijat Kawale

### Overview
This repository comprises JS, Python, and SQL scripts designed for loading and analyzing the MyAnimeList dataset from Kaggle as part of the CSCI620 Course project. The project involves data loading, analysis, and comparisons between PostgreSQL and MongoDB.

Dataset: [MyAnimeList Dataset](https://www.kaggle.com/datasets/azathoth42/myanimelist)

## Project Phases:
The project is divided into three phases. Refer to each Phase report for detailed information. Each subsequent phase assumes the previous one has been executed, and the data is available in both PostgreSQL and MongoDB. For an overview of the project lifecycle, consult the "CSCI620 - Project Presentation."

### Phase 1
This phase focuses on selecting a viable dataset for analysis using a relational model. Refer to [CSCI620 - Report Phase 1.pdf](https://github.com/athina-stewart/Introduction-to-Big-Data----CSCI-620----Project/blob/main/CSCI620%20Project%20Report%20Phase%201.pdf) for detailed information and script execution instructions.

#### Objectives:
* Select one or more datasets, ensuring the final dataset is large (~50M tuples in a relational database) and interesting for meaningful queries and information mining.
* Provide a description of the data and a meaningful relational model to accurately represent the dataset.
* Develop a program to load the dataset.

### Phase 2
This phase involves proposing and loading the dataset using a document-oriented model. Refer to [CSCI620 - Report Phase 2.pdf](https://github.com/athina-stewart/Introduction-to-Big-Data----CSCI-620----Project/blob/main/CSCI620%20Project%20Report%20Phase%202.pdf) for detailed information and script execution instructions.

#### Objectives:
* Propose a document-oriented model for the dataset and compare it with the relational model.
* Provide code to load data into this model.
* Offer a program that issues at least five interesting SQL queries over the previous relational model and propose indexes to speed up query execution.
* Discover and explain functional dependencies and discuss normalization regarding the relational model provided in Phase I.

### Phase 3
This phase deals with data cleaning, integration, and item set mining. Refer to [CSCI620 - Report Phase 3.pdf](https://github.com/athina-stewart/Introduction-to-Big-Data----CSCI-620----Project/blob/main/CSCI620%20Project%20Report%20Phase%203.pdf) for detailed information and script execution instructions.

### Objectives:
* Provide a program for cleaning and integrating the dataset.
* Generate and discuss statistical observations from the dataset.
* Develop a program applying the Apriori algorithm for itemset mining to discover association rules.
* Conduct a comparison study on the better model fit for the dataset and the tasks performed on it.
