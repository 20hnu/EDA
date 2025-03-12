# Digital Marketing Conversion Trends Analysis

This Notebook contains an in-depth analysis of digital marketing conversion trends, exploring how different demographics and campaign types impact conversion metrics. The dataset includes attributes such as customer demographics, campaign channels, and engagement metrics to derive key insights into marketing effectiveness.

## Dataset

**Columns:**  
`CustomerID`, `Age`, `Gender`, `Income`, `CampaignChannel`, `CampaignType`, `AdSpend`, `ClickThroughRate`, `ConversionRate`, `WebsiteVisits`, `PagesPerVisit`, `TimeOnSite`, `SocialShares`, `EmailOpens`, `EmailClicks`, `PreviousPurchases`, `LoyaltyPoints`, `AdvertisingPlatform`, `AdvertisingTool`, `Conversion`

## Key Findings & Conclusions

### Demographic-Based Marketing Insights

- **Teenagers & Seniors** respond most effectively to **social media campaigns**.
- **Young Adults** engage best with **SEO-driven campaigns**.
- **Adults** are most influenced by **email marketing campaigns**.
- Across all genders and campaign types, various campaign channels are utilized effectively.
- PPC (pay per click)
### Gender-Based Best Campaign Channels by Marketing Funnel

| Marketing Funnel Stage | Male          | Female        |
|------------------------|--------------|--------------|
| Awareness             | Referral     | Referral     |
| Consideration         | PPC          | Social Media |
| Conversion           | Referral     | SEO         |
| Retention            | Email        | Referral     |

### Best Campaign Channels for Marketing Outcomes

| Metric         | Female         | Male          |
|---------------|---------------|--------------|
| ClickThroughRate | PPC        | Social Media |
| ConversionRate   | Social Media | Social Media |
| WebsiteVisits    | Email        | Social Media |
| PagesPerVisit   | PPC          | Social Media |
| TimeOnSite      | Social Media | PPC          |

## Ad Spend & Engagement Metrics

- **Ad spend does not significantly impact engagement metrics** such as:
  - Click-Through Rate (CTR)
  - Website Visits
  - Pages Per Visit
  - Time on Site
  - Email Clicks
- **However, increased ad spending positively influences** key performance indicators such as:
  - Conversion Rate
  - Social Shares
  - Email Opens

## Effectiveness of Campaign Types

- **Referral campaigns** excel in driving **Email Opens & Email Clicks**.
- **PPC campaigns** are most effective for **Click-Through Rates (CTR)**.
- **Social Media campaigns** lead in:
  - Conversion Rates
  - Website Visits
  - Pages Per Visit
  - Time on Site
  - Social Shares

## Correlation Between Website Visits & Conversion Rate

- A **statistical analysis** confirms that an **increase in website visits leads to a higher conversion rate**.
- However, **Time Spent on Website does not significantly impact conversion rates**.
- A combined analysis of Website Visits & Time Spent on Site (**F-statistic = 0.8666, p-value = 0.420**) indicates **no strong predictive relationship between these variables and conversion rate**.

## Conclusion

This analysis provides critical insights into how different demographics, genders, and campaign strategies influence digital marketing effectiveness. The findings underscore the importance of **targeted marketing strategies** and **optimizing ad spend** for better conversion rates and engagement outcomes.
# Mental Health in Pregnancy During COVID-19

## Dataset

**Columns:**  
`OSF_ID`, `Maternal_Age`, `Household_Income`, `Maternal_Education`, `Edinburgh_Postnatal_Depression_Scale`, `PROMIS_Anxiety`, `Gestational_Age_At_Birth`, `Delivery_Date` (converted to month and year), `Birth_Length`, `Birth_Weight`, `Delivery_Mode`, `NICU_Stay`, `Language`, `Threaten_Life`, `Threaten_Baby_Danger`, `Threaten_Baby_Harm`

## Key Findings & Conclusions

- **Women aged 25-38** during conception experience **low anxiety and postpartum depression**, leading to better care for themselves and their newborns.
- **Pregnancy beyond 42 years** poses a **high risk of premature birth**, typically occurring **before 7.5 months of gestation**.
- **Women aged 25-42** show **less concern about COVID-19’s impact** on themselves and their newborns compared to **younger (<25) and older (>45) women**.
- **Women over 38** are **13% more likely** to require a **C-section**.
- **Significant association** between **maternal age and NICU stay** due to **unhealthy birth weight**, but **no significant association** with **birth height**.
- **High anxiety, depression, and premature birth** are key contributors to **NICU admission**.
- **Families earning below $70,000** are **70% more likely** to suffer from **anxiety and depression** due to COVID-19.
- **Higher income** reduces the probability of **mental health struggles**, with **high-income women facing a 33% risk** compared to lower-income women.
- **Families below survival line** show **high concern for maternal health**, with a **51/100 threatening score**, whereas **higher-income families worry less** due to better healthcare access.
- **Concerns for newborn health** are **universal across income groups**, leading to **increased anxiety during pregnancy**.
- **Women with high EPDS scores** have a **higher likelihood of premature birth**, but typically **after 8.5 months, reducing health risks**.
- **Anxiety and EPDS scores are highly correlated**, showing that **increased depression often results in increased anxiety**.
- **Unhealthy birth weight babies** have a **22% NICU stay probability**, **15% higher** than healthy birth weight babies.
- **Low-income, low-education women** across all age groups are **most vulnerable** to **high EPDS scores**, though **high-income, highly educated women aged 40+ are also at risk**.
- **81% of women with high EPDS scores** also suffer from **high anxiety**.
- **Families with low income** show **higher pandemic-related concerns** about maternal and newborn health.
- **Education and income** both significantly influence the **level of COVID-19 concern** among pregnant women.

Dataset link: https://drive.google.com/drive/u/1/folders/1ECQTeOqB8rR8ZBiQeiBnxGSzAgYvu95b
