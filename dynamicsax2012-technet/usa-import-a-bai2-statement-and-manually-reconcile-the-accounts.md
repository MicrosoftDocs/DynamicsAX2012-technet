---
title: (USA) Import a BAI2 statement and manually reconcile the accounts
TOCTitle: (USA) Import a BAI2 statement and manually reconcile the accounts
ms:assetid: 46c32624-ed17-4f2e-a7fe-569778f102ac
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242387(v=AX.60)
ms:contentKeyID: 36056905
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- import
- USA
- BAI2
- reconcile
---

# (USA) Import a BAI2 statement and manually reconcile the accounts 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Bank Administration Institute (BAI) file format is used to electronically transmit transaction data from a bank to an organization. Bank Administration Institute version 2 (BAI2) splits the payment amount into separate invoice references and corresponding payments. You can use this format to do the following tasks:

  - Analyze and account for all incoming receipts that include interest, and for outgoing payments that include bank charges.

  - Create bank reconciliation statements.

  - Create and estimate cash flow or funds flow. This includes services such as cash concentration and zero-balance accounting.

You can import the BAI2 statement and validate the check entries against the bank transactions. Then you can manually correct the discrepancies in the amounts of bank cash balances and your accounts, and post the reconciled transactions to the bank account from the bridging account. A bridging account is the ledger account that holds check payment transactions that are pending manual approval before they are reconciled with the bank statement.

## Set up the bank reconciliation import process

Before you can view service operations, you must select the **Advanced bank reconciliation** check box in the **Bank accounts** form for a bank account.


> [!NOTE]
> <P>The following steps should be performed by system administrators who have knowledge of the Application Object Tree (AOT). For more information about these steps, see <A href="https://technet.microsoft.com/en-us/library/hh208821(v=ax.60)">AIF inbound ports (form)</A>.</P>



1.  In the AOT, under the **Resources** node, locate the BAI2 files. These files translate the electronic bank statements from their original format to a format that Microsoft Dynamics AX can use.

2.  Right-click the **BAI2CSV\_to\_BAI2XML\_xslt\_NA** file, and then click **Open**.

3.  In the **Preview** form, select **XML document** in the **File type** field.

4.  Click **Export** to generate XSLT templates and save the templates.

5.  Close the **Preview** form.

6.  In the AOT, right-click the **BAI2XML\_to\_BAI2AIF\_xslt\_NA**file, and then click **Open**.

7.  In the **Preview** form, select **XML document** in the **File type** field.

8.  Click **Export** to generate XSLT templates and save the templates.

## Set up Application Integration Framework (AIF)

Before you can receive the BAI2 statement electronically, you must register custom services and adapters, manage operations and inbound transforms, and activate inbound ports.

1.  Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Inbound ports**.

2.  Click **New** to create a new inbound port.

3.  In the **Port name** and **Description** fields, enter BAI2 for the name and description of the inbound port.

4.  In the **Adapter** field, select **File system adapter** as the adapter name.

5.  In the **URI** field, enter a path for receiving electronic data.

6.  On the **Service contract customizations** FastTab, click **Service operations** to open the **Select service operations** form.

7.  Double-click service operations such as **BankStmtISOService.Create**, **BankStmtISOService.Delete**, **BankStmtISOService.Find**, and **BankStmtISOService.Read** to move them from the **Remaining service operations** list to the **Selected service operations** list.

8.  Close the **Select service operations** form.

9.  On the **Processing options** FastTab, select the **Transform all requests** check box to include inbound transforms.

10. Click **Inbound transforms** to open the **Inbound transforms** form.

11. Click **Manage transforms** to open the **Manage transforms** form, and then click **Yes** when the message is displayed.

12. Click **New** to create a transform. Enter csv2xml in the **Name** field.

13. Click **Load** and select the **BAI2CSV\_to\_BAI2XML\_xslt\_NA** template that you saved in the previous procedure.

14. Click **New** to create a transform. Enter xml2aif in the **Name** field.

