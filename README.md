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
<div style="display: flex; gap: 20px;">

  <div style="flex: 1; background-color: #f9f9f9; border-radius: 10px; padding: 15px; box-shadow: 0 2px 5px rgba(0,0,0,0.1);">
    <h4>📊 Percentage Fraud Risk by Region</h4>
    <ul>
      <li><b>Regional Fraud Concentration:</b> London recorded <b>7%</b> of high-risk claims but contributed <b>31%</b> of total claims — a strong indicator of regional fraud clustering.</li>
      <li><b>Midlands Exposure:</b> The Midlands followed with <b>6%</b> high-risk versus <b>20%</b> total claims, showing notable risk in mid-volume regions.</li>
      <li><b>Regional Comparison:</b> Wales and the North West both recorded <b>7%</b> and <b>6%</b> high-risk shares respectively, suggesting smaller regions are not immune to fraud exposure.</li>
      <li><b>Key Takeaway:</b> Fraud risk is unevenly distributed — London remains a critical zone for proactive fraud monitoring and control.</li>
    </ul>
  </div>

  <div style="flex: 1; background-color: #f9f9f9; border-radius: 10px; padding: 15px; box-shadow: 0 2px 5px rgba(0,0,0,0.1);">
    <h4>🚘 High-Risk Claims by Claim Type</h4>
    <ul>
      <li><b>Category Exposure:</b> Business claims accounted for <b>15%</b> of all high-risk claims, compared to <b>10%</b> for Auto claims.</li>
      <li><b>Policy Sensitivity:</b> Fraud detection shows stronger signals within business-related policies, likely due to higher claim complexity and payout value.</li>
      <li><b>Low-Risk Categories:</b> Home and Travel claims presented no notable high-risk activity in this review period.</li>
      <li><b>Key Takeaway:</b> Business claims require tighter pre-payout investigation and enhanced oversight.</li>
    </ul>
  </div>

</div>


