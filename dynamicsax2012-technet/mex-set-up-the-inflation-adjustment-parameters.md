---
title: (MEX) Set up the inflation adjustment parameters
TOCTitle: (MEX) Set up the inflation adjustment parameters
ms:assetid: 19930efb-020f-49b4-aa05-479612ad62a0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208451(v=AX.60)
ms:contentKeyID: 36056114
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Mexico
- parameters
- adjustment
- inflation
- inflation adjustment
audience: Application User
ms.search.region: Mexico
---

# (MEX) Set up the inflation adjustment parameters 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you can update ledger account balances using the inflation adjustment method assigned to an account, you must set up the Índice nacional de precios al consumidor (INPC) inflation rates in the **INPC rates** form. After you set up the rates, use the **General ledger parameters** form to set up the inflation adjustment parameters for the inflation adjustment calculation. You can also select a revaluation account code and revaluation method for inflation adjustment.

## Set up the calculation factors for inflation adjustment

Use the **General ledger parameters** form to specify the ledger account and the offset account for inflation adjustment calculation.

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  Click the **Ledger** link, in the **Account for inflation correction (REPOMO)** field, select the ledger account to post the adjustment inflation amount for Resultado por Posición Monetaria (REPOMO) and inflation recognition (RESTATE).

3.  In the **Inflation offset account** field, select the offset account to use for inflation adjustment transactions.

4.  Close the form to save your changes.

## Set up parameters to revalue inflation adjustment

Use the **Main accounts - chart of accounts: %1** form to select a main account for inflation adjustment and specify the inflation adjustment method.

1.  Click **General ledger** \> **Setup** \> **Chart of accounts** \> **Chart of accounts**.

2.  On the right pane, click **New** to open the **Main accounts - chart of accounts: %1** form.

3.  Select a main account, and then click the **Setup** FastTab. For more information, see [Main accounts - chart of accounts (form)](https://technet.microsoft.com/en-us/library/hh209695\(v=ax.60\))

4.  In the **Posting type** field, select the posting type for the main account.

5.  Under the **Inflation accounting B-10** field group, select the **B-10 adjustment** check box to include the ledger account in the inflation adjustment process and to indicate that the account should be revalued based on government standards.

6.  In the **Adjustment method** field, select the type of inflation adjustment method from the following options:
    
      - **None** – The inflation is not adjusted.
    
      - **Transaction date** – The inflation adjustment is based on the transaction date. The account type can be **Equity**, **Asset**, **Liability**, or **Balance sheet**.
    
      - **Opening balance** – The adjustment method is based on the opening account balance. The account type can be **Asset**, **Liability**, or **Balance sheet**.
    
      - **Monthly balance** – The adjustment method is based on the monthly account balance. The account type can be **Profit and loss**, **Expense**, or **Revenue**.
    
      - **Balance** – The adjustment method is based on the account balance.
    

    > [!NOTE]
    > <P>This field is only available if you select the <STRONG>B-10 adjustment</STRONG> check box.</P>



7.  Close the forms to save your changes.

## See also

[(MEX) Set up inflation rates](mex-set-up-inflation-rates.md)

[(MEX) Create and post inflation adjustment ledger transactions](mex-create-and-post-inflation-adjustment-ledger-transactions.md)

[General ledger parameters (form)](https://technet.microsoft.com/en-us/library/aa557286\(v=ax.60\))

  


