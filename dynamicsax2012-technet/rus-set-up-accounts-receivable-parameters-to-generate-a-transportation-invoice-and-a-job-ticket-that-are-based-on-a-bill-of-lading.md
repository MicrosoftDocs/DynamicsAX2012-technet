---
title: (RUS) Set up accounts receivable parameters to generate a transportation invoice and a job ticket that are based on a bill of lading
TOCTitle: (RUS) Set up accounts receivable parameters to generate a transportation invoice and a job ticket that are based on a bill of lading
ms:assetid: ef314f00-7da2-4a22-a670-2615c7154ab3
ms:mtpsurl: https://technet.microsoft.com/library/JJ678590(v=AX.60)
ms:contentKeyID: 49388073
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up accounts receivable parameters to generate a transportation invoice and a job ticket that are based on a bill of lading 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Accounts receivable parameters** form to specify the parameters that are required to generate a transportation invoice and a job ticket. For more information, see [(RUS) About transportation invoices and job tickets that are based on bills of lading](rus-about-transportation-invoices-and-job-tickets-that-are-based-on-bills-of-lading.md).

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  Click **Shipments**.

3.  In the **Bill of lading** field, specify the circumstances in which a bill of lading is created when a shipment is dispatched. You can select from the following options:
    
      - **None** – A bill of lading is not created.
    
      - **Packing slip update** – A bill of lading is created when a packing slip is updated.
    
      - **Invoice posting** – A bill of lading is created when an invoice is posted.
    
      - **Both** – A bill of lading is created both when a packing slip is updated and when an invoice is posted.

4.  In the **Document type** field, select **Transportation invoice** or **Job ticket** as the type of bill of lading.

5.  Click **Number sequences**, and then select **Transportation document number.** and **Job ticket number** to set up number sequences for both types of documents.

## See also

[Accounts receivable parameters (form)](https://technet.microsoft.com/library/aa576993\(v=ax.60\))

  


