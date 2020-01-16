---
title: (IND) Post service tax transactions by using a customer payment journal
TOCTitle: (IND) Post service tax transactions by using a customer payment journal
ms:assetid: 868ef98b-c0b4-4a8f-b80d-c6934c217c1b
ms:mtpsurl: https://technet.microsoft.com/library/JJ678011(v=AX.60)
ms:contentKeyID: 49385972
author: Khairunj
ms.date: 05/06/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.LedgerJournalTransCustPaym
- Forms.LedgerJournalTable
- Forms.TaxTmpWorkTrans
audience: Application User
ms.search.region: India
---

# (IND) Post service tax transactions by using a customer payment journal 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012_

Use the **Payment journal** form to create and post service tax transactions that you receive from customers. You can specify the service code and the service category for each journal line before you post the journal.

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Select or create a journal, and then click **Lines** to create a journal line. For more information, see [Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md).

3.  In the **Journal voucher** form, on the **Tax information** tab, in the **STC number** field, select the Service Tax Code (STC) number of the legal entity.
    

    > [!NOTE]
    > <P>If you have associated an STC number with the address of the legal entity, the <STRONG>STC number</STRONG> field is updated with that STC number. The ledger accounts for posting the service tax amounts are identified by the STC number.</P>



4.  In the **Service code** field, select the service code that is associated with the item of type **Service**.
    

    > [!NOTE]
    > <P>In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: The accounting code for the service is updated in the <STRONG>Accounting code</STRONG> field based on the service code that you select. For more information, see <A href="ind-set-up-service-codes-for-service-goods.md">(IND) Set up service codes for service goods</A>.</P>



5.  In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: In the **Service category** field, select one of the following options to indicate the service category for the journal line:
    
      - **Inward** – Select this option when you purchase goods from a vendor.
    
      - **Inter unit or input** – Select this option either when you transfer goods between two units within your legal entity, or when you transfer goods from the legal entity to a subcontractor for additional processing. For example, you can select this option when the goods are manufactured in one unit and then transferred to the packing unit of your legal entity.
    
      - **Others** – Select this option for other service categories for which input tax is paid. The input tax amount for this category is posted to the expense account instead of the recoverable account or the interim recoverable account.

6.  On the **General** tab, in the **Sales tax group** and **Item sales tax group** fields, update the sales tax group and item sales tax group for the goods. The sales tax group and the item sales tax group for a journal line must contain tax codes that have a tax type of **Service tax**.

7.  Click **Sales tax** to open the **Sales tax transactions** form, where you can view the calculated service tax for the journal.

8.  Close the **Sales tax transactions** form.

9.  Post the journal.

## See also

[(IND) Journal voucher - Customer payment journal (modified form)](https://technet.microsoft.com/library/jj664751\(v=ax.60\))

[(IND) Temporary sales tax transactions (modified form)](https://technet.microsoft.com/library/jj664487\(v=ax.60\))

[(IND) Service codes (form)](https://technet.microsoft.com/library/jj664830\(v=ax.60\))

  


