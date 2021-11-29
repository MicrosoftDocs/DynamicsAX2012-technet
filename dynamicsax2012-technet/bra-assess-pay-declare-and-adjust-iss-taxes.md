---
title: (BRA) Assess, pay, declare, and adjust ISS taxes
TOCTitle: (BRA) Assess, pay, declare, and adjust ISS taxes
ms:assetid: 38f5ade8-12d4-463a-8b29-df7b7a0bbeb2
ms:mtpsurl: https://technet.microsoft.com/library/Dn600272(v=AX.60)
ms:contentKeyID: 62200232
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.FBTaxAssessmentISSListPage_BR
- MsDynAx060.Forms.FBTaxAssessmentISSListPage_BR
audience: Application User
ms.search.region: Brazil
---

# (BRA) Assess, pay, declare, and adjust ISS taxes 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to determine the amount of Brazilian service tax or Imposto sobre Serviços (ISS) to be paid to São Paulo for each fiscal establishment, and for each service code and tax rate.

The ISS tax assessment includes ISS tax from issuing fiscal documents (NFS\_e) and incoming acquired services. There are two types of ISS tax payments:

  - Payments that are based on outgoing service fiscal documents.

  - Payments that are based on incoming service fiscal documents when the ISS tax is retained by the vendor.

## Assess, pay, and declare ISS taxes

To assess, pay, and declare ISS taxes, follow these steps:

1.  Click **Fiscal books** \> **Common** \> **Tax assessment** \> **ISS**.

2.  On the **ISS** list page, on the **Action Pane**, click **ISS tax assessment** \> **New**.

3.  Select the booking period to create the ISS tax assessment for. Click **OK**.

4.  On the **ISS** list page, you can view FactBoxes that display:
    
      - **Debits** – The amount of ISS tax debit that was posted on outgoing services fiscal documents.
    
      - **Retained** – The amount of ISS tax that was retained on incoming services fiscal documents.
    
      - On the bottom part of the **ISS** list page, you can view a summary of ISS tax amounts.

5.  Run ISS reports to determine whether there are any inconsistencies in ISS tax calculations. Follow these steps:
    
      - On the **ISS** list page, on the **Action Pane**, click **Print** \> **ISS tax assessment model book 51**. Select a fiscal establishment and enter a starting and ending date. Click **OK**.
    
      - On the **ISS** list page, on the **Action Pane**, click **Print** \> **ISS tax assessment book acquired services**. Select a fiscal establishment and enter a starting and ending date. Click **OK**.

6.  On the **ISS** list page, click **Fiscal documents** to view the fiscal documents that have an ISS tax amount.

7.  Click **Finalize** to close the selected ISS tax assessment.

8.  To open the ISS tax assessment for additional adjustments, you can select a closed ISS tax assessment on the **ISS** list page, and then click **Reopen**.

  


