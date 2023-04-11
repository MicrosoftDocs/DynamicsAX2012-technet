---
title: (IND) Verify tax amounts for an incentive scheme by using a bill of entry journal
TOCTitle: (IND) Verify tax amounts for an incentive scheme by using a bill of entry journal
ms:assetid: 02c450a4-a502-453b-b22a-23cfa7e62d25
ms:mtpsurl: https://technet.microsoft.com/library/JJ664437(v=AX.60)
ms:contentKeyID: 49385526
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Verify tax amounts for an incentive scheme by using a bill of entry journal 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Tax transactions** form to view the total amount of sales tax, incentive scheme tax, and balance tax for a purchase order. You can also use this form to view any amounts that have been adjusted for the incentive scheme tax and balance tax.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. Select a purchase order, and then, on the **Action Pane**, on the **Customs** tab, in the **Journals** group, click **Bill of entry**.

2.  In the **Bill of entry journal** form, on the **Lines** FastTab, click **Tax**.
    

    > [!NOTE]
    > <P>This button is available only if you select the <STRONG>Customs</STRONG> check box in the <STRONG>Apply India taxes</STRONG> field group in the <STRONG>Sales tax</STRONG> area in the <STRONG>General ledger parameters</STRONG> form.</P>



3.  On the **Overview** FastTab, view the quantity of items that were purchased, the sales tax amount, and the sign direction (debit or credit) that is posted for the selected purchase order.

4.  On the **General** FastTab, view the following details for the selected purchase order:
    
      - In the **Current currency** field group, view the value on which the sales tax is calculated, stated in the company currency.
    
      - In the **Amount** field group, view the calculated amount of sales tax.
    
      - In the **Adjustment** field group, view the adjusted amount of the sales tax, stated in the company currency.
    
      - In the **Customs currency** field group, in the **Tax amount** field, view the total amount of tax for the selected purchase order. The value is displayed in the currency of the vendor for the transaction.
    
      - In the **Adjustment in customs currency** field group, in the **Actual tax amount** field, view the corrected tax amounts for the incentive scheme tax and balance tax. The values are displayed in the customs currency.

## See also

[(IND) Tax transactions (form)](https://technet.microsoft.com/library/jj710906\(v=ax.60\))

  


