# Workflow Settings

The **Workflow Settings** module defines the actual operational flow that the organization follows during key stages of the loan lifecycle. It applies to **Loan Approval**, **Loan Disbursement**, **Collateral Registry**, and **Collateral Approval**. These settings determine the sequence of actions, assign responsible user groups, and enforce approval thresholds based on loan amounts.

<figure><img src="../.gitbook/assets/workflo setting.png" alt=""><figcaption></figcaption></figure>

1. Navigate to the **Administration** Module
2. Under the Administration module, select **Workflow Settings**
3. In the top-left corner of the Users screen, click the **"+ New Work Flow Setting"**
4. Fill the workflow setting and save

### Creating workflow setting

<figure><img src="../.gitbook/assets/setting form.png" alt=""><figcaption></figcaption></figure>

| Property              | Description                                                                                                     |
| --------------------- | --------------------------------------------------------------------------------------------------------------- |
| Workflow type         | Specifies the operational category of the workflow being configured                                             |
| Workflow status       | Selects the specific status from the predefined list that the record must pass through in this stage            |
| Description           | A brief explanation of what this workflow setting                                                               |
| Loan product          | Specifies which loan product(s) this workflow setting applies to(optional)                                      |
| Documents             | Lists the required documents that must be submitted (optional)                                                  |
| User groups           | Specifies the system user group(s) responsible for processing or reviewing records at this workflow stage.      |
| Min transaction limit | The minimum loan amount required for this workflow setting to be applied                                        |
| Max transaction limit | The maximum loan amount allowed for this workflow setting                                                       |
| Loan type             | Specifies the category of the loan this workflow applies                                                        |
| Is conditional        | True or False indicator whether this workflow setting has custom conditions applied                             |
| Is credit officer     | Flags the setting as one that must be handled specifically by a credit officer                                  |
| Send notification     | Determines whether a system-generated notification should be triggered when a record enters this workflow stage |

