# CustomerSegmentation
<img width="942" alt="image" src="https://user-images.githubusercontent.com/47039591/156309367-1099330e-03d2-402f-b6f5-e4de95767347.png">
image credit:https://www.segmentify.com/blog/top-customer-segmentation-examples-every-marketer-needs-to-know

## Background & Goal
The bank marketing team wants to launch a targeted marketing ad campaign which is tailored  to a specific group of customers.  To ensure the effectiveness of the ad campaign, the team would like to segment the customers into distinctive groups based on their similarities or behaviors. Therefore, I will explore the patterns from the given transaction data and leverage unsupervised machine learning method to the group the unlabeled customers.

## Data Descriptions

The sample Dataset summarizes the usage behavior of about 9000 active credit card holders. The file is at a customer level with 18 behavioral variables.

- **CUSTID:**   Identification of Credit Card holder 
- **BALANCE:** Balance amount left in customer's account to make purchases
- **BALANCE_FREQUENCY:** How frequently the Balance is updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated)
- **PURCHASES:** Amount of purchases made from account
- **ONEOFFPURCHASES:** Maximum purchase amount done in one-go
- **INSTALLMENTS_PURCHASES:** Amount of purchase done in installment
- **CASH_ADVANCE:** Cash in advance given by the user (get a short-term cash loan at a bank or ATM.)
- **PURCHASES_FREQUENCY:** How frequently the Purchases are being made, score between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased)
- **ONEOFF_PURCHASES_FREQUENCY:**  (1 = frequently purchased, 0 = not frequently purchased)
- **PURCHASES_INSTALLMENTS_FREQUENCY:** How frequently purchases in installments are being done (1 = frequently done, 0 = not frequently done)
- **CASH_ADVANCE_FREQUENCY:** How frequently the cash in advance being paid
- **CASH_ADVANCE_TRX:** Number of Transactions made with "Cash in Advance"
- **PURCHASES_TRX:** Number of purchase transactions made
- **CREDIT_LIMIT:** Limit of Credit Card for user
- **PAYMENTS:** Amount of Payment done by user
- **MINIMUM_PAYMENTS:** Minimum amount of payments made by user  
- **PRC_FULL_PAYMENT:** Percent of full payment paid by user
- **TENURE:** Tenure of credit card service for user