15. Click **Load** and select the **BAI2XML\_to\_BAI2AIF\_xslt\_NA** template that you saved in the previous procedure.

16. Close the form to save the changes and return to the **Inbound ports** form.

17. Click **New** and select **csv2xml** in the **Transform name** field.

18. Click **New** and select **xml2aif** in the **Transform name** field.

19. Click **Move up** or **Move down**, if you need to, so that the transform for the **BAI2CSV\_to\_BAI2XML\_xslt\_NA** template is before the transform for the **BAI2XML\_to\_BAI2AIF\_xslt\_NA** template.

20. Close the form to save the changes, and then close the **Inbound ports** form.

## Register the services and adapters

To register the services and adapters, use the **Initialization checklist**.

  - In Microsoft Dynamics AX 2012: Click **System administration** \> **Setup** \> **Checklists** \> **Initialization checklist**. Click **Initialize system** \> **Set up system parameters**.

  - In Microsoft Dynamics AX 2012 R2: Click **System administration** \> **Setup** \> **Checklists** \> **Partition initialization checklist**. Click **Partition initialization checklist** \> **Set up system parameters**.

## Set up a method of payment

Use the **Methods of payment - vendors** form to select the bridging account to use to post the check payment transactions. When these transactions are manually reconciled with the BAI2 statement, the transactions are posted to the bank account.

1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Methods of payment**.

2.  Click **New** to create a method of payment for checks. For more information, see [Set up a method of payment for checks](set-up-a-method-of-payment-for-checks.md).

3.  On the **General** FastTab, in the **Account type** field, select the **Bank** account type.

4.  In the **Payment account** field, select the bank account from which the checks are issued.

5.  Select the **Bridging posting** check box to post the payment transaction to a bridging account and then to the corresponding bank account.

6.  In the **Bridging account** field, select the bridging account.

## Set up the BAI2 statement import method

Use the **Import methods for account statements** form to select the import format, bank account, bridging account, and inbound port to use to import BAI2 statements.

1.  Click **General ledger** \> **Setup** \> **Journals** \> **Methods of importing account statements**.

2.  Click **New** to create a method to import a BAI2 statement. For more information, see [Methods of importing account statements (form)](https://technet.microsoft.com/en-us/library/aa618250\(v=ax.60\)).

3.  In the **Method of import** field, enter a method to import the BAI2 statement.

4.  In the **Inbound port** field, select the inbound port for BAI2.

5.  In the **Import format** field, select the **BAI2 (NA)** import format.

## Import BAI2 and reconcile the accounts

Use the **Journal voucher** form to import the BAI2 statement and manually reconcile the discrepancies with the payments that are generated for checks. For more information, see [Make a payment by check](make-a-payment-by-check.md).

1.  Click **General ledger** \> **Journals** \> **General journal**.

2.  Click **New** to create a line.

3.  In the **Name** field, select a journal.

4.  Click **Lines** to open the **Journal voucher** form.

5.  Click **Functions** \> **Import account statement (transactions)**, and then select the method of import in the **Method of import** field.

6.  Click **OK** to import the BAI2 statement.

7.  In the **File name** field, specify the path and file name for the BAI2 statement text file.

8.  Click **OK** to import and transfer the reconciled transactions and the transactions that have discrepancies to the journal lines.

9.  Click **Post** \> **Post** to post the reconciled transactions from the bridging account to the bank account. If the transactions are not reconciled, press click **New** to create a line.

10. In the **Account type** field, select the **Bank** account type. In the **Credit** field, enter an amount to reconcile the transaction.

11. In the **Offset account type** field, select the **Ledger** offset account type. In **Offset account** field, select the bridging account.

12. Click **Post** to post the reconciled transaction.

13. Use the **Bank statement import validation** form to view the reconciled transactions. Click **Cash and bank management** \> **Inquiries** \> **Bank statement import validation**.

## See also

[Journal voucher - General journal (form)](https://technet.microsoft.com/en-us/library/aa591466\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

