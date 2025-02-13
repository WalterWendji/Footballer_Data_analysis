This is a **university project** created in **German** by @px2023 and myself. 
In this project, we had to download **FIFA datasets from the Kaggle website** 
and, after analysis, **identify exceptional football players**.
We used the **BayesianGaussianMixture algorithm** to determine the **number of 
meaningful clusters** within the dataset. This algorithm is an advanced form 
of the classical Gaussian Mixture Model and uses **Bayesian methods** to automatically 
determine the number of clusters. Unlike the k-Means algorithm and 
the Gaussian Mixture Model, it allows for additional **statistical 
constraints** on the data, leading to a more reliable number of clusters.
Following this, we created a **correlation matrix** to analyze the **relationships 
between the attributes** within each cluster. The **Pearson correlation coefficient** 
was used to determine the dependence of the attributes. A **correlation matrix** was 
generated for all attributes and each group.
Ultimately, we were able to **identify the names of the most exceptional football 
players in different categories** (strikers, midfielders, defenders, and goalkeepers). 
The best player in each category was defined as the most exceptional player. The data 
was extracted using **Python**, **numpy** and the **Pandas library**. 

- **Data Source**: The data originates from [Kaggle](https://www.kaggle.com/datasets/rehandl23/fifa-24-player-stats-dataset/data).
- **Data Preprocessing**: The data underwent manual checks for inconsistencies, resolution of encoding issues, removal of empty columns, and elimination of duplicates. The last 7 lines of the CSV file required manual correction due to not being UTF-8 encoded.
- **Libraries Used**: The analysis was conducted using Python, numpy and the Pandas library.
- **Jupyter Notebook**: The project was implemented in a Jupyter Notebook, which contains the code snippets.
- **Results**: Lionel Messi was identified as the best striker and midfielder, Virgil van Dijk as the best defender, and Gianluigi Donnarumma as the best goalkeeper.
- **Motivation**: The motivation for this project was to achieve faster, more precise, and more cost-effective results compared to manual research.
- **Outlook**: Future research could involve identifying the best players from each country or predicting which country will win the next World Cup.
