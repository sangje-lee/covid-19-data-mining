# The Covid-19 Open Research Dataset Data Mining


## Notice

The code is slightly updated. Previous code are located here, https://github.com/sangje-lee/covid-19-data-mining-old

---

## Overview

The dataset, “The Covid-19 Open Research Dataset” contains all the research papers that are related to COVID-19 mostly in 2020 to 2022 with some of research paper dated before 2022. The (final) dataset itselfis roughly 18GB, consist of four of the columns, “cord_uid”, unique identifier, “title”, “published_time”, and “abstract”. The problem primarily will involve the ‘title’ column, to find keywords primarily focus on "Patient", "Disease", “Vaccine”, and "Infect". For this analysis, the modified dataset which only the resarch papers dated between 2020 to 2022 is being used.

- **Goal:** To find any keywords inside the dataset that contains title of the research paper. The search of keyword involved primarily on 'title' columns.

- **Method:** Classification, Assocation Rules, Time Series, Decision Tree/Random Forest/Emsemble-Begging, and Text/Data mining

- **Tools:** Ananconda (Conda) Virtual Environment with Python version 3.9.12, Numpy, Pandas, mlxtend, matplotlib, seaborn, sklearn, NLTK

---

## Project Structure

**Python (Jupiter Notebook) Script**

- Jupiter_Notebook_Final_Initial_Code_Part_01.ipynb ==> Related to text mining (Part 1)
- Jupiter_Notebook_Final_Initial_Code_Part_02.ipynb ==> Related to classification. (Part 2)
- Jupiter_Notebook_Final_Initial_Code_Part_03.ipynb ==> Related to modifying the dataset and bagging/ensemble model. (Part 3)

- "Html" file available (Github/Drive) as well as "pdf" file (Google Drive)
- Dataset_Without_Abstract.txt ==>  Dataset (modified dataset) used for this project

---

## Project Dataset

Link of the modified dataset that will be used during this analysis. Unable to put inside Github because of the dataset size<br />
 https://drive.google.com/file/d/1NNlfCUdVFTk1ADTSio2Th2Bh42rvrLZc/view?usp=drive_link <br />

Alternative (Google Drive), https://drive.google.com/drive/folders/1vxsa1mW9UbiiEtPavJDZQinDGFNIvZo2?usp=drive_link <br />
-> Contain all the datasets including the original dataset, alternative dataset with abstract columns, and script that modify original dataset into modified dataset to fit for this project.<br />

---

## Research Questions

-	What are the main keywords aside from the dataset and the grammar structures appear in the title column?  (Part 1)
-	How frequent do the main keywords appear in the title column? (Part 2)
-	What are the keyword patterns associated with the initial keyword? (Ex. Vaccine → Test) (Part 3)
-	What does the probability of the keyword ‘infect’ appearing inside the title column aside from the other keywords and duration? (Part 4)


---

## Getting started

### 1. The repository

- Clone/Download the respository
- Run the code on the Python (particularly conda/anaconda virutal environment) 3.9.12.
- There may be warning pop up from the vs code or the jupiter notebook.
- Upgrade to newer Python version may pop up new error and may not run correctly.

### 2. Dependencies

**Package Includes**<br />

- matplotlib
- nltk
- numpy
- pandas
- scikit-learn
- seaborn
- sklearn

---

## Alternative Dataset storage

Alternative (Google Drive), https://drive.google.com/drive/u/1/folders/1fNlXaACqC11my3Tswibd8S_Sh1fChSgL <br />
-> Contain all the datasets including the original dataset, alternative dataset with abstract columns, and script that modify original dataset into modified dataset to fit for this project.
<br /><br />
**Python (Jupiter Notebook) Script (Inside Google Drive)**

- Jupiter_Notebook_Final_Initial_Code_Part_00a_Modify_Dataset.ipynb ==> Modified from original dataset to dataset that will be analysis for this project.
- Jupiter_Notebook_Final_Initial_Code_Part_00b_Initial_stage.ipynb ==> Related to my initial analysis.

**Miscellious Files**

- Output_order_fdist.csv (Inside Google Drive) ==>  List of the words that are extracted from ‘title’ column with frequency.
- Output_By_Data_Mining "Folder" ==> List of the words that are extracted based on the categories.<br />
-> Output_order_fdist_by_2020.csv ==> Words extracted based on year of 2020 <br />
-> Output_order_fdist_by_2021.csv ==> Words extracted based on year of 2021 <br />
-> Output_order_fdist_by_2022.csv ==> Words extracted based on year of 2022 <br />
-> Output_order_fdist_lockdown.csv ==> Words extracted based on keyword ‘lockdown’ <br />
-> Output_order_fdist_test.csv ==> Words extracted based on keyword ‘test’ <br />
-> Output_order_fdist_vaccine.csv ==> Words extracted based on keyword ‘vaccine’ <br />
-> Output_order-fdist_vaccine_lockdown.csv ==> Words extracted based on keyword pattern ‘vaccine -> lockdown’ <br />
-> Output_order_fdist_vaccine_test.csv ==> Words extracted based on keyword pattern ‘vaccine -> test’ <br />
-> Output_order_fdist_worker.csv ==> Words extracted based on keyword ‘worker’<br />

---

## Author

Sangjin (Eric S) Lee

---
