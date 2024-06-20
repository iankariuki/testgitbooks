# Fees

The Fees module allows for the structured creation and management of various charges levied on customers. These charges are imposed on customers for specific services or activities. These can include application fees, processing fees and other types of service charges.

## Creating a Fee

<figure><img src="../.gitbook/assets/fee first step.png" alt=""><figcaption></figcaption></figure>

1. Navigate to the **Accounting** module
2. Under Accounting go to **fees**
3. Click the **"+ New Fee"** button located at the top left
4. In fee creation, fill the following information:
   1. fees information
   2. graduate scale details
   3. fees split details

### Fees information

<figure><img src="../.gitbook/assets/fee information.png" alt=""><figcaption></figcaption></figure>

1. **Name:** The name of the fee.
2. **Category:** The category determines the context in which the fee is applied
   * **Loans:** The fee is applied to the loan
   * **All:** The fee is applied to both loan and savings
   * **Savings:** The fee is applied to savings
3. **Recovery Method:** The method specifies how and when the fee is recovered from the customer
   * **Recurring per term:** The fee is applied on each term of the loan
   * **Recurring per schedule:** The fee is applied according to the loan repayment schedule
   * **Upfront:** The fee is paid once at the beginning of the loan service&#x20;
4. **Recovery Account:** This field indicated from which account the fee will be deducted
   * **Savings Account:** The fee is deducted from the customer's savings account.
   * **Loan Account:** The fee is deducted from the customer's loan account
5. **Recovery Type:** The type of recovery defines the specific event or process during which the fee is collected
   * **Loan Origination:** The fee is recovered at the initiation of the loan
   * _Customer Onboarding:_ The fee is recovered when a customer is onboarded into the system
   * _Loan Servicing:_ The fee is recovered during the servicing phase of the loan

### Graduate Scale Details

<figure><img src="../.gitbook/assets/fee graduate scale details.png" alt=""><figcaption></figcaption></figure>

1. **Lower Limit:** This defines the lowest value for which a particular fee applies
2. **Upper Limit:**  This defines the highest value for which a particular fee applies
3. **Charge Type:** The method by which the fee amount is calculated
   * _Fixed:_ The fee is a set, unchanging amount
   * _Percentage:_ The fee is calculated as a percentage of a specified amount
4. **Value:** The exact amount to be charged. This could either be a fixed monetary amount or a percentage, depending on the selected charge type.

### Fee Splits Details

<figure><img src="../.gitbook/assets/fee splits details.png" alt=""><figcaption></figcaption></figure>

1. **Chart of Accounts:** Select the specific chart of accounts to which the fee will be applied
2. **Name:** Assign a descriptive name to the fee
3. **Percentage:** Define the percentage allocation of the fee. If the fee is to be split across multiple accounts, ensure that the total allocation adds up to 100%.
