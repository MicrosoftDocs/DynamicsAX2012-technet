---
title: Set up fixed asset posting profiles
TOCTitle: Set up fixed asset posting profiles
ms:assetid: b91d226b-4e53-411e-86e3-27e6dfc62c9d
ms:mtpsurl: https://technet.microsoft.com/library/Aa498846(v=AX.60)
ms:contentKeyID: 36676407
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up fixed asset posting profiles 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Depending on the structure of the chart of accounts and the requirements for ledger reporting, the posting profiles that are set up for fixed assets can be either very detailed or very general. The profiles that are set up must meet your organization’s requirements for financial reporting.

1.  Click **Fixed assets** \> **Setup** \> **Fixed asset posting profiles**.

2.  Click **New** to create a fixed asset posting profile.

3.  Enter a unique identifier and a description for the posting profile.

4.  Click the **Ledger accounts** FastTab. The fixed asset transaction types are listed.

5.  Select a transaction type that your legal entity uses, such as **Acquisition**.

6.  Click **Add** to create a line for each value model that uses this transaction type. Select the value model in the **Value model** field.

7.  For each value model, select a value for the **Main account** and **Offset account** fields. The same accounts can be used for multiple value models or all value models.
    

    > [!NOTE]
    > <P>You typically change the value of the fixed asset when you post and select a main account that has a main account type of <STRONG>Balance sheet</STRONG> for the <STRONG>Main account</STRONG> field. The offset account is often a main account that has a main account type of <STRONG>Profit and loss</STRONG>, because income or expenditures are often posted for fixed asset transactions. There can be exceptions to these very general rules. Therefore, you must understand the objectives of your legal entity for each fixed asset transaction type and posting profile.</P>



8.  Add all the value models that use the selected posting type and specify the necessary posting accounts.

9.  Select the next transaction type to define for the posting profile, and then repeat steps 6 through 8.

## See also

[Fixed asset posting profiles (form)](https://technet.microsoft.com/library/aa571467\(v=ax.60\))

  


