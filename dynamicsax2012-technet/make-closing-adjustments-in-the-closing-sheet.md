---
title: Make closing adjustments in the closing sheet
TOCTitle: Make closing adjustments in the closing sheet
ms:assetid: 23cf0baa-4e01-4e56-8b69-e9f8cb39b54d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa496805(v=AX.60)
ms:contentKeyID: 36056184
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Make closing adjustments in the closing sheet 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

1.  Click **General ledger** \> **Periodic** \> **Fiscal year close** \> **Closing sheet**.

2.  Press CTRL+N to create a line for a closing sheet in a particular posting layer for the fiscal year that is being closed. The posting layers are:
    
      - **Current**
    
      - **Operations**
    
      - **Tax**
    
    You can make several closing sheets for each year, but each must have a unique identifier in the **Closing sheet** field.

3.  Enter or select an identifier and name for the closing sheet.

4.  Select a value in the **Type** field. To make closing adjustments for the entire year that are kept separate from the daily postings in the last period of the year, select **Closing**.
    

    > [!NOTE]
    > <P>If you select <STRONG>Closing</STRONG>, you must use the <STRONG>Closing fiscal period</STRONG> field on the <STRONG>General</STRONG> tab to specify which closing period to post to.</P>



5.  On the **General** tab, specify the period that the adjustments apply to.

6.  In the **Post** field, specify the posting date for the adjustments.

7.  Close the form.

8.  Click **General ledger** \> **Reports** \> **Base data** \> **Chart of accounts**.

9.  On the **Main accounts** FastTab, click **New** to open the **Main accounts - chart of accounts: %1** form.

10. Select a main account to include in the closing sheet.

11. On the **General** FastTab, in the **Close** field, select an option to determine which corresponding field in the **Closing accounts** form the balance of the main account is transferred into. The options are:
    
      - **Result**
    
      - **Balance**
    
      - **Capital**

12. Close the form.

13. Attach the balances of selected ledger accounts to the selected closing sheet in the **Close** form. (Click **General ledger** \> **Periodic** \> **Fiscal year close** \> **Closing sheet**. Select a closing sheet and click **Closing accounts**.)

14. Click **Load balances**.

15. Select the accounts to add to the closing sheet.

16. Select the **Delete existing accounts** check box to delete existing accounts and then click **OK**. The balances of the selected accounts will be displayed in the **Closing accounts** form.

17. Examine the transferred balances and make adjustments if they are required. When the transfers and adjustments are balanced for an account, select the account.

18. Click **Post** to post the balances and adjustments to the closing sheet.

## See also

[Fiscal year closing checklist](fiscal-year-closing-checklist.md)

[Close (form)](https://technet.microsoft.com/en-us/library/aa589239\(v=ax.60\))

  


