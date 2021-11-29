---
title: (IND) Post service tax in purchase transactions by using the Invoice approval journal form
TOCTitle: (IND) Post service tax in purchase transactions by using the Invoice approval journal form
ms:assetid: 0325e79f-eac0-46b1-975b-58f7c9a3f548
ms:mtpsurl: https://technet.microsoft.com/library/JJ664438(v=AX.60)
ms:contentKeyID: 49385527
author: Khairunj
ms.date: 05/06/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.LedgerJournalTransApprove
- Forms.LedgerJournalTable
audience: Application User
ms.search.region: India
---

# (IND) Post service tax in purchase transactions by using the Invoice approval journal form 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012_

Use the **Invoice approval journal** form to create and post a journal to post service tax in purchase transactions. You can specify the service code and service category for each journal line before you post the journal.

1.  Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice approval journal**.

2.  Click **New** to create a journal, enter the journal details, and then click **Lines**. For more information, see [Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md).

3.  Click **Find vouchers**, and select the vouchers to be processed in the journal. For more information, see [Post invoices in the Invoice approval journal form](post-invoices-in-the-invoice-approval-journal-form.md).

4.  In the **Sales tax group** field, select the service tax group for the vendor.

5.  In the **Item sales tax group** field, select the item tax group for the vendor. The sales tax group and the item sales tax group for a journal line must contain tax codes that have a tax type of **Service tax**.

6.  On the **Tax information** tab, in the **Company information** field group, you can modify the name and current address of the legal entity.

7.  In the **Service code** field, select the service code that is attached to goods of the type **Service**.
    

    > [!NOTE]
    > <P>In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: The accounting code for the service is updated in the <STRONG>Accounting code</STRONG> field based on the service code that you select. For more information, see <A href="ind-set-up-service-codes-for-service-goods.md">(IND) Set up service codes for service goods</A>.</P>



8.  Depending on the version that you are using, do one of the following:
    
      - In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: In the **Service category** field, select one of the following options to specify the service category for the journal line:
        
          - **Inward** – Select this option when you purchase goods from a vendor.
        
          - **Inter unit or input** – Select this option when you transfer goods between two units within your legal entity, or from the legal entity to a subcontractor for additional processing. For example, you can select this option when the goods are manufactured in one unit, and then transferred to the packing unit of your legal entity.
        
          - **Others** – Select this option for other service categories. The input tax amount for this category is posted to the expense account instead of the recoverable account or the interim recoverable account.
    
      - In Microsoft Dynamics AX 2012 R2: In the **GTA service category** field, select one of the following options to specify the category of goods transport agency (GTA) service:
        
          - **Inward** – Select this option when you purchase goods from a vendor.
        
          - **Outward - inter unit/input** – Select this option when you transfer goods between two units within your legal entity, or from the legal entity to a subcontractor for additional processing.
        
          - **Others** – Select this option for all other categories of GTA services.

9.  On the **Invoice** tab, in the **Consignment note number** field, enter the consignment note number for the vendor.

10. Click **Sales tax** to view the calculation of the service tax in the **Sales tax transactions** form.

11. Close the **Sales tax transactions** form.

12. Validate and post the journal voucher. The service tax amounts are credited to the tax payable accounts.

## See also

[(IND) Calculate service tax for a purchase order](ind-calculate-service-tax-for-a-purchase-order.md)

[(IND) Calculate service tax using a vendor payment journal](ind-calculate-service-tax-using-a-vendor-payment-journal.md)

[(IND) Calculate service tax in an Invoice journal form](ind-calculate-service-tax-in-an-invoice-journal-form.md)

[(IND) Service codes (form)](https://technet.microsoft.com/library/jj664830\(v=ax.60\))

  


