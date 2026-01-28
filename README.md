<h1 align="center">Driving Early Fraud Detection in Insurance Claims</h1>
<h2 align="center">Fraud Risk Analytics for Proactive Claims Investigation at Verita Assurance Ltd</h2>

<h2>Project Background</h2>

<p>
  Verita Assurance Ltd. is a mid-sized insurance provider in the UK offering auto, home, travel, and business insurance.
  Over the past two years, the company recorded a <strong>14% increase in suspicious insurance claims</strong>. In many cases,
  potential fraud was only identified <strong>after claims had already been paid</strong>, leading to financial losses that could not
  be recovered and higher investigation costs.
</p>

<p>
  As claim volumes increased, the Risk Management team did not have a <strong>single, consistent way to identify high-risk claims early</strong>
  or decide <strong>which claims should be investigated first</strong>. Fraud checks were largely reactive, making it difficult to prevent losses
  before payouts were made and increasing both financial and compliance risk.
</p>

<p>
  To address this, a fraud risk analytics initiative was carried out using historical claims data. The aim was to
  <strong>identify recurring fraud patterns</strong>, <strong>assign fraud risk scores</strong>, and support <strong>earlier investigation of suspicious claims before settlement</strong>.
</p>

<h2>Scope of the Analysis</h2>

<p>
  The analysis reviewed <strong>over 7,000 insurance claims</strong> with a total claim value of <strong>£76.4M</strong> across auto, home, travel,
  and business insurance. Using a fraud scoring approach, <strong>471 claims worth £8.84M</strong> were flagged as high risk.
</p>

<ul>
  <li>Auto claims accounted for <strong>77.5%</strong> of high-risk claims</li>
  <li>Business claims made up the remaining <strong>22.5%</strong></li>
  <li>Fraud risk was highest in <strong>London</strong> and the <strong>Midlands</strong></li>
  <li><strong>16.1%</strong> of customers and a small number of agents were linked to repeated high-risk activity</li>
</ul>

<p>
  These findings highlighted clear patterns in where fraud risk is concentrated and provided a strong basis for improving fraud risk management.
</p>

<h2>Key Analytical Focus Areas</h2>

<ul>
  <li>
    <strong>Fraud Pattern Detection:</strong>
    Reviewing past claims to identify common signs of fraud such as repeated claims, unusually high claim values, and short policy duration.
  </li>
  <li>
    <strong>Risk Scoring and Classification:</strong>
    Assigning fraud risk scores (0–100) and grouping claims into High, Medium, and Low Risk to support investigation prioritization.
  </li>
  <li>
    <strong>Customer and Agent Behaviour:</strong>
    Identifying customers and agents associated with repeated or concentrated fraud risk to strengthen oversight.
  </li>
  <li>
    <strong>Fraud Risk Monitoring:</strong>
    Bringing insights together in a dashboard to allow ongoing monitoring of fraud risk across claims, regions, customers, and agents.
  </li>
</ul>


<h2 align="center">Executive Summary</h2>
## Insight 1: Identifying and Prioritising High-Risk Claims

One of the key objectives of this analysis was to identify which insurance claims carry the highest fraud risk and should be reviewed before payment is made.

The chart shows how claims were grouped into High, Medium, and Low Risk categories. This grouping was built from patterns seen in historical claims—such as repeat submissions, unusually high claim amounts, and short policy duration—that have previously been linked to fraud. Going forward, these same patterns can be used to score new claims as they come in, so suspicious claims are flagged early and routed for review before payout.

Out of more than 7,000 claims analysed, 471 claims were classified as high risk. While this is a small share of total claims, it represents the priority investigation queue for the Risk Management team. Medium-risk claims can be monitored, while low-risk claims can proceed with minimal friction to avoid unnecessary delays for genuine customers.

This approach shifts fraud detection from post-payment discovery to early risk screening, improving investigation focus and reducing preventable fraud losses.

**Why this insight matters**
- Helps flag risky claims early using patterns already seen in past fraud cases  
- Enables faster, more focused investigations  
- Protects genuine customers by reducing unnecessary claim delays  

**Claims Distribution by Fraud Risk Category**

![Claims Distribution by Fraud Risk Category](assets/claims_distribution_by_fraud_risk_category.png)

---

## Insight 2: Understanding Financial Exposure from Fraud Risk

Beyond the number of risky claims, it is important to understand how much money is actually at risk. This chart shows the total claim value associated with each fraud risk category.

Although high-risk claims represent a smaller share of total claims, they account for an estimated £8.84M in potential fraud exposure. This highlights that fraud risk is not evenly distributed by volume alone—a small number of claims can still carry significant financial impact if not identified early.

Medium-risk claims account for a larger share of overall claim value. While these claims may not require immediate investigation, they represent an area where ongoing monitoring is important, as even a small increase in fraud activity within this group could lead to material losses.

Low-risk claims make up the largest portion of total claim value but are less likely to be fraudulent. Allowing these claims to move through the process with minimal friction helps protect customer experience while keeping investigative focus on higher-risk cases.

By viewing fraud risk through a financial lens, Verita Assurance can prioritise investigations not only by volume, but by potential loss, ensuring that fraud controls are focused where they deliver the greatest business value.

**Why this insight matters**
- Shows where financial exposure is concentrated  
- Helps justify proactive fraud controls in monetary terms  
- Supports better prioritisation of investigation effort  

**Total Claim Amount by Fraud Risk Category**

![Total Claim Amount by Fraud Risk Category](assets/total_claim_amount_by_fraud_risk_category.png)

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

