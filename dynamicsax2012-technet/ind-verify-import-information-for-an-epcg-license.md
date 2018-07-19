---
title: (IND) Verify import information for an EPCG license
TOCTitle: (IND) Verify import information for an EPCG license
ms:assetid: bbe59b27-f9a8-4c7d-843e-6a10b7da93a9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664842(v=AX.60)
ms:contentKeyID: 49386172
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (IND)
- india
- import information
- Verify import information
audience: Application User
ms.search.region: India
---

# (IND) Verify import information for an EPCG license 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can view the import details for an Export Promotion Capital Goods (EPCG) license in the **Import details** form.

1.  Click **General ledger** \> **Common** \> **EXIM EPCG Schemes**.

2.  Select the export-import (EXIM) EPCG scheme for which to view import details.

3.  On the **Action Pane**, in the **Inquiries** group, click **Import details**.

4.  In the **Import details** form, view the import details, including information in the following fields:
    
      - **Import value as per license** – The import value of the EPCG license.
    
      - **Import value in total** – The total import value.
    
      - **Maximum utilization pct.** – The maximum percentage of the allowable import value for cost, insurance, and freight (CIF).
        
        **Example**
        
        If the allowable import value is 1,000, and the maximum utilization percentage is 10 percent, the maximum allowable import value is 1,100.
    
      - **Allowable import value** – The import value that is allowed for exemption of duty. This calculation is based on the following formula:
        
        Import value per license + (Import value as per license \* Maximum utilization pct. /100)
    
      - **Import value for export obligation** – The import value that is used to calculate the export obligation amount.
        
        **Example**
        
        If the import value that is used to calculate the export obligation amount is 1,100, and the CIF factor is 8, the export obligation amount is 8,800.

## See also

[(IND) Verify the approved EPCG scheme details](ind-verify-the-approved-epcg-scheme-details.md)

[(IND) Verify details about the technology upgrade for an EPCG license](ind-verify-details-about-the-technology-upgrade-for-an-epcg-license.md)

[(IND) Verify export obligation details for an EPCG license](ind-verify-export-obligation-details-for-an-epcg-license.md)

[(IND) Verify the block extension details](ind-verify-the-block-extension-details.md)

  


