---
title: (IND) Create purchase credit notes for excisable goods
TOCTitle: (IND) Create purchase credit notes for excisable goods
ms:assetid: 41f16c4a-5cda-49f0-91fc-a4e8fa46b41c
ms:mtpsurl: https://technet.microsoft.com/library/JJ664648(v=AX.60)
ms:contentKeyID: 49385725
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Create purchase credit notes for excisable goods 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When you return the purchased goods to your vendor by using a credit note, the excise amount that is calculated is reversed.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Click the **Purchase** tab, and then click **Credit note** to create a credit note. Attach the related purchase order to the credit note.

3.  Select the **Tax as per original invoice** check box to apply the tax rate for excise as it was on the date the original order was invoiced.
    
    For example, a purchase order is invoiced on April 10, 2008, and the rate of BED on this date is 12%. A credit note is posted on May 21, 2008, and the rate of excise on this date is 15%.
    
      - If you select the **Tax as per original invoice** check box, the tax rate for the calculation of excise on the credit note will be 12%.
    
      - If the **Tax as per original invoice** check box is not selected, the tax rate will be 15%.

4.  Select the transactions for creating the credit note.

5.  Post the credit note. The excise duty is calculated for the number of items returned. You can modify the values entered in the fields that are related to excise or delete any of the values in these fields before posting the credit note.
    

    > [!NOTE]
    > <P>For more information, see <A href="ind-about-transactions-that-include-excise-duty.md">(IND) About transactions that include excise duty</A>.</P>



## See also

[(IND) Purchase orders (modified form)](https://technet.microsoft.com/library/jj664798\(v=ax.60\))

[(IND) Copy purchase orders (modified form)](https://technet.microsoft.com/library/jj664580\(v=ax.60\))

  


