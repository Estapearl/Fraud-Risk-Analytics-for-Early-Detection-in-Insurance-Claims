<h1 align="center">Driving Early Fraud Detection in Insurance Claims</h1>
<h2 align="center">Fraud Risk Analytics for Proactive Claims Investigation at Verita Assurance Ltd</h2>

<h2>Project Background</h2>

<p>
  Verita Assurance Ltd. is a mid-sized insurance company in the UK that provides auto, home, travel, and business insurance.
  Over the last two years, the company noticed a <strong>14% rise in suspicious insurance claims</strong>. Most of these cases
  were only discovered <strong>after claims had already been paid</strong>, leading to financial losses that could not be recovered
  and higher investigation costs.
</p>

<p>
  As the number of claims continued to grow, the Risk Management team did not have a clear, centralized way to
  <strong>identify high-risk claims early</strong> or decide <strong>which claims should be investigated first</strong>. Fraud checks
  were mainly done after payment, making it difficult to prevent losses before they occurred.
</p>

<p>
  This analysis was carried out to help Verita Assurance <strong>spot potential fraud earlier in the claims process</strong>, using
  past claims data to highlight risky patterns and support <strong>earlier investigation before payouts are made</strong>.
</p>


**Verita Assurance Ltd.** is a mid-sized insurance provider based in the UK, offering auto, home, travel, and business coverage. Over the past two years, the company has experienced a **14% rise in suspicious claims**, with most fraudulent activity detected only **after payouts were made**, leading to unrecoverable financial losses and higher operational costs. As claim volumes grew, the lack of a unified fraud detection process increased both financial exposure and compliance risks, prompting the need for a more proactive, data-driven solution.

---
The dataset analyzed contained **7,000+ claims** across various insurance types, with a **total claim value of £76.4M**. Of these, **471 claims worth £8.84M (11.6%)** were flagged as high-risk through a fraud scoring framework. The analysis revealed that **auto claims accounted for 77.5%** of high-risk claims, followed by **business claims at 22.5%**. Regionally, **London and the Midlands** recorded the highest fraud exposure. Furthermore, **16.1% of customers and several agents** showed recurring fraud patterns, emphasizing the need for tighter oversight. These insights provided a strong empirical foundation for improving fraud risk management.

---

This analysis was developed in collaboration with the **Risk Management Department** to enhance early fraud detection across Verital insurance claims data. The objective is to leverage **historical claims data** to uncover recurring patterns, assign **fraud risk scores (0–100)**, and categorize claims into high, medium, and low-risk tiers. By integrating these insights into **real-time Power BI dashboards**, the team can now identify and investigate suspicious claims **before payouts occur**, enabling them to act swiftly, minimize financial losses, and strengthen overall **risk governance**.

---
### Key Analytical Focus Areas

- **Fraud Pattern Detection:** Historical claims data was analyzed to identify recurring behaviors and indicators commonly linked with fraudulent submissions, including duplicate claims, unusually high claim values and short policy tenures.  

- **Risk Scoring and Classification:** A fraud scoring model (0–100) was developed to categorize claims into high, medium or low-risk tiers, enabling faster prioritization for investigation before payouts are made.

- **Customer and Agent Behavior Profiling:** Customer and agent activity patterns were evaluated to uncover relationships between repeated claim submissions, claim frequency and past fraud involvement, strengthening early risk identification.  

- **Real-Time Fraud Monitoring:** Interactive Power BI dashboards were implemented to visualize risk levels across claims, customers and regions, allowing the Risk Management and Compliance teams to monitor exposure and respond proactively.

<h2 align="center">Executive Summary</h2>

<table width="100%">
<tr>

<!-- LEFT: REGION -->
<td width="50%" valign="top" align="center">

<img src="Percentage%20Fraud%20Risk%20by%20Region.png" width="100%" />

<p><b>📊 Percentage Fraud Risk by Region</b></p>

<p align="left">
London shows the <b>highest fraud exposure</b>, with <b>7% of all claims flagged as high risk</b> despite contributing only <b>31% of total claim volume</b>.  
This indicates fraud is <b>concentrated in high-activity regions</b>, where large volumes allow suspicious behaviour to blend in.  
The <b>Midlands (6%)</b> and <b>Wales (7%)</b> also show notable fraud risk, proving that fraud is <b>not limited to major cities</b>.
<br><br>
<b>Insight:</b> London is the <b>primary fraud hotspot</b> and should be prioritised for stricter pre-claim checks.
</p>

</td>

<!-- RIGHT: CLAIM TYPE -->
<td width="50%" valign="top" align="center">

<img src="High%20Risk%20Claim%20by%20Claim%20Type.png" width="100%" />

<p><b>🚘 High-Risk Claims by Claim Type</b></p>

<p align="left">
<b>Business insurance claims</b> have the <b>highest fraud risk (15%)</b>, significantly higher than <b>Auto claims (10%)</b>.  
This reflects how <b>high-value and complex policies</b> attract more fraudulent activity due to larger payouts.  
<b>Home and Travel claims</b> show minimal fraud, meaning <b>smaller claims are less targeted</b>.
<br><br>
<b>Insight:</b> Business policies should undergo <b>enhanced fraud screening</b> before settlement.
</p>

</td>

</tr>
</table>

## How Fraud Risk Was Calculated

Each insurance claim was evaluated using multiple fraud risk indicators designed to capture abnormal or suspicious behaviour. 
Rather than relying on a single signal, a rule-based scoring framework was used to measure overall fraud exposure per claim.

The fraud risk model was built using the following indicators:

- Duplicate claims (same customer or policy submitting similar claims)
- Unusually high claim values compared to normal ranges
- Claims submitted during weekends

Each claim received a fraud score based on how many of these indicators were triggered.  
Claims with multiple active flags were classified as **High Risk**, while fewer flags resulted in **Medium, Low, or No Risk** categories.

## Key Fraud Insights
The fraud risk model and dashboard revealed several important patterns across Verita Assurance’s claims portfolio:

- Fraud is highly concentrated in specific regions, with London and the Midlands showing the highest number of high-risk claims.
- Business and Auto insurance products generate the largest share of suspicious claims, making them the primary drivers of fraud exposure.
- A small group of customers and agents account for a disproportionate number of high-risk and multi-flag claims.
- Only 6.7% of total claims are flagged as High Risk, yet they represent a significant portion of potential financial loss, highlighting the value of targeted investigations.

