---
title: (RUS) Generate an expense account line using the Copy from sources function
TOCTitle: (RUS) Generate an expense account line using the Copy from sources function
ms:assetid: 51f9963d-250e-4e4d-8d81-ed08deef6783
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ665381(v=AX.60)
ms:contentKeyID: 49387469
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Generate an expense account line using the Copy from sources function 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts payable** \> **Common** \> **Advance holders** \> **Advance reports**.

2.  Press CTRL+N and enter information in the required fields.

3.  In the lower pane, click the **Lines** tab.

4.  Click **Functions**, and then select **Copy from sources** to open the **Create lines - Advance report** form. The form displays a list of credit transactions posted by the advance holder.
    

    > [!NOTE]
    > <P>In the upper pane, the <STRONG>Source type</STRONG> field displays the identification type of the original document. The source for type <STRONG>Facture</STRONG> is the purchase order, and the source for type <STRONG>Accounts payable</STRONG> is the vendor transaction. The <STRONG>Amount currency</STRONG>, <STRONG>Currency</STRONG>, and <STRONG>Amount</STRONG> fields indicate the total amount in the secondary currency of the transaction, the currency code, and the amount in the company's standard currency. In the lower pane, the <STRONG>Number</STRONG> field displays the number of the vendor's facture. The <STRONG>Description</STRONG> field displays the item name. The <STRONG>Currency</STRONG>, <STRONG>Amount currency</STRONG>, and <STRONG>Sales tax amount in currency</STRONG> fields display the voucher currency, the line amount, and the sales tax amount respectively.</P>



5.  In the upper pane, select the **Mark** check box to confirm the documents to be copied.

6.  Click **OK** to transfer the expense data to the advance report.
    
    In the **Document number** field of the advance report, the number of the source facture is copied if the **Line Type** field of the advance report is set to **Facture**, or the number of the transaction is copied if the **Line Type** field of the advance report is set to **Vendor**.
    

    > [!NOTE]
    > <P>You cannot edit the <STRONG>Amount</STRONG>, <STRONG>Currency</STRONG>, and <STRONG>Ledger account</STRONG> fields.</P>



7.  Click **Post** to post the report.

8.  Press CTRL+S or close the form.

## See also

[(RUS) Generate and post advance report lines manually](rus-generate-and-post-advance-report-lines-manually.md)

[(RUS) Advance reports (form)](https://technet.microsoft.com/en-us/library/jj733237\(v=ax.60\))

[(RUS) Create lines - Advance report (form)](https://technet.microsoft.com/en-us/library/jj733226\(v=ax.60\))

  


