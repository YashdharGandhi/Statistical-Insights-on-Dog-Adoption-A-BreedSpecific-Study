# **Statistical Insights on Dog Adoption: A Breed-Specific Study**

## **Project Objective**
This project explores the impact of dog breed on adoption times, challenging the conventional assumption of a 27-week average rehoming time. Using statistical analysis and probability distribution modeling, we assess whether breed differences significantly influence adoption durations and whether adoption strategies should be tailored accordingly.

## **Data Description**
The dataset focuses on various dog breeds and their respective rehoming times. Key attributes include:

- **Breed**: Classification of dogs into different breeds.
- **Rehomed**: Number of weeks taken for a dog to find a new home.
- **Visited**: Number of times a dog was viewed before adoption.
- **Health**: General health score of the dog.
- **Age**: Age category (Puppy or Fully Grown).
- **Reason**: Reason for rehoming.
- **Returned**: Whether the dog was returned after adoption.

### **Data Preprocessing Steps**
- Removed missing values (10.34% of dataset).
- Eliminated duplicate entries, finalizing 337 distinct records.
- Identified outliers using box plots to improve dataset integrity.

## **Tasks Performed**
1. **Descriptive Statistics**
   - Calculated mean, variance, standard deviation, and skewness for rehoming times across breeds.
   - Analyzed health scores and age distribution for each breed.

2. **Distribution Modeling**
   - Fitted Normal, Exponential, and Poisson distributions to understand the nature of rehoming times.
   - Used the Method of Moments estimation to determine key parameters for each distribution.

3. **Hypothesis Testing**
   - **Kolmogorov-Smirnov test**: Checked if rehoming times follow a normal distribution.
   - **One-Sample Z-Test**: Compared breed-specific rehoming times to the hypothesized 27-week average.
   - **Two-Sample T-Tests**: Compared rehoming times between different breeds to determine statistical dependencies.

## **Key Findings**
- Significant differences in rehoming times between breeds:
  - **Labrador Retrievers & Rottweilers** have similar normal distributions.
  - **Staffordshire Bull Terriers** exhibit a distinct distribution, differing significantly from the others.
- Exponential and Poisson distributions provide different perspectives on hazard rates and adoption event counts.
- Breed-specific adoption trends suggest that shelters should tailor their adoption strategies for different breeds.

## **Requirements to Run the Code**
To reproduce the analysis, ensure you have the following installed:

### **Software & Environment**
- **R (version 4.0 or later)**
- **RStudio (recommended for ease of use)**

### **Required R Packages**
Install the necessary R packages before running the script:
install.packages(c("ggplot2", "dplyr", "gridExtra", "MASS", "moments", "tidyr"))

## Author 
**Yashdhar Gandhi**

## License
This project is licensed under the MIT License.
