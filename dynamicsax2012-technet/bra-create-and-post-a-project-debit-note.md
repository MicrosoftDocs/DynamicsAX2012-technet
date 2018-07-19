---
title: (BRA) Create and post a project debit note
TOCTitle: (BRA) Create and post a project debit note
ms:assetid: ed956e1a-25bf-47dd-aaa0-891b864b9833
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ916231(v=AX.60)
ms:contentKeyID: 50877512
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- create debit note
- debit notes
- debot note
- project debit note
audience: Application User
ms.search.region: Brazil
---

# (BRA) Create and post a project debit note 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can generate debit notes for projects that have a transaction type of **Expense**. You can generate a project debit note by using the project debit note proposal workflow. Before you can generate a debit note, you must set up a fiscal document type to use in project transactions. For more information, see [(BRA) Set up fiscal document types](bra-set-up-fiscal-document-types.md). You must also post an expense journal for the project.

## Post an expense journal

1.  Click **Project management and accounting** \> **Journals** \> **Expense**.

2.  Create an expense journal, and then in the **Name** field, select a journal name. Click **Lines**.
    
    –or–
    
    Select a journal, and then click **Lines**.

3.  In the **Project** and **Category** fields, select a project number and the category that the journal is posted for.

4.  In the **Worker** field, select the name of the employee who incurred the expense.

5.  In the **Description** field, select a description for the transaction.

6.  In the **Cost price** and **Sales price** fields, enter a cost price and a sales price.

7.  In the **Offset account type** field, select **Ledger**.

8.  In the **Offset account** field, select the account that the journal amount is posted to.

9.  Click **Post** \> **Post** to post the journal.

## Create and post a project debit note

Before you create a debit note proposal, you must set up a fiscal document type to use in project transactions and post an expense journal. For more information, see Post an expense journal.

1.  Click **Project management and accounting** \> **Common** \> **Project debit notes** \> **Project debit note proposals**.

2.  On the **Action Pane**, click **Debit note proposal**.

3.  In the **Project contract** field, select a project contract number for the debit notes.
    

    > [!NOTE]
    > <P>You can filter the debit notes by specifying criteria in the <STRONG>Project</STRONG>, <STRONG>Debit note date</STRONG>, <STRONG>Funding source</STRONG>, <STRONG>Reason code</STRONG>, <STRONG>Start date</STRONG>, and <STRONG>End date</STRONG> fields. After you select the filters, click <STRONG>Search</STRONG>.</P>



4.  Select the check box in the **Select** field for each debit note that is used to create the debit note proposal.

5.  Click **OK** to create the debit note proposal.

6.  Close the form.

7.  In the **Project debit note proposals** list page, select a debit note proposal, and then on the **Action Pane**, click **Post**.
    

    > [!NOTE]
    > <P>You can post a debit note proposal only if workflow is not enabled.</P>



8.  Click **OK** to post a debit note for the debit note proposal. In the **Project debit note proposals** list page, the status of the debit note proposal is updated to **Debit note issued**.

## Create and post a project debit note by using a workflow

Use the following procedure to create and post a project debit note proposal by using the project debit note proposal workflow. For more information, see [Create a workflow](create-a-workflow.md).


> [!NOTE]
> <P>You can post project debit notes by using the workflow only if your company uses workflows. Contact your Microsoft Dynamics AX system administrator to set up workflows.</P>



Before you create a debit note proposal, you must set up a fiscal document type to use in project transactions, and post an expense journal. For more information, see Post an expense journal.

1.  Click **Project management and accounting** \> **Common** \> **Project debit notes** \> **Project debit note proposals**.

2.  On the **Action Pane**, click **Debit note proposal**.

3.  In the **Project contract** field, select a project contract number for the debit notes to create a debit note proposal.
    

    > [!NOTE]
    > <P>You can filter the debit notes by specifying criteria in the <STRONG>Project</STRONG>, <STRONG>Debit note date</STRONG>, <STRONG>Funding source</STRONG>, <STRONG>Reason code</STRONG>, <STRONG>Start date</STRONG>, and <STRONG>End date</STRONG> fields. After you select the filters, click <STRONG>Search</STRONG>.</P>



4.  Select the check box in the **Select** field for each debit note that is used to create the debit note proposal.

5.  Click **OK** to create the debit note proposal.

6.  Close the form.

7.  In the **Project debit note proposals** list page, select a debit note proposal, and then on the **Action Pane**, click **Debit note proposals**. By default, the debit note proposal has a status of **Open**.

8.  Click **Submit** to submit the debit note proposal to the workflow process.

9.  Enter comments about the debit note proposal, and then click **Submit**. The status of the debit note proposal is updated to **Submitted**.

10. Click **Actions** \> **Approve** to approve the debit note. The status of the debit note proposal is updated to **Approved**.

11. Click **Actions** \> **Post**, and then enter comments to post the debit note proposal.

12. Click **Post**, and then in the **Narration** field, enter comments about the debit note proposal.

13. Click **OK** to post a debit note for the debit note proposal.

## See also

[(BRA) Project debit note proposals (list page)](https://technet.microsoft.com/en-us/library/jj923401\(v=ax.60\))

[(BRA) Debit note proposal (form)](https://technet.microsoft.com/en-us/library/jj923193\(v=ax.60\))

[(BRA) Cancel a project debit note](bra-cancel-a-project-debit-note.md)

[(BRA) About project debit notes](bra-about-project-debit-notes.md)

  


