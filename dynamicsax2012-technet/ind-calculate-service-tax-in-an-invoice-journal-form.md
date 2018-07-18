---
title: (IND) Calculate service tax in an Invoice journal form
TOCTitle: (IND) Calculate service tax in an Invoice journal form
ms:assetid: e8a6a871-4911-43e9-8be6-31641204d914
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ710919(v=AX.60)
ms:contentKeyID: 49386331
ms.date: 05/06/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.LedgerJournalTransVendInvoice
- Forms.LedgerJournalTable
audience: Application User
ms.search.region: India
---

# (IND) Calculate service tax in an Invoice journal form 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012_

Use the **Invoice journal** form to calculate service tax for vendors. You can specify the service code and service category for vendors and foreign vendors before you post the journal.

1.  Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice journal**.

2.  Press CTRL+N to create a journal, and then enter the journal details. For more information, see [Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md) and [(IND) Invoice journal (modified form)](https://technet.microsoft.com/en-us/library/jj677950\(v=ax.60\)).

3.  Click **Lines** to open the **Journal voucher** form.

4.  On the **Overview** tab, enter the invoice line details.

5.  In the **Sales tax group** field, select the service tax group that you have created for the vendor.

6.  In the **Item sales tax group** field, select the item tax group that you have created for the vendor. The sales tax group and the item sales tax group for a journal line must contain tax codes that have a tax type of **Service tax**.

7.  On the **Tax information** tab, in the **Company information** field group, you can modify the company name and address.

8.  In the **Service** field group, in the **STC number** field, select the service tax code (STC) number of the company. The ledger accounts for posting the service tax amounts are identified based on the STC number.

9.  In the **Service code** field, select the service code that is attached to goods of the type **Service**.
    

    > [!NOTE]
    > <P>In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: The accounting code for the service is updated in the <STRONG>Accounting code</STRONG> field based on the service code that you select. For more information, see <A href="ind-set-up-service-codes-for-service-goods.md">(IND) Set up service codes for service goods</A>.</P>



10. Depending on the version that you are using, do one of the following:
    
      - In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: In the **Service category** field, select one of the following options to specify the service category for the journal line:
        
          - **Inward** – Select this option when you purchase goods from a vendor.
        
          - **Inter unit or input** – Select this option when you transfer goods between two units within your legal entity, or from the legal entity to a subcontractor for additional processing. For example, you can select this option when the goods are manufactured in one unit, and then transferred to the packing unit of your legal entity.
        
          - **Others** – Select this option for other service categories for which input tax is paid. The input tax amount for this category is posted to the expense account instead of the recoverable account or the interim recoverable account.
    
      - In Microsoft Dynamics AX 2012 R2: In the **GTA service category** field, select one of the following options to indicate the category of goods transport agency (GTA) service:
        
          - **Inward** – Select this option when you purchase goods from a vendor.
        
          - **Outward - inter unit/input** – Select this option when you transfer goods between two units within your legal entity, or from the legal entity to a subcontractor for additional processing.
        
          - **Others** – Select this option for all other categories of GTA services.

11. On the **Invoice** tab, in the **Consignment note number** field, enter the consignment note number for the vendor.

12. Click **Sales tax** to view the calculation of the service tax in the **Sales tax transactions** form.

13. Click **Formula designer** to view the calculation expression for each tax code. Close the form.

14. Close the **Sales tax transactions** form.

15. Validate and post the journal voucher. The service tax amounts are debited to the interim tax recoverable accounts and to the interim tax payable accounts for the vendor.
    

    > [!NOTE]
    > <P>You can attach a journal line from the <STRONG>Vendor invoice pool excluding posting details</STRONG> form to the invoice journal voucher.</P>



## See also

[(IND) Invoice pool excl. posting (modified form)](https://technet.microsoft.com/en-us/library/jj664595\(v=ax.60\))

[(IND) Temporary sales tax transactions (modified form)](https://technet.microsoft.com/en-us/library/jj664487\(v=ax.60\))

[(IND) Formula designer (form)](https://technet.microsoft.com/en-us/library/jj677983\(v=ax.60\))

[(IND) Calculate sales tax using the Invoice journal lines form](ind-calculate-sales-tax-using-the-invoice-journal-lines-form.md)

[(IND) Service codes (form)](https://technet.microsoft.com/en-us/library/jj664830\(v=ax.60\))

  


