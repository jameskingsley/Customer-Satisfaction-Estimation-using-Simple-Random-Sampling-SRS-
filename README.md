# Customer-Satisfaction-Estimation-using-Simple-Random-Sampling-SRS-

## Project Overview
This project estimates the overall customer satisfaction of a company using a **probability sampling technique** — specifically **Simple Random Sampling (SRS)**. Using a dataset of Amazon product reviews, we demonstrate sampling, standard error, confidence intervals, and visual validation.

## Dataset
- Source: `cleaned_reviews.csv`
- Contains: 1,177 product reviews with columns:
  - `brand`, `categories`, `name`, `reviews.rating`, `reviews.date`

## Methodology
1. Load the dataset and inspect population statistics
2. Perform Simple Random Sampling (10% sample)
3. Calculate:
   - Sample mean and standard deviation
   - Standard Error with Finite Population Correction (FPC)
   - 95% Confidence Interval
4. Visualize population vs sample using histogram and boxplot
5. Interpret results

## Key Findings
- Sample Mean = 4.2373  
- Population Mean = 4.3594  
- Standard Error = 0.09534  
- 95% Confidence Interval = (4.0504, 4.4242)

> The sample is representative of the population; SRS is effective for estimating customer satisfaction.

## Visualizations
- Histogram: Population vs Sample distribution
<img width="498" height="468" alt="image" src="https://github.com/user-attachments/assets/787cfe1b-97f3-442f-9165-fe97a1179b8d" />

  
- Boxplot: Population vs Sample spread and outliers
<img width="291" height="433" alt="image" src="https://github.com/user-attachments/assets/fed974fd-c476-4e5a-8b6f-b9120a67e504" />


## Author
**James Kingsley** – Data Analyst / Data Scientist

