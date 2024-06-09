# Bati Bank Credit Scoring Model
![image](https://github.com/Endework/Bati-Bank/assets/83136075/961e8d11-8ad6-4633-a20b-0e550e2bebc8)

## Overview

This repository contains the development of a Credit Scoring Model for Bati Bank's Buy-Now-Pay-Later service, aimed at evaluating the creditworthiness of potential borrowers.

## Objectives

1. **Risk Management**: Minimize default risks.
2. **Customer Segmentation**: Tailor credit offerings.
3. **Regulatory Compliance**: Ensure adherence to Basel II.
4. **Competitive Advantage**: Enhance reputation and attract customers.
5. **Strategic Growth**: Support market expansion.

## Business Need

Bati Bank seeks to introduce a flexible payment option to meet the growing demand, supporting informed decision-making and operational efficiency while complying with regulations.

## Understanding Credit Risk

Credit risk is the probability of a loss due to a borrower's failure to repay a loan. Effective management ensures profitability and stability for financial institutions.

### Data and Features

- **Source**: [Xente Challenge on Kaggle](https://www.kaggle.com/xentechallenge)
- **Key Fields**: TransactionId, BatchId, AccountId, SubscriptionId, CustomerId, CurrencyCode, CountryCode, ProviderId, ProductId, ProductCategory, ChannelId, Amount, Value, TransactionStartTime, PricingStrategy, FraudResult.

### EDA and Feature Engineering

- Summary statistics and distribution analysis.
- Correlation and missing value analysis.
- Aggregated and extracted features.
- Encoding and standardization of variables.
- RFMS (Recency, Frequency, Monetary value, Stability) features.

## Modeling

Evaluated models: Logistic Regression, Decision Tree, Random Forest, Gradient Boosting Machine. Logistic Regression was chosen for its high performance.

### Model Performance

- **Logistic Regression**: Accuracy: 99.9%, Precision: 0.833, Recall: 0.227, F1 Score: 0.357, ROC-AUC Score: 0.999
- **Other Models**: Performance metrics available in the repository.

## Recommendations

- **Adopt Logistic Regression**: High accuracy and ROC-AUC score.
- **Enhance Recall**: Adjust decision threshold, cost-sensitive learning.
- **Continuous Monitoring**: Regular retraining and performance tracking.
- **Incorporate Alternative Data**: Improve creditworthiness assessment.
- **Regulatory Compliance**: Adhere to Basel II standards.
- **Customer Segmentation**: Develop tailored credit offerings.
- **Educational Outreach**: Improve customer understanding of credit scores.

## Installation and Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/Endework/Bati-Bank.git
    ```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For questions or comments, please open an issue or contact [Endework Abera](mailto:endework99@gmail.com).

---

