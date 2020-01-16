---
title: (RUS) Set up fixed asset value models
TOCTitle: (RUS) Set up fixed asset value models
ms:assetid: 536b5ec5-ff98-4c24-ae43-75ef880796d1
ms:mtpsurl: https://technet.microsoft.com/library/JJ911379(v=AX.60)
ms:contentKeyID: 51784209
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up fixed asset value models 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You define a value model so that you can create fixed asset transactions in the general ledger for accounting functions, such as tax and business transactions. You can also create sub-models and depreciation groups for each value model.

Use this procedure to set up value models for fixed assets.

1.  Click **Fixed assets** \> **Setup** \> **Value models**.

2.  Press CTRL+N to create a new value model.

3.  In the **Value model** field, enter the code for the value model. In the **Name** field, enter the name of the value model.

4.  In the **Currency** field, select the currency code for the fixed asset value model.

5.  In the **Round-off** field, enter the value that is used to round amounts.

6.  In the **Posting profile** field, select the posting profile that is used for the fixed asset transactions.

7.  In the **Posting profile (Shortage)** field, select the posting profile that is used to write off fixed assets.

8.  In the **Posting layer** field, select a posting layer for value model transactions, from the following options:
    
      - **Current** − The value model is used for all general business transactions and corrections.
    
      - **Operations** – The value model is used for unique business transactions and corrections that are part of the periodic financial reporting for internal purposes.
    
      - **Tax** − The value model is used for tax accounting purposes.
        

        > [!NOTE]
        > <P>A separate posting profile must be configured for the tax value model, because the value of the fixed asset tax account is based on off-balance accounts.</P>



9.  Click the **FA value submodels** FastTab to create sub-models or derived models for the value model.

10. In the **Value model** field, select a derived model for the value model.

11. In the **Transaction type** field, select the type of transaction that the derived model is associated with.

12. Click **Depreciation groups** to define depreciation groups for the value model. For more information, see [(RUS) Depreciation groups (form)](https://technet.microsoft.com/library/jj678328\(v=ax.60\)).

## See also

[(RUS) Value models (modified form)](https://technet.microsoft.com/library/jj923586\(v=ax.60\))

  


