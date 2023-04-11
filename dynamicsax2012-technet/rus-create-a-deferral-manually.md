---
title: (RUS) Create a deferral manually
TOCTitle: (RUS) Create a deferral manually
ms:assetid: 305e22f5-46a4-461b-9398-fb14d698c7a5
ms:mtpsurl: https://technet.microsoft.com/library/JJ665249(v=AX.60)
ms:contentKeyID: 49387338
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (RUS)
- Russia
- deferral
audience: Application User
ms.search.region: Russia
---

# (RUS) Create a deferral manually 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Deferrals** form to manually create a deferral. You must also specify the deferrals model for a deferral. The status of a deferral that is created manually is updated to **Scheduled**. You cannot manually modify the status of a deferral that is created manually.

1.  Click **General ledger** \> **Common** \> **Deferrals**.

2.  Press CTRL+N to create a new deferral.

3.  In the **Number** and **Name** fields, enter the unique identification number and name of the deferral.

4.  In the **Comment** field, enter a detailed description of the deferral.

5.  In the **Date attached** field, select the date when the deferral is created.
    

    > [!NOTE]
    > <P>The <STRONG>Table name</STRONG> field displays the name of the table that provides the source data that is used to generate the deferral. The <STRONG>Reference</STRONG> field displays the number of this table.</P>



6.  In the **Expense code** field, select the expense code.

7.  In the **VAT offset method for deferrals** field, select the method that is used to deduct value-added tax (VAT) for the deferral. The following options are available:
    
      - **Standard** – Process the incoming VAT for factures that are related to deferrals by using the standard VAT deduction method.
    
      - **Proportionate** – Process the incoming VAT for factures that are related to deferrals by using the proportional VAT deduction method.

8.  Click **Deferrals models** to open the **Deferrals models** form.

9.  Create or select a deferrals model for the deferral. For more information, see [(RUS) Set up a deferrals model](rus-set-up-a-deferrals-model.md).

## See also

[(RUS) Deferrals models (form)](https://technet.microsoft.com/library/jj678655\(v=ax.60\))

  


