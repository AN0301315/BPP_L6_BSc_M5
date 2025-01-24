#### My Bio
![Stickperson Me](/docs/assets/images/Stickperson.jfif)
This GitHub page has been created for educational purposes only as required by the summative assessment for my studies of ‘Data Science Professional Practice’.
To protect my privacy, I will stay anonymous.

<img src="/docs/assets/images/Stickperson.jfif">

#### Title
Predicting UK GQ education malpractice cases (%) by exam board (multivariate time series analysis), using public data.

##### Introduction
This project explores published UK secondary school education data, and performing a predictive data analysis, extending the data into the future.
The chosen dataset is similar in structure to one I use in my daily work, so besides demonstrating my data science skills, I can integrate my code with small modifications into my reporting to stakeholders, replacing a crude and flawed seven-day sliding window prediction.

##### Dataset
The data used in this project is public data, published by Ofqual. “All content is available under the Open Government Licence v3.0”, which means I can “use and re-use the Information that is available under this license freely and flexibly” (The National Archives, 2019) and include it into my work.
I used the dataset of Summary statistics for GCSE AS and A level (Ofqual Analytics, n.d.), with data of the past seven years, which includes the period of the cancelled or modified summer examinations due to the Covid-19 pandemic. I merged the dataset I collected at the beginning of the project contained the years 2017-2023, with an updated version towards completing the project containing the years 2018-2024, which provided me with the data of eight years.

##### Process
In my day-to-day job, data sourcing and methods/tools/concepts used is driven by the business question. This project is the reverse as the dataset drives what research questions can be answered and what methods are suitable.
![Mind_Map](/docs/assets/images/Brainstorming_DataAnalysis_Techniques.jpg)
Image 1: Mind Map for selecting data analysis method
After evaluating the suitability of various analysis techniques for the dataset using mind mapping (image 1), I selected Time Series Analysis as it is the most relevant option for the dataset.

##### Methods, Techniques, Tools and Technologies
Before downloading the dataset, I read through information and documentation provided with the data by the provider, as well as the data usage policy.
I used Python code, especially the Pandas library, for the Data Quality Audit, and data manipulations, building the supervised machine learning model, and data visualization using libraries Matplotlib and Seaborn. This works well for larger dataset and the procedures are repeatable and easier to maintain, which helped me in rerunning the project after I created a new dataset with Ofqual’s updated version.
I created ETL Diagrams, Data & Process Workflow Illustrations, and Data Dictionaries for highlighting any bottlenecks or data processing challenges and helping to keep the project realization on track.


Read Me under docs
This is a my stick person image
![Stickperson Me](/docs/assets/images/Stickperson.jfif)
#### This is a level 4 header
##### This is a level 5 header
###### This is a level 6 header
Reference
[Ref](https://analytics.ofqual.gov.uk/apps/GCSEandGCE/SummaryStats/)
