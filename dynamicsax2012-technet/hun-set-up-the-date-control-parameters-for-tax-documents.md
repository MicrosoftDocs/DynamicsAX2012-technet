---
title: (HUN) Set up the date control parameters for tax documents
TOCTitle: (HUN) Set up the date control parameters for tax documents
ms:assetid: 8fea2218-e3fe-42fe-925a-39d729b9b065
ms:mtpsurl: https://technet.microsoft.com/library/JJ664331(v=AX.60)
ms:contentKeyID: 49385420
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Hungary
---

# (HUN) Set up the date control parameters for tax documents 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  Click the **Updates** tab.

3.  In the **Invoice date control** field, select the method of invoice date control from the following options:
    
      - **None** − If no date control is applied.
    
      - **Warning** – If the **Document date** is later than **Invoice date** with more than the pre-defined **Number of days**, a warning message is displayed when the invoice is posted. The posting process can continue.
    
      - **Error** – If the **Document date** is later than **Invoice date** with more than the pre-defined **Number of days**, an error message is displayed when the invoice is posted. The posting process is terminated.

4.  In the **Credit note date control** field, select the method of credit note date control from the following options:
    
      - **None** – If no date control is applied.
    
      - **Warning** – If you change the **Document date** so that it differs from the current date, a warning message is displayed.
    
      - **Error** – If you change the **Document date** so that it differs from the current date, an error message is displayed.

5.  In the **Document date control** field, select the document date control method from the following options:
    
      - **None** – If no date control is applied.
    
      - **Warning** - If you change the **Document date** so that it differs from system date, a warning message is displayed.
    
      - **Error** – If you change the **Document date** so that it differs from system date, an error message is displayed.

6.  Select the maximum number of days available to issue the invoice after the fulfillment date in the **Number of days** field.

7.  Press CTRL+S or close the form.

## See also

[(HUN) Accounts receivable parameters (modified form)](https://technet.microsoft.com/library/jj714534\(v=ax.60\))

  


