#  AB-Test Analysis
## by Moamen Abdelkawy

## Dataset

A/B tests are very commonly performed by data analysts and data scientists. This project tries to understand the results of an A/B test run by an e-commerce website. The company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. The goal is to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.

This project is a part of Udacity Advanced Data Analysis Nanodegree.

## Summary of Findings

- The data shows that during the experiment, 11.96% of users converted regardless of the page they received. The conversion rate was slightly higher among those received the old page with a rate of 12.04% compared to 11.88% for new page users.

- However, the differences are narrow and do not provide a compelling evidence. More investigation is required using A/B test and regression models.

- Sampling distribution was generated under the null (assuming that the new page is not effective or even worse).The analysis found that more than 90% of the samples generated during the simulation had diff above the observed value (p-value = 0.9012); hence, the study concluded that we can't reject the null. Meaning that the new page is ineffective or even worse in generating higher conversion rate.

- Using a regression approach, the study acheived similar results. P-value associated with the slop was 0.190, indicating no statistical significance. 

- In addition, there was no evidence that users' countries affect the conversion rate.

## Limitations
This analysis did not include the influences associated with time on conversion.
