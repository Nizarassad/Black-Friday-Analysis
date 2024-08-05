# Black Friday Data Analysis and Prediction

- The Friday following Thanksgiving, known as "Black Friday," marks the beginning of the holiday shopping season in the US. On this day, many retailers offer significant discounts, attracting a large number of shoppers. This project analyzes customer purchase data from Black Friday to understand preferences for specific products and predict future purchases. 
- The study involves data exploration, pre-processing, and the development of a prediction model using a random forest algorithm. We compare our model's accuracy with other models that used the same dataset.

<div align="center">
  <img height="350" src="https://drive.google.com/file/d/1B-55DfbdmtC1FamjcJrQJIPhSJ1VVpQR/view?usp=sharing" alt="data process" width="500"  />
</div>


## Keywords

Black Friday, machine learning, random forest, visual analytics, deep learning

## Aim and goals

The aim of this study is to investigate collective consumption patterns on Black Friday, a major shopping day in many countries. As businesses grow into large franchises, understanding customer preferences becomes challenging. Prediction models are necessary to better understand these preferences. This research goals to answer the following questions:

- What is the relationship between factors affecting customer purchases?
- Which factors are most influential in purchases?
- Can we create a reliable prediction model for customer purchases?

## Dataset

The dataset used in this project is provided by "ABC Private Limited" and contains purchase summaries of customers for selected high-volume products over a month.
- https://www.researchgate.net/figure/The-Black-Friday-data-made-available-by-ABC-Private-Limited_tbl1_333506727

## Analysis

### Analysis Approach

Quantitative data was used for exploratory analysis. Tools like Python, pandas, matplotlib, numpy, seaborn, and Jupyter Notebooks facilitated the analysis. Visual methods highlighted key features of the dataset, including factors like gender, marital status, occupation, and city category.

### Analysis Process

Data exploration began with a health check and visualizations, such as histograms and box plots, to assess data quality and distribution. The analysis revealed interesting patterns, such as the dominance of male buyers and the influence of occupation on purchasing capacity. The most active buyers were identified as being between 26 and 35 years old.

### Analysis Result

A Random Forest Regressor was used for prediction, achieving an accuracy of 95% on the training dataset and 69% on the testing dataset. The analysis showed that city category and occupation were the most significant factors influencing purchase amounts.

## Critical Reflection

The study revealed that customer behavior is complex and difficult to predict. Despite achieving reasonable accuracy, human buying habits remain unpredictable. Further research could involve using more data and refining the prediction models to improve accuracy.

## References

1. H. Chen, R. H. Chiang, and V. C. Storey, “Business intelligence and analytics: From big data to big impact,” MIS. Quarterly, vol. 36, no. 4, pp. 1165–1188, 2012.
2. S. Kalra, B. Perumal, S. Yadav, and S. J. Narayanan, "Analysing and Predicting the purchases done on the day of Black Friday," 2020 International Conference on Emerging Trends in Information Technology and Engineering (ic-ETITE), 2020, pp. 1-8, doi: 10.1109/ic-ETITE47903.2020.256.
3. C. -S. M. Wu, P. Patil, and S. Gunaseelan, "Comparison of Different Machine Learning Algorithms for Multiple Regression on Black Friday Sales Data," 2018 IEEE 9th International Conference on Software Engineering and Service Science (ICSESS), 2018, pp. 16-20, doi: 10.1109/ICSESS.2018.8663760.
4. M. H. Rehman, C. S. Liew, A. Abbas, P. P. Jayaraman, T. Y. Wah et al., “Big data reduction methods: A survey,” Data Science and Engineering, vol. 1, no. 4, pp. 265–284, 2016.

