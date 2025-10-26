<h1 align="center">Fraud Risk Analytics for Early Detection in Insurance Claims</h1>

<h2 align="center">Client Background</h2>

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

---
<h2 align="center">Executive Summary</h2>

<table width="100%">
  <tr>
    <td align="center" width="50%" style="vertical-align: top;">
      <img src="Percentage%20Fraud%20Risk%20by%20Region.png" alt="Percentage Fraud Risk by Region" width="95%"><br>
    </td>
    <td align="center" width="50%" style="vertical-align: top;">
      <img src="High%20Risk%20Claim%20by%20Claim%20Type.png" alt="High Risk Claim by Claim Type" width="95%"><br>
    </td>
  </tr>
</table>
----
<div style="display: flex; justify-content: space-between; gap: 25px; margin-top: 20px;">

  <!-- Chart 1 Explanation -->
  <div style="flex: 1; padding: 18px; background: #fafafa; border-radius: 10px; box-shadow: 0 2px 6px rgba(0,0,0,0.08);">
    <h4 style="text-align:center;">📊 Percentage Fraud Risk by Region</h4>
    <p>
      Analysis revealed that <b>London</b> consistently recorded the <b>highest fraud exposure</b>, with <b>7% of all claims flagged as high risk</b>, despite accounting for <b>31% of total claims</b>.  
      This suggests that fraud cases are <b>heavily concentrated in high-activity regions</b>, likely due to higher transaction volumes and looser manual verification.  
      Meanwhile, the <b>Midlands (6%)</b> and <b>Wales (7%)</b> showed moderate but notable risk levels, indicating that <b>fraud risk is not limited to major metropolitan regions</b>.  
      <b>Insight:</b> London remains the <b>primary fraud hotspot</b>, requiring focused monitoring and stricter pre-claim verification processes.
    </p>
  </div>

  <!-- Chart 2 Explanation -->
  <div style="flex: 1; padding: 18px; background: #fafafa; border-radius: 10px; box-shadow: 0 2px 6px rgba(0,0,0,0.08);">
    <h4 style="text-align:center;">🚘 High-Risk Claims by Claim Type</h4>
    <p>
      The breakdown by claim type shows that <b>Business-related claims</b> had the <b>highest proportion of fraud risk (15%)</b>, far exceeding <b>Auto claims (10%)</b>.  
      This trend reflects how <b>complex and high-value policy types</b> attract more fraudulent attempts due to potential payout size.  
      Conversely, <b>Home and Travel claims</b> displayed <b>minimal or no high-risk activity</b>, suggesting that smaller or lower-value claims remain less targeted.  
      <b>Insight:</b> Business policies require <b>enhanced fraud screening</b> and <b>risk scoring models</b> before settlement approval.
    </p>
  </div>

</div>
---
| **Percentage Fraud Risk by Region** | **High-Risk Claims by Claim Type** |
|------------------------------------|------------------------------------|
| The analysis shows **regional differences** in fraud exposure. **London** accounts for **31% of total claims** but only **7% of high-risk claims**, suggesting better fraud controls relative to its claim volume. **Midland (20% total, 6% high-risk)** and **Scotland (15% total, 8% high-risk)** also stand out. Overall, the chart reveals that while regions like London handle the highest volume, their **fraud risk rate is proportionally lower**, indicating stronger detection measures. | The breakdown by claim type reveals that **Business claims (15%)** and **Auto claims (10%)** make up the majority of high-risk activity. The other claim types show minimal or no high-risk cases. This emphasizes the need for **targeted fraud monitoring** in high-value and vehicle-related claims, as these categories show greater vulnerability to fraudulent behavior. |

