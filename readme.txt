AML Transaction Monitoring Project

This project analyzes financial transaction data using Python to identify
potential money laundering risks.

The analysis focuses on detecting common AML red flags such as:
- Structuring (multiple small transactions below reporting thresholds)
- Transactions involving high-risk countries
- Unusual transaction spikes compared to normal account behavior

Using these red flags, the project assigns risk scores and risk categories
to transactions and generates alerts for high-risk activity.

The results are summarized at both the transaction level and the
account level and exported as CSV files for review.

Tools Used:
- 
