# BA 545 Course Project 1: Advanced Preparation of Financial Data
## Spring 2020

## Overview of the Competition

We created 3 pipelines and each of us took a pipeline to focus on. Tony focused on Pipeline 1, Brian on Pipeline 2 and Monika on Pipeline 3. The pipelines are listed on the top of each file showing the order of operation we performed. Overall, the pipelines vary in the optional order section, specifically, outlier IQR or outlier standard deviation, normalization and standardization z-score or min-max. 

After running these 3 main pipelines and hundreds of sub-pipelines we found our optimal pipeline with the highest F1 and AUC scores in Pipeline 1. The results for Y1 - F1 .6879; AUC .7172 and for Y2 - F1 .7385; AUC .6835. However, pipeline 2 and pipeline 3 resulted in similar but slightly less favorable F1 and AUC scores. 

### Submission Rules
We submitted one file with each pipeline in a different workbook. Pipeline 1 has the most optimal results and highest F1 and AUC scores. At the top of each pipeline the optimal results are listed under conclusion section. 

### Additional Rules
We split the work evenly by taking over one pipeline for each person. In the beginning we worked together to finish the steps involved in each pipeline, such as, impulation, normalization and standardization. 

### Conclusion
Under the assumption that "All IPO's are underpriced", the baseline accuracy for Y1 and Y2 are the following: Y1 : 50.15% accuracy; Y2: 67.60% accuracy. However, our model proved to outperform these baseline results. Our Y1 model performed 18.61% better than the baseline model and our Y2 model performed 6.25% better than the baseline model. In conclusion, our logistic regression model is better than random guessing or leaving it up to a 50/50 coin toss.