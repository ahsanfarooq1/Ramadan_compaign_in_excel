# MCD Ramadan Campaign Analysis in Excel

## Introduction

This report presents a comprehensive analysis of a digital marketing campaign conducted during Ramadan across **TikTok**, **Meta** (Facebook & Instagram), and **Snapchat**. The primary objective of the analysis is to evaluate the campaign's performance in terms of **brand awareness**, **engagement**, and **conversions**.

By leveraging Excel's data cleaning, analysis, and visualization capabilities, this report aims to uncover valuable insights into the campaign's effectiveness and identify areas for improvement. The analysis includes:

- **Data Cleaning**
- Applying formulas to categorize performance
- Creating **Pivot Tables**
- Conditional formatting

Through a detailed examination of key performance indicators (**KPIs**) like **impressions**, **clicks**, **click-through rate (CTR)**, **cost per click (CPC)**, and **engagement metrics**, this report provides actionable recommendations to enhance future campaigns.

## Dataset
The dataset used for this analysis is available [here](https://github.com/ahsanfarooq1/Ramadan_compaign_in_excel/blob/main/V4%20-%20MCD%20-%20Ramadan%20Campaign%20-%20Report%20(1).xlsx)

## Dataset Attributes

The dataset includes several key attributes essential for understanding the ad data and insights derived from it. Below is a description of each attribute:

1. **Market**: Geographic market where the ad was displayed.
2. **Campaign Name**: Name of the specific ad campaign.
3. **Audience**: Target audience for the ad, defined by demographics, interests, or other characteristics.
4. **Ad Name**: Unique name for each individual ad.
5. **Language**: Language of the ad content (e.g., Arabic, English).
6. **Format**: Type of ad format, such as video or image.
7. **Creative Variation**: Different creative variations used for testing, including visual and textual differences.
8. **Amount Spent**: Total monetary expenditure on the ad.
9. **Clicks**: Total number of clicks the ad received.
10. **Paid Reach**: Count of individuals who saw the ad and were part of the paid audience.
11. **Cost Per Click (CPC)**: Average cost per individual click on the ad.
12. **Paid Reach (Duplicate)**: Repeated measure for the number of individuals who were part of the paid audience.
13. **Total Impressions**: Total number of times the ad was displayed (includes multiple views by the same person).
14. **Click-Through Rate (CTR)**: Percentage of impressions that resulted in clicks (calculated as clicks divided by impressions).
15. **Cost Per Mille (CPM)**: Cost per 1,000 impressions of the ad.
16. **2-Second Video Views**: Count of instances the video was viewed for at least 2 seconds.
17. **Video Completions**: Number of times viewers watched the video to completion.
18. **View-Through Rate (2 Sec) (VTR)**: The percentage of impressions that resulted in at least 2 seconds of video view time (calculated as 2-second video views divided by impressions).
19. **View-Through Rate (Complete)**: Percentage of impressions that resulted in full video completion (calculated as video completions divided by impressions).
20. **Total Engagement**: Total interactions with the ad, including likes, comments, shares, and other forms of engagement.
21. **Engagement Rate**: The ratio of engagement to impressions, providing insight into how effectively the ad engaged its audience.

This structure ensures clarity for all users working with the dataset, offering a comprehensive understanding of the data used in the analysis.

## Key Performance Indicators (KPIs) and Analysis Questions

This analysis uses specific KPIs to evaluate ad performance across various social media platforms and focuses on data cleaning, performance evaluation, and summarizing key metrics with pivot tables. Below are the main analysis questions:

### 1. Data Cleaning and Preparation

- **Q1: Text-to-Column Requirement in TikTok Data**  
  Identify which columns in the TikTok data required splitting using the Text-to-Column function. Document the steps taken to clean and prepare the data for analysis, ensuring consistency and accuracy.

- **Q2: Error Patterns in Meta Data**  
  After cleaning the Meta data, observe any patterns or errors that required correction. Document these patterns and the adjustments made before proceeding with further analysis.

### 2. Performance Evaluation

- **Q3: CTR Evaluation in Meta Data**  
  Using the Meta data, apply an IF statement to evaluate the Click-Through Rate (CTR) of each campaign. Determine the percentage of campaigns that had a "Good" CTR, defined as a rate above 2%. This insight helps gauge the effectiveness of campaign engagement.

- **Q4: Low Engagement Campaigns on Snapchat**  
  Use the NOT function to identify campaigns on Snapchat with low engagement, specifically those with fewer than 1,000 clicks. Document the total number of campaigns flagged for low engagement and discuss potential implications for campaign strategy.

### 3. Pivot Tables

- **Q5: CTR by Campaign Name in TikTok Data**  
  Create a Pivot Table from the TikTok data to sum impressions and clicks by campaign name. Identify the campaign with the highest CTR and hypothesize reasons for its success, considering factors like target audience, ad format, or content type.

- **Q6: Conversion Rate by Age Group in Meta Data**  
  From the Meta data, create a Pivot Table to analyze ad performance across different age groups. Identify the age group with the highest conversion rate and discuss how this insight could guide future ad targeting and content strategies.

---

These KPIs and questions are central to evaluating campaign performance across platforms, providing actionable insights for optimizing future ad strategies.

## Detailed Analysis Report 

My detailed analysis report is available [here](https://github.com/ahsanfarooq1/Ramadan_compaign_in_excel/blob/main/Excel%20portfolio%20by%20Ahsan.pdf)

## Conclusions

1. **Campaign Performance Across Platforms**  
   Analysis shows that campaign performance varied significantly across platforms. Snapchat emerged as the most cost-effective platform, with the lowest Cost Per Engagement (CPE) at $25.03, making it highly efficient for budget allocation. TikTok also performed well, with a CPE of $35.23, while Meta (Facebook & Instagram) had the highest CPE at $120.78, indicating it required more budget to achieve similar levels of engagement.

2. **High Variation in Click-Through Rate (CTR)**  
   CTR varied widely across platforms and demographics. Campaigns targeting Millennials, particularly on TikTok, achieved significantly higher CTRs compared to campaigns targeting Boomers. This suggests that younger audiences, especially Millennials, are more responsive to digital advertising, with TikTok being particularly effective in engaging this demographic.

3. **Significant Number of Low Engagement Campaigns**  
   On Snapchat, 72% of campaigns had low engagement levels, registering fewer than 1,000 clicks. This high number of low-performing campaigns indicates a need for better-targeted ads, creative optimization, and possibly strategic improvements in ad placement to enhance campaign outcomes.

4. **Top-Performing Campaigns**  
   Specific campaigns, such as `CNMCDRamadanCHTiktokMKAETGAwareness`, demonstrated high CTR, particularly on TikTok in the UAE market. The campaign’s success underscores the importance of targeted content, engaging visuals, and clear calls to action. This example highlights how well-aligned creative content with market needs can drive high engagement.

## Recommendations

1. **Allocate More Budget to Snapchat**  
   Given Snapchat’s low CPE, increasing budget allocation for this platform is recommended for future campaigns. By focusing on Snapchat and improving targeting strategies, engagement levels could increase, maximizing return on investment (ROI) and reducing low-performing campaigns.

2. **Focus on Millennials for Higher Conversion Rates**  
   With Millennials showing the highest conversion rates across platforms, especially on Meta and TikTok, future campaigns should prioritize this demographic. Tailoring content, messaging, and ad formats to resonate with younger audiences, particularly on TikTok, could enhance engagement and conversions.

3. **Re-evaluate Low-Engagement Campaigns on Snapchat**  
   To address low engagement, especially on Snapchat, a re-evaluation of targeting strategies is essential. Experimenting with different audience segments, refining ad messaging, and optimizing landing pages can help boost engagement rates and improve campaign performance.

4. **Creative Optimization for Meta Ads**  
   Meta (Facebook & Instagram) had the highest CPE but remains crucial due to its wide reach and targeting options. Focusing on creative optimization can lower the cost per engagement. Testing different ad formats (e.g., video vs. image), messaging, and creative elements can improve CTR and reduce costs.

5. **Monitor Competitor Activities for Differentiation**  
   Observing competitor activities closely can inform strategy adjustments. By positioning the brand effectively and ensuring differentiation, engagement and conversion rates could improve, particularly in competitive platforms like Meta.

---

These conclusions and recommendations offer a data-driven approach to optimize future ad strategies, emphasizing platform efficiency, demographic targeting, and creative improvements for enhanced engagement and ROI.


## PDF Page 1
![PDF Page 1](.https://github.com/ahsanfarooq1/Ramadan_compaign_in_excel/blob/main/Excel%20portfolio%20by%20Ahsan.pdf)


