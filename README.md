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

<h2 align="center">Executive Summary</h2>

<table width="100%">
  <tr>

    <!-- LEFT: Region Chart + Insight -->
    <td width="50%" align="center" style="vertical-align: top; padding: 10px;">

      <img src="Percentage%20Fraud%20Risk%20by%20Region.png" 
           alt="Percentage Fraud Risk by Region" width="95%">

      <h4>📊 Percentage Fraud Risk by Region</h4>

      <p align="left">
        <b>London</b> recorded the <b>highest fraud exposure</b>, with <b>7% of all claims flagged as high risk</b> despite representing <b>31% of total claim volume</b>.  
        This shows that fraud activity is <b>heavily concentrated in high-transaction regions</b>, where large claim volumes make abnormal behaviour harder to detect.  
        The <b>Midlands (6%)</b> and <b>Wales (7%)</b> also display notable fraud risk, proving that fraud is <b>not limited to major metropolitan areas</b>.  
        <br><br>
        <b>Insight:</b> <b>London is the primary fraud hotspot</b> and should be prioritised for enhanced monitoring and stricter pre-claim verification.
      </p>

    </td>

    <!-- RIGHT: Claim Type Chart + Insight -->
    <td width="50%" align="center" style="vertical-align: top; padding: 10px;">

      <img src="High%20Risk%20Claim%20by%20Claim%20Type.png" 
           alt="High Risk Claim by Claim Type" width="95%">

      <h4>🚘 High-Risk Claims by Claim Type</h4>

      <p align="left">
        <b>Business insurance claims</b> show the <b>highest fraud exposure at 15%</b>, significantly exceeding <b>Auto claims (10%)</b>.  
        This reflects how <b>high-value and complex policies</b> attract more fraudulent activity due to larger potential payouts and looser validation processes.  
        In contrast, <b>Home and Travel claims</b> exhibit minimal fraud, suggesting that <b>lower-value claims are less targeted</b>.  
        <br><br>
        <b>Insight:</b> <b>Business policies should undergo enhanced fraud screening and risk-based approval</b> before settlement.
      </p>

    </td>

  </tr>
</table>

