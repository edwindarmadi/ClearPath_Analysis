# ClearPath Marketing Insights

## The goal of this project is to investigate the performance of marketing campaigns at ClearPath in order to surface recommendations on marketing budget allocation across future campaign categories

Founded in 2016, ClearPath is a U.S.-based medical insurance company serving thousands of customers. In 2019, they introduced marketing campaigns focused on wellness tips, affordability, and preventative care. Customers can choose from four plans—bronze, silver, gold, and platinum—offering varying premiums and coverage rates.

Now that they’ve hired a new data team and are strategizing their marketing budget for the year, the company would like to build more understanding of the effectiveness of these campaign categories and how they relate to signups and subsequent patient claims. The budget is allocated to drive two primary objectives: 1) to increase the number of customer signups, and 2) to raise awareness of MedCare's brand across the country.

# Dataset Structure

The dataset consisted of three tables, including information about campaigns, signups and user demographics, as well as claims filed by customers and related claim information.

![ClearPath Dataset](https://github.com/user-attachments/assets/90b73249-d747-430a-88a7-6d3fd7e01930)

# Insights Summary

In order to evaluate campaign performance, we focused on the following key metrics:
* Signup Rate: The percent of people who see a campaign and subsequently sign up for a Row Health plan.
* Cost per Signup: The average dollars spent in order to acquire a signup from each campaign.
* Click through Rate: The percent of people who see a campaign and click on the associated link.

<p></p>


**Marketing**
* Health for All and Benefit Updates achieved the highest CTRs (22–25%) despite having low impression volumes, showing strong audience engagement relative to reach
* Benefit Updates also recorded one of the lowest CPCs ($0.04), making it a cost-efficient campaign with high engagement per dollar spent
* Golden Years Security showed the lowest CTR (1%) and the highest CPC ($0.68) — nearly 10× higher than the average ($0.07), this reflects an inefficent campaign and potential overspending relative to campaign impact
* Family Health Coverage is missing CTR and CPC data, this needs to be investigated as it indicates a potential data quality or tracking issues
* Tailored Health Plans drove the highest impressions (1.3M) but only a moderate CTR (7%), suggesting the campaign reached many people but didn’t drive as much engagement

**Signups**
* Health for All had the highest signup rate (2.08%) and the second-highest signup count (3,545), showing strong conversion efficiency at a below-average cost per signup ($1.23)
* Healthy Living recorded the highest signup count (3,727) and a slightly above-average signup rate (0.27%), suggesting broad reach with consistent conversion, though lower efficiency compared to top performer Health for All
* Coverage Matters achieved the third-highest signup count (3,536) and an above-average signup rate (0.50%), while maintaining the lowest cost per signup ($0.65) — indicating strong overall campaign effectiveness
* Golden Years Security had the highest cost per signup ($176.73), the lowest signup rate (0.01%), and the lowest signup count (23), reflecting poor cost efficiency and limited audience conversion.

**Claims**
* Customers from the Compare Health Coverage had the highest Average Claim Amount of $410 and the highest number of claims at 3.9M
* The average claim amount for Compare Health Coverage was ~50% greater than the $267 average, which raises concerns about its cost-effectiveness and sustainability.
* Claim amounts rose with the surge in signups during 2021–2022. The Compare Health Coverage campaign stood out, climbing to a high of $173K in July 2022 before dropping in later months as claim counts fell.

## Recommendations

**1. Reassess underperforming campaigns for budget efficiency**

Review the Golden Years Security campaign — it has the lowest CTR (1%), lowest signup rate (0.01%), and highest CPC ($0.68), signaling weak audience targeting and cost inefficiency. Consider reducing spend or testing new creatives to improve ROI

**2. Expand investment in high-performing campaigns**

Health for All and Benefit Updates continue to outperform across engagement and cost metrics. Health for All achieved a strong CTR (25%) with an efficient CPC ($0.10) and high signup rate (2.08%), while Benefit Updates delivered similarly strong CTR (22%) at a notably low CPC ($0.04). Both campaigns show high engagement efficiency and are strong candidates for further budget allocation or audience expansion

**3. Investigate data quality and tracking gaps**

The Family Health Coverage campaign shows missing CTR and CPC data. Investigate issues with campaign or missing data

**4. Analyze high-claim campaigns for sustainability**

Compare Health Coverage produces the highest total claim amount ($3.9M) and average claim ($410) — ~50% above the portfolio average. Collaborate with risk and actuarial teams to assess whether this reflects higher-value customers or rising cost exposure

## Dashboard
The dashboard can be found in Tableau Public [here](https://public.tableau.com/app/profile/edwin.darmadi/viz/ClearPathMedicalDashboard/Dashboard3?publish=yes). This dashboard enables users to filter by plan, campaign type, and state, and focuses on trends and values in marketing metrics, signup metrics, and claim metrics.

<img width="2447" height="2728" alt="ClearPath Medical Dashboard" src="https://github.com/user-attachments/assets/cbda9fcd-7937-4a5b-b5b3-549571f72cbf" />

## Presentation Sample
The presentation created for the marketing team walks through the insights and recommendations above and can be found [here](url). Some extracts are presented below for easy viewing
