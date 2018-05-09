---
title: (ESP) Make adjustments in the opening sheet
TOCTitle: (ESP) Make adjustments in the opening sheet
ms:assetid: 9c7abf48-1789-457a-a64c-ff8da1243b51
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh209433(v=AX.60)
ms:contentKeyID: 36058729
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Spain
- Opening sheet
---

# (ESP) Make adjustments in the opening sheet 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Legal entities in Spain can post special entries as **Opening** entries for the current period, while adapting their accounts to changes in accounting rules. When you close the entries for the previous fiscal year, you can create several lines by setting the **Type** field to **Opening**. You can then post the special opening entries for the current fiscal year.

Use this procedure to make adjustments in the opening sheet for the fiscal year.

1.  Click **General ledger** \> **Periodic** \> **Fiscal year close** \> **Opening sheets**.

2.  Press CTRL+N to create a new opening sheet.

3.  In the **Opening sheets** field, enter a code for the opening sheet.
    

    > [!NOTE]
    > <P>You can create several opening sheets for each year, but each must have a unique identifier in the <STRONG>Opening sheets</STRONG> field.</P>



4.  In the **Name** field, enter a name for the opening sheet.

5.  In the **Posting layer** field, select the posting layer for the transactions.

6.  In the **Type** field, select **Opening** to make adjustments for the entire year that were maintained separately from the daily postings in the last period of the year.
    

    > [!NOTE]
    > <P>If you select <STRONG>Opening</STRONG>, you must use the <STRONG>Opening fiscal period</STRONG> field on the <STRONG>General</STRONG> tab to specify the opening period to post to.</P>



7.  Click the **General** tab, and in the **From** and **To** fields, specify the period that the adjustments apply to.

8.  In the **Post** field, specify the posting date for the adjustments.

9.  Click **Opening accounts** to open the **Opening accounts** form.

10. Click **Load balances** to specify the main accounts to include to the opening sheet.

11. Click **OK** to attach the balances of selected ledger accounts to the selected opening sheet. The account balances for the selected ledger accounts are listed in the **Opening accounts** form.

12. Click **Post** to post all ledger account balances and adjustments to the opening sheet.

13. In the **Open** form, click **Post** to post the opening sheet.

14. Close the form to save your changes.

## See also

[Opening transactions (form)](https://technet.microsoft.com/en-us/library/aa572506\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

