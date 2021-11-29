---
title: (RUS) Post a statement for return transactions that are processed during a different shift
TOCTitle: (RUS) Post a statement for return transactions that are processed during a different shift
ms:assetid: 530b359c-4901-47fb-a242-fb72a776b860
ms:mtpsurl: https://technet.microsoft.com/library/Dn716018(v=AX.60)
ms:contentKeyID: 62200264
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailStatementTable
- Forms.RetailStatementJour
audience: Application User
ms.search.region: Russia
---

# (RUS) Post a statement for return transactions that are processed during a different shift 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to post a statement for return transactions that are processed during a different shift. You can then verify the details of the return transactions in the posted statement.

1.  Click **Retail** \> **Journals** \> **Open statements**.

2.  Double-click a statement or click **New statement** to create a statement. For more information, see “Create and calculate the statement” in [Create and post a statement](create-and-post-a-statement.md).

3.  In the **Statements** form, on the **Line details** FastTab, on the **Amounts** tab, in the **Returned amount** field, verify the amount of the cash return in a different shift.

4.  Post the statement. For more information, see “Post a statement” in [Create and post a statement](create-and-post-a-statement.md). When you post the statement, Microsoft Dynamics AX verifies the information, such as the number, amount, currency, and cash office for the disbursement slip for the return transaction against the information that is available in the **Cash transaction** form.
    

    > [!NOTE]
    > <P>You cannot post a statement that contains a return transaction for which:</P>
    > <UL>
    > <LI>
    > <P>the cash transaction that is associated with the disbursement slip is not posted.</P>
    > <LI>
    > <P>the payment transaction that is associated with the disbursement slip is settled.</P></LI></UL>



5.  Close the forms.

6.  Click **Retail** \> **Inquiries** \> **Posted statements**.

7.  In the upper pane, select a posted statement.

8.  In the lower pane, select a line, and then on the **Amounts** tab, in the **Returned amount** field, verify the returned amount.

9.  In the lower pane, click **Transactions** \> **Payment transactions** to open the **Payment transactions** form.

10. On the **General** FastTab, in the **Order number** field, verify the cash disbursement slip number. If the transaction was not included in the posted statement or if the disbursement slip number for the cash return is not correct, click **Transactions** \> **Select another disbursement slip** to modify the disbursement slip number. Close the **Payment transactions** form.

11. In the **Statement journal** form, click **Inquiries** \> **Transactions** to open the **Transactions** form, where you can verify the details about the posted transaction. The fields on the **Fiscal memory data** FastTab do not contain a value, and are not available for a return transaction that is processed during a different shift.

## See also

[(RUS) Set up Microsoft Dynamics AX to process returns during a different shift](rus-set-up-microsoft-dynamics-ax-to-process-returns-during-a-different-shift.md)

[View posted statements](view-posted-statements.md)

  


