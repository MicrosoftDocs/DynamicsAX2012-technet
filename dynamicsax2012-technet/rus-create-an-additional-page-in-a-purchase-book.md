---
title: (RUS) Create an additional page in a purchase book
TOCTitle: (RUS) Create an additional page in a purchase book
ms:assetid: 3fe92961-9f5e-4b18-a8dd-ed00ac87fff6
ms:mtpsurl: https://technet.microsoft.com/library/JJ665315(v=AX.60)
ms:contentKeyID: 49387404
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Create an additional page in a purchase book 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



When you correct transactions for a closed tax period, an additional page is created in the closed purchase book to represent the tax period of the adjustment. Corrected factures are displayed in the new page in the purchase book.

The additional page contains information about purchase book totals at the end of the corrected period, including previous additional pages, corrected factures, and other registered changes.

1.  Click **General ledger** \> **Journals** \> **General journal**.

2.  Press CTRL+N to create a new line, and enter the required details.

3.  In the **Account type** field, select **Ledger**.

4.  In the **Account** field, select the ledger account number.
    

    > [!NOTE]
    > <P>The ledger account must be specified with the <STRONG>Sales tax</STRONG> posting type.</P>



5.  In the **Debit** field, enter the corrected debit amount.

6.  In the **Offset account type** field, select **Ledger**.

7.  In the **Offset account** field, select the ledger offset account number.

8.  Click the **General** tab. In the **Sales tax code** field, select the sales tax code for the transaction.
    

    > [!NOTE]
    > <P>The ledger account specified in the <STRONG>Account</STRONG> field on the <STRONG>Overview</STRONG> tab must belong to the accounting posting group of the selected sales tax code.</P>



9.  Click **Post** \> **Post** to post the journal voucher.

10. In the **Journal voucher** form, click **Functions** \> **Purchase book** to open the **Update facture** form.

11. In the **Counteragent** field, select the vendor.

12. In the **Date of the registration** field, select the registration date of the corrected facture.

13. In the **Facture** field, select the corrected facture from the vendor factures page, as specified in the **Counteragent** field.

14. In the **Facture date** field, view the facture creation date.
    

    > [!NOTE]
    > <P>The corrected book code is determined by the date of the corrected period. Previous period modifications are registered in the book for the current period. These modifications are displayed on additional pages that are added to the books for previous periods.</P>



15. In the lower section of the form, on the **Invoice** tab, use the **To facture** check box to select the invoice or invoices for the facture.
    

    > [!NOTE]
    > <P>If you do not want to create a facture for a particular invoice line, clear the <STRONG>To facture</STRONG> check box on the <STRONG>Invoice lines</STRONG> tab.</P>



16. Click **Posting** \> **Update facture** to post the facture journal.
    

    > [!NOTE]
    > <P>The created facture is updated in the <STRONG>Facture journal</STRONG> form. After VAT is processed and the purchase book lines are refreshed, the corrected facture is displayed in the <STRONG>Purchase book lines</STRONG> form. The <STRONG>Correction</STRONG> field group displays the details about the corrected facture.</P>



17. Click **Accounts payable** \> **Periodic** \> **Purchase book** \> **Purchase books journal** to open the **Purchase books journal** form.

18. Select the additional page and click **Print** \> **Print additional list** to print the page.
    

    > [!NOTE]
    > <P>Corrected purchase book lines are included in the additional pages. Other additional pages are created if other tax periods were corrected in the current reporting period.</P>
    > <P>The purchase book can be printed in a Microsoft Office Excel template.</P>



## See also

[(RUS) Purchase books journal (form)](https://technet.microsoft.com/library/jj853172\(v=ax.60\))

[(RUS) Facture journal (form)](https://technet.microsoft.com/library/jj923567\(v=ax.60\))

  


