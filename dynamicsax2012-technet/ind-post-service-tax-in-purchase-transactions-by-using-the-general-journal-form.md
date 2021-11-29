---
title: (IND) Post service tax in purchase transactions by using the General journal form
TOCTitle: (IND) Post service tax in purchase transactions by using the General journal form
ms:assetid: ab3f66a3-dca9-413c-8a42-b446ba96f493
ms:mtpsurl: https://technet.microsoft.com/library/JJ664759(v=AX.60)
ms:contentKeyID: 49386089
author: Khairunj
ms.date: 05/06/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.LedgerJournalTable
- Forms.LedgerJournalTransDaily
audience: Application User
ms.search.region: India
---

# (IND) Post service tax in purchase transactions by using the General journal form 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012_

Use the **General journal** form to create and post a journal to post service tax in purchase transactions. You can specify the service code and service category for each journal line before you post the journal.

1.  Click **General ledger** \> **Journals** \> **General journal**.

2.  Click **New** to create a journal, enter the journal details, and then click **Lines** to create invoice lines. For more information, see [Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md).

3.  In the **Journal voucher** form, on the **Overview** tab, in the **Sales tax group** field, select the service tax group for the vendor.

4.  In the **Item sales tax group** field, select the item tax group for the vendor. The sales tax group and the item sales tax group for a journal line must contain tax codes that have a tax type of **Service tax**.

5.  On the **Tax information** tab, in the **Company information** field group, you can modify the name and current address of the organization.

6.  In the **Service code** field, select the service code that is attached to goods of the type **Service**.
    

    > [!NOTE]
    > <P>In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: The accounting code for the service is updated in the <STRONG>Accounting code</STRONG> field based on the service code that you select. For more information, see <A href="ind-set-up-service-codes-for-service-goods.md">(IND) Set up service codes for service goods</A>.</P>



7.  Depending on the version that you are using, do one of the following:
    
      - In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: In the **Service category** field, select one of the following options to specify the service category for the journal line:
        
          - **Inward** – Select this option when you purchase goods from a vendor.
        
          - **Inter unit or input** – Select this option when you transfer goods between two units within your legal entity, or from the legal entity to a subcontractor for additional processing. For example, you can select this option when the goods are manufactured in one unit, and then transferred to the packing unit of your legal entity.
        
          - **Others** – Select this option for other service categories. The input tax amount for this category is posted to the expense account instead of the recoverable account or the interim recoverable account.
    
      - In Microsoft Dynamics AX 2012 R2: In the **GTA service category** field, select one of the following options to indicate the category of goods transport agency (GTA) service:
        
          - **Inward** – Select this option when you purchase goods from a vendor.
        
          - **Outward - inter unit/input** – Select this option when you transfer goods between two units within your legal entity, or from the legal entity to a subcontractor for additional processing.
        
          - **Others** – Select this option for all other categories of GTA services.

8.  On the **Invoice** tab, in the **Consignment note number** field, enter the consignment note number for the vendor.

9.  Click **Sales tax** to view the calculation of the service tax in the **Sales tax transactions** form.

10. Click **Formula designer** to view the calculation expression for each tax code. Close the form.

11. Close the **Sales tax transactions** form.

12. Validate and post the journal voucher for the general journal. The service tax amounts are credited to the tax payable accounts.


> [!NOTE]
> <P>When you post the payment to a vendor by using the <STRONG>General journal</STRONG> form, if the payment has an account combination of Vendor account (debit) and Bank account (credit), the service tax payable amounts are posted separately to the tax payable accounts. The taxes are not added to the cost of the inventory even if the <STRONG>Load on inventory</STRONG> check box is selected.</P>



## See also

[(IND) Journal voucher - General journal (modified form)](https://technet.microsoft.com/library/jj678053\(v=ax.60\))

[(IND) Formula designer (form)](https://technet.microsoft.com/library/jj677983\(v=ax.60\))

[(IND) Temporary sales tax transactions (modified form)](https://technet.microsoft.com/library/jj664487\(v=ax.60\))

[(IND) Service codes (form)](https://technet.microsoft.com/library/jj664830\(v=ax.60\))

  


