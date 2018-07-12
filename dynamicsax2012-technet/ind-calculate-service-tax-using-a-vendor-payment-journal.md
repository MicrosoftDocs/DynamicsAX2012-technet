---
title: (IND) Calculate service tax using a vendor payment journal
TOCTitle: (IND) Calculate service tax using a vendor payment journal
ms:assetid: 794e811a-1648-49d1-a997-05f97af1d254
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677923(v=AX.60)
ms:contentKeyID: 49385872
ms.date: 05/06/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.LedgerJournalTransVendPaym
- Forms.LedgerJournalTable
audience: Application User
ms.search.region: India
---

# (IND) Calculate service tax using a vendor payment journal 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012_

Use the **Payment journal** form to calculate the service tax for a vendor. You can specify the service code and service category for vendors and foreign vendors before you post the journal.

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Click **New** to create a journal, and then enter the journal details.

3.  Click **Lines** to open the **Journal voucher** form. For more information, see [Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md).

4.  On the **Overview** tab, enter the details of the journal.

5.  In the **Consignment note number** field, enter the consignment note number for a goods transport agency (GTA) vendor.

6.  On the **General** tab, in the **Sales tax group** field, select the service tax group that you have created for the vendor.

7.  In the **Item sales tax group** field, select the item tax group that you have created for the vendor. The sales tax group and the item sales tax group for a journal line must contain tax codes that have a tax type of **Service tax**.

8.  On the **Tax information** tab, in the **Company information** field group, you can modify the legal entity name and address.

9.  In the **Service** field group, in the **STC number** field, select the service tax code (STC) number of the legal entity. The ledger accounts for posting the service tax amounts are identified based on the STC number.

10. In the **Service code** field, select the service code that is attached to goods of the type **Service**.
    

    > [!NOTE]
    > <P>In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: The accounting code for the service is updated in the <STRONG>Accounting code</STRONG> field based on the service code that you select. For more information, see <A href="ind-set-up-service-codes-for-service-goods.md">(IND) Set up service codes for service goods</A>.</P>



11. Depending on the version that you are using, do one of the following:
    
      - In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: In the **Service category** field, select one of the following options to specify the service category for the journal line:
        
          - **Inward** – Select this option when you purchase goods from a vendor.
        
          - **Inter unit or input** – Select this option when you transfer goods between two units within your legal entity, or from the legal entity to a subcontractor for additional processing. For example, you can select this option when the goods are manufactured in one unit, and then transferred to the packing unit of your legal entity.
        
          - **Others** – Select this option for other service categories for which input tax is paid. The input tax amount for this category is posted to the expense account instead of the recoverable account or the interim recoverable account.
    
      - In Microsoft Dynamics AX 2012 R2: In the **GTA service category** field, select one of the following options to specify the category of GTA service:
        
          - **Inward** – Select this option when you purchase goods from a vendor.
        
          - **Outward - inter unit/input** – Select this option when you transfer goods between two units within your legal entity, or from the legal entity to a subcontractor for additional processing.
        
          - **Others** – Select this option for all other categories of GTA services.

12. Click **Sales tax** to view the calculation of the service tax in the **Sales tax transactions** form.

13. Click **Formula designer** to view the calculation expression for each tax code. Close the form.

14. Close the **Sales tax transactions** form.

15. Validate and post the journal voucher. The service tax amounts are debited from the interim tax recoverable accounts and from the interim tax payable accounts for the vendor.
    

    > [!NOTE]
    > <P>If the <STRONG>Tax recoverable on full payment</STRONG> check box is selected on the <STRONG>Sales tax</STRONG> tab in the <STRONG>General ledger parameters</STRONG> form, and you make the full payment of the invoice amount, the full amount of service tax that is calculated on the invoice is reversed from interim tax recoverable accounts to tax recoverable accounts. The service tax amount is reversed proportionately on the partial payments.</P>



## See also

[(IND) Journal voucher - Vendor payment journal (modified form)](https://technet.microsoft.com/en-us/library/jj664794\(v=ax.60\))

[(IND) Temporary sales tax transactions (modified form)](https://technet.microsoft.com/en-us/library/jj664487\(v=ax.60\))

[(IND) Formula designer (form)](https://technet.microsoft.com/en-us/library/jj677983\(v=ax.60\))

[(IND) Service codes (form)](https://technet.microsoft.com/en-us/library/jj664830\(v=ax.60\))

  


