---
title: Import and reconcile using advance bank reconciliation
TOCTitle: Import and reconcile using advance bank reconciliation
ms:assetid: 5615a135-0cbb-45de-a2e0-07ddcc4ebd4e
ms:mtpsurl: https://technet.microsoft.com/library/JJ729753(v=AX.60)
ms:contentKeyID: 49564919
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Import and reconcile using advance bank reconciliation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In Microsoft Dynamics AX, you can import electronic bank statements and automatically reconcile bank statements with bank documents.


> [!NOTE]
> <P>You can only import electronic bank statements if you have set up Microsoft Dynamics AX to import bank statements. For more information, see <A href="set-up-advanced-bank-reconciliation-import.md">Set up advanced bank reconciliation import</A>.</P>



## Import a bank statement

1.  Click **Cash and bank management** \> **Setup** \> **Cash and bank management parameters**.

2.  Click the **Bank reconciliation** link, and then select which options to use for advance bank reconciliation.

3.  Click the **Number sequences** link, and then select a number sequence for **Reconcile ID**, **Statement ID**, and **Download ID**.
    
    For more information, see [Cash and bank management parameters (form)](https://technet.microsoft.com/library/aa591289\(v=ax.60\))

4.  Click **Cash and bank management** \> **Setup** \> **Bank reconciliation** \> **Bank statement format**.

5.  Click **New** to create a new bank statement format.

6.  In the **Inbound port** field, select the inbound port that was created during the setup of advanced bank reconciliation import.

7.  Click **Cash and bank management** \> **Common** \> **Bank accounts**. Select a bank account. On the **Action Pane**, click **Edit**. On the **Reconciliation** FastTab, select the **Advanced bank reconciliation** check box.
    
    For more information, see [Bank accounts (form)](https://technet.microsoft.com/library/aa587660\(v=ax.60\)).

8.  In the **Bank accounts** form, click **Bank statements**
    

    > [!NOTE]
    > <P>The <STRONG>Bank reconciliation</STRONG> option is only available if the <STRONG>Advanced bank reconciliation</STRONG> check box is selected in the <STRONG>Bank accounts</STRONG> form on the <STRONG>Reconciliation</STRONG> FastTab.</P>



9.  In the **Bank statements** form, click **Import statement** to open the **Import bank statements** form.
    
    For more information, see [Import bank statements (form)](https://technet.microsoft.com/library/jj729765\(v=ax.60\)).

10. After the bank statement is imported, click **Validate** to validate the bank statement.
    

    > [!NOTE]
    > <P>Only bank statements with a status of <STRONG>Validated</STRONG> can be reconciled.</P>



11. In the **Bank statements** form, select the bank statement, and then click **Edit** to open the **Bank statement** form to view all the bank statement lines that were imported.

12. To distribute a bank statement line to more than one account, you can select the line and then click **Distribute amounts** to open the **Accounting distributions** form.
    
    For more information, see [Accounting distributions (form)](https://technet.microsoft.com/library/hh209296\(v=ax.60\)).

## Reconcile a bank statement using advanced bank reconciliation

After an electronic bank statement has been imported and validated in the **Bank statements** form, the bank statement can now be reconciled using the **Bank reconciliation worksheet** form.

1.  Click **Cash and bank management** \> **Journals** \> **Bank reconciliation**.
    
    –or–
    
    Click **Cash and bank management** \> **Common** \> **Bank accounts**. On the **Action pane**, in the **Reconcile** group, click **Bank reconciliation**.
    

    > [!NOTE]
    > <P>The <STRONG>Bank reconciliation</STRONG> option is only available if the <STRONG>Advanced bank reconciliation</STRONG> check box is selected in the <STRONG>Bank accounts</STRONG> form on the <STRONG>Reconciliation</STRONG> FastTab.</P>



2.  Click **New** to create a new bank reconciliation journal.

3.  In the **Bank account** field, select the bank account that the bank statement was imported for.

4.  Click **Lines** to open the **Bank reconciliation worksheet** form, where you can reconcile bank statement lines with bank document lines.

5.  To match a bank statement line and a bank document line, select the bank statement line from the **Open statement lines** by selecting the check box. Select the bank document line to match to it, by selecting the check box for the bank document line in the **Open bank documents** group.

6.  Click **Match**.
    
    When a bank statement line and a bank document line are matched, the lines will move to the **Matched statement lines** section on the **Matched documents** FastTab.
    

    > [!NOTE]
    > <P>To unmatch the matched lines and move them back to <STRONG>Open statement lines</STRONG> and <STRONG>Open bank documents</STRONG>, select the lines and click <STRONG>Unmatch</STRONG>.</P>



7.  In the **Bank reconciliation worksheet** form, on the **Open documents** FastTab, you can view **Open statement lines** and **Open bank documents** that are available to reconcile.

8.  On the **Matched documents** FastTab, you can view the bank statement lines and the bank document lines that have been reconciled.

9.  On the **Line details** FastTab, you can view the details of a line that is selected on the **Open statement lines** FastTab.

10. Click **Run matching rules** to have bank statement lines and bank document lines be matched up according to a set of criteria that are set up in the **Reconciliation matching rules** form and the **Reconciliation matching rule sets** form.
    
    For more information, see [Set up bank reconciliation matching rules](set-up-bank-reconciliation-matching-rules.md).
    
    To run the matching rules during the import process, select the **Reconcile after import** check box in the **Bank accounts** form. If you select this check box, the bank statement will be imported and validated, a new bank reconciliation journal will be created, and the selected matching rule set will be run.
    
    For more information, see [Bank accounts (form)](https://technet.microsoft.com/library/aa587660\(v=ax.60\)).

11. When you have finished matching up bank documents lines and bank statement lines, click **Reconcile** to post the bank reconciliation.

  


