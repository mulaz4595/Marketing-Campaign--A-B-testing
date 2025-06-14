# Marketing A/B Testing Analysis

A comprehensive analysis of marketing campaign effectiveness using A/B testing methodology to determine whether advertisements outperform public service announcements in driving user conversions.

## Project Overview

This project analyzes a marketing A/B test dataset to answer key business questions:
- Does advertising lead to higher conversion rates than control messaging?
- What is the statistical significance of observed differences?
- What are the business implications and recommended next steps?

## Dataset

**Source:** https://www.kaggle.com/datasets/sahilnbajaj/marketing-campaigns-data-set

**Size:** 588,101 user records

**Variables:**
- `user_id`: Unique user identifier
- `test_group`: Either "ad" (advertisement) or "psa" (public service announcement)
- `converted`: Boolean indicating whether user made a purchase
- `total_ads`: Number of ads shown to user
- `most_ads_day`: Day of week with highest ad exposure
- `most_ads_hour`: Hour of day with highest ad exposure

## Key Findings

### Conversion Rates
- **Advertisement Group:** 2.55% conversion rate (14,423 conversions from 564,577 users)
- **PSA Control Group:** 1.79% conversion rate (420 conversions from 23,524 users)
- **Improvement:** 43.1% relative increase in conversions

### Statistical Significance
- **Chi-square statistic:** 54.01
- **P-value:** < 0.001
- **Result:** Statistically significant difference confirmed

## Business Impact

The analysis demonstrates that advertising campaigns generate measurably higher conversion rates compared to control messaging. The 0.77 percentage point improvement translates to approximately 8 additional conversions per 1,000 ad exposures.

## Files

- `marketing_AB.csv` - Raw dataset
- `ab_testing_analysis.ipynb` - Complete analysis notebook
- `ab_testing_dashboard.html` - Interactive results dashboard
- `README.md` - Project documentation

## Tools Used

- **Python:** pandas, matplotlib, scipy
- **Statistical Analysis:** Chi-square test for independence
- **Visualization:** Chart.js for interactive dashboard

## How to Run

1. Clone this repository
2. Install required packages: `pip install pandas matplotlib scipy`
3. Run the Jupyter notebook: `ab_testing_analysis.ipynb`
4. Open `ab_testing_dashboard.html` in your browser to view results

## Methodology

1. **Data Exploration:** Examined dataset structure and quality
2. **Group Analysis:** Calculated conversion rates for each test group
3. **Statistical Testing:** Applied chi-square test to determine significance
4. **Business Analysis:** Interpreted results and calculated business impact
5. **Visualization:** Created dashboard for stakeholder presentation

## Recommendations

Based on the analysis results:

- **Continue Current Campaign:** The advertising strategy shows proven effectiveness
- **Scale Investment:** Consider increasing budget allocation given positive ROI
- **Optimize Targeting:** Focus on high-performing user segments
- **Monitor Performance:** Establish ongoing measurement framework
- **Test Variations:** Experiment with different ad formats and messaging

## Author

Created as part of data analysis portfolio demonstrating A/B testing methodology and statistical analysis skills.

## License

This project is for educational and portfolio purposes.