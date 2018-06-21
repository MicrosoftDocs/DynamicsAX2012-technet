---
title: Include budgets in cash flow forecasts
TOCTitle: Include budgets in cash flow forecasts
ms:assetid: 8b199556-def2-42e0-80a4-7670bf9b9990
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa498248(v=AX.60)
ms:contentKeyID: 36941345
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Include budgets in cash flow forecasts [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can include budgets that are created from budget models in cash flow forecasts.

1.  Click **Budgeting** \> **Setup** \> **Basic budgeting** \> **Budget models**.

2.  If you want the cash flow forecast to include budgets that are based on a specific budget model, select the **Cash flow forecasts** check box on the **General** FastTab. Close the form.

3.  Click **General ledger** \> **Common** \> **Main accounts**.

4.  Select a main account that is based on the budget model from step 2, and that you want to include in the cash flow forecast. On the **Action Pane**, click **Edit**.

5.  In the **Select the level of main account to display** field, select **Companies**, and then select a legal entity in the **Companies** field. On the **Setup** FastTab, click **Cash flow forecast**.

6.  In the **Set up cash flow forecasts** form, select or enter values in the fields to specify how to include each budget register entry in the cash flow forecast:
    
      - **Percent** – Specify the percentage of the budget amount on the account that will be included.
    
      - **Terms of payment** – Specify the terms of payment. For ledger budgets, this is the period from the actual transaction date until the future transaction occurs. For inventory forecasts, the terms are copied from the customer or vendor account.
    
      - **Posting type** – If appropriate, specify the posting type of the expected transactions, such as **Vendor settlement**.
    
      - **Main account** – Specify the main account into which the percentage of the budget amount is posted.
    
      - **Transactions/Budget** – Select **Budget**.
    

    > [!NOTE]
    > <P>To include the whole budgeted amount in the cash flow forecast, specify the following field values:</P>
    > <UL>
    > <LI>
    > <P><STRONG>Percent</STRONG> – Enter 100.</P>
    > <LI>
    > <P><STRONG>Terms of payment</STRONG> – Leave this field blank.</P>
    > <LI>
    > <P><STRONG>Main account</STRONG> – Select the budget account.</P></LI></UL>



7.  Close the **Set up cash flow forecasts** form, and then close the **Main accounts - chart of accounts: %1** form.

8.  To generate cash flow amounts for the general ledger, sales, and purchases based on the budget, open the **Period allocation categories** form. Create period allocation keys that indicate the share of the budget that is used in the cash flow forecasts. Then apply the keys in the relevant parameter setup forms:
    
      - In the **Budget parameters** form, select an allocation key for cash flow forecasts for budgeting.
    
      - In the **Ledger and sales tax** area of the **Accounts receivable parameters** form, select an allocation key for cash flow forecasts for sales budgets.
    
      - In the **Ledger and sales tax** area of the **Accounts payable parameters** form, select the allocation key for cash flow forecasts for purchase budgets.
    
    **Example**
    
    The budget for the year is divided into monthly budget periods. The allocation key for cash flow forecasts divides the months into weeks, and 25 percent of the budget is allocated to each week. If the cash flow forecast is calculated on the tenth day of the month, the cash flow forecasts include only 75 percent of the budget for that month.

9.  If appropriate, add inventory forecasts to the cash flow forecasts by setting up cash flow forecasts on the ledger budget:
    
    1.  In the **Forecast models** form in Inventory and warehouse management, select the **Cash flow forecasts** check box.
    
    2.  In the **Set up cash flow forecasts** form for the appropriate ledger budget, select values for the fields, as described in step 6.

10. If appropriate, transfer sales and purchase budgets to the ledger budget:
    
      - Click **Inventory management** \> **Periodic** \> **Forecast** \> **Update** \> **Sales budget to ledger**.
    
      - Click **Inventory management** \> **Periodic** \> **Forecast** \> **Update** \> **Purchase budget to ledger**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

