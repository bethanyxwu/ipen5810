# ipen5810
repository for ipen5810


////////////////////////////////////////////////////////////////////////////////
FILES FOR:
// 
Mini Group Project I - Employee reviews of their employers - IPEN 5810
// 
by Xinyu, WU & Chengyue, LAI
// 
date: 12 Mar 2024
// 
////////////////////////////////////////////////////////////////////////////////


* Project Overview:
  
This project aims to analyze a dataset of employee reviews of employers on Glassdoor, using natural language processing (NLP) and machine learning methods to preprocess text data, classify topics in reviews, and explore the correlation between these topics and income-related indicators. sex.

* Installation guide:

To run the code for this project, you need to install the following Python libraries: numpy; pandas; sklearn; matplotlib; seaborn; nltk; gensim
Missing libraries can be installed using the pip install command.

* How to run the code:
  
1.Clone the repository locally.
2.Make sure all dependencies are installed.
3.Run cells in Jupyter Notebook.

* File structure and description:

ipen5810_mini_project.ipynb: Contains complete code and instructions for data preprocessing, topic classification, visualization and correlation analysis.

* Dataset introduction:

The dataset reviews_bsample.csv contains employee reviews of their employers collected from the Glassdoor website. The dataset is used to train an NLP model to identify and classify topics in reviews.

* Methodology:

The following methods were used in this project:
1.Text preprocessing: remove punctuation marks, stop words, etc.
2.TF-IDF method: Vectorize text 
3.NMF topic model: for classification.
4.word cloud analysis: Visualize results.
5.Use GPT for zero-shot learning.
6.Use GPT for data augmentation.
7.Cosine Similarity Calculation: measure thematic alignment between review 
8.RandomForestRegressor and text analysis: predict employment length

* Main findings and conclusions:

1.Employees are most concerned about the management and working hours of their workplace;
2.Companies with strong capabilities and development opportunities are more likely to be favored by employees;
3.Salary issues are the source of dissatisfaction among most employees;
4.Most employees want their employer to improve the company's overall strength and development opportunities;
5.Engineers and sales pay more attention to work-life balance (WLB) issues
6.Employees in the United Kingdom are more concerned about WLB issues;
7.Sales, Finance and Engineers are more likely to make extreme comments about their jobs;
8.The topics covered can be leveraged to predict the duration of employment and positively impact compensation rates and work-life balance.






