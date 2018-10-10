# Web-Scraping-and-NLP-on-Indeed-Job-Postings

### Motivation

The motivation of this project is based on the observation that Data science roles and responsibilities are diverse and skills required for them vary considerably. However, the job titles not necessarily represent the actual job duties and requirements. For example, a company, who wants to hire a professional in data analyst, ends up posting a job looking for data scientists. This also leads job seekers fail to identify some best matched jobs if they don't look into the details. Here, I trained unsupervised learning models of K-Means Clustering and LDA to identify latent job duties and skill requirements of each posting for clustering and calculated similarity 

### Overview

In this project, I built a web scraper, which used BeautifulSoup to parse data science related job listings in multiple cities across the US. This scraper pulled 2,000 postings for jobs per location. The detailed job descriptions were also collected for the Natural language Processing using TF-IDF, and were clustered into 3 groups based on latent semantic structures.   

### Keypoints
•	Preprocessed the text by tokenizing, stemming and stop-words removing, and extracted features by term frequency-inverse document frequency approach

•	Trained unsupervised learning models of K-Means Clustering and LDA to identify latent job duties and skill requirements of each posting for clustering and calculated similarity 

•	Visualized model training results by dimensionality reduction using PCA

•	The web scraper and all models were built with Python (BeautifulSoup, Scikit-Learn, NLTK, Pandas). 
