---
title: Resolve invoice totals invoice matching discrepancies
TOCTitle: Resolve invoice totals invoice matching discrepancies
ms:assetid: 812b85c2-b2b9-462f-a16a-5bb699ab840f
ms:mtpsurl: https://technet.microsoft.com/library/Hh292599(v=AX.60)
ms:contentKeyID: 36655936
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Resolve invoice totals invoice matching discrepancies 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this information to identify and resolve matching discrepancies between expected and actual totals on invoices for purchase orders. You can use the **Pending vendor invoices** list page to identify invoices that have been entered and saved, but that are not yet approved to be posted.


> [!NOTE]
> <P>Use this procedure if the <STRONG>Match invoice totals</STRONG> check box is selected in the <STRONG>Accounts payable parameters</STRONG> form.</P>



After you have identified the discrepancy, you might have to contact the vendor if you think that the information on the invoice is incorrect. Depending on the resulting agreement with the vendor, you can do any of the following tasks:

  - Accept the price difference and post the invoice with matching discrepancies.

  - Revise the invoice amount to the expected amount and post the invoice.

  - Request a full credit from the vendor and a new, corrected invoice.

<!-- end list -->

1.  Click **Accounts payable** \> **Common** \> **Vendor invoices** \> **Pending vendor invoices**.

2.  Double-click a saved vendor invoice that has corresponding purchase order.

3.  On the **Action Pane**, on the **Review** tab, click **Matching details**.

4.  If a warning icon is displayed next to the **Invoice amount** field, click the **…** button.

5.  In the **Invoice totals matching details** form, review the expected and actual total amounts. Make a note of the amounts that have a warning icon displayed next to them. Close the form.

6.  In the **Invoice matching details** form, to revise the invoice amounts to the expected amounts, change the amounts that have warning icons displayed next to them.

7.  To accept the invoice totals variances and post the invoice with matching discrepancies, select the **Approve posting with matching discrepancies** check box, enter a comment, and then click **OK**.
    

    > [!NOTE]
    > <P>If the <STRONG>Post invoice with discrepancies</STRONG> field in the <STRONG>Accounts payable parameters</STRONG> form is set to <STRONG>Allow with warning</STRONG>, these fields are not available and you can skip this step.</P>



8.  In the **Vendor invoice** form, on the **Action Pane**, click **Post**.

9.  In the **Select the posting settings** dialog box, select print settings, and then click **Post**.
    

    > [!NOTE]
    > <P>Alternatively, you can submit the invoice to be posted by using batch processing.</P>



## See also

[Record the receipt of vendor invoices and match against received quantities](record-the-receipt-of-vendor-invoices-and-match-against-received-quantities.md)

[Invoice matching details (form)](https://technet.microsoft.com/library/hh209713\(v=ax.60\))

[Invoice totals matching details (form)](https://technet.microsoft.com/library/hh209476\(v=ax.60\))

[Vendor invoice (form)](https://technet.microsoft.com/library/hh209644\(v=ax.60\))

  


