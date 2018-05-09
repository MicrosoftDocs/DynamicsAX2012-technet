---
title: Print periodic customer account statements
TOCTitle: Print periodic customer account statements
ms:assetid: 896a59aa-e767-4bdb-ad0a-5a4c0433e076
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg242856(v=AX.60)
ms:contentKeyID: 36966733
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- statements
- centralized
- statement
---

# Print periodic customer account statements 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the information in this topic to create statements that you can send to customers. Each statement can include information about the current, past, or future balance of the customer account. The statement can also include transaction activity for the time period that the statement covers.

To improve performance when you run statements for many customers at the same time, use one or more of the following options:

  - Use batch processing. By moving the processing to a server, report performance can improve.

  - Apply range restrictions to limit the number of records in each batch. Performance can be improved by submitting multiple smaller batches to be processed at the same time on different servers, instead of submitting one large batch.

  - You can select the **Only open** check box to include only open transactions, instead of all transactions, for each customer.

  - You can select the **Balance other than zero** check box to avoid printing statements for customers who have a balance of 0.00.

Centralized statements are customer statements that are sent from one legal entity on behalf of other legal entities in your organization. If your organization uses centralized statements, make sure that you are logged on to the legal entity for statements before you set up or create statements.

## Set up customer accounts for customer statements

For each customer, verify these prerequisites before you print that customer's statements for the first time. To print customer statements that include transactions from multiple legal entities, you must map the customer accounts to the corresponding customers in the other legal entities. Either use the same combination of party ID and legal entity for the customer accounts in all the affected legal entities, or include the customer accounts in an organization hierarchy that is used by all the legal entities that are affected. For more information, see [Merge party IDs for customer accounts across multiple legal entities](merge-party-ids-for-customer-accounts-across-multiple-legal-entities.md).

1.  Switch to the legal entity that you use to create centralized customer statements.

2.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

3.  Double-click a customer account.

4.  In the **Customers** form, on the **Action Pane**, click **Edit**.

5.  On the **Miscellaneous details** FastTab, in the **Account statement** field, select a value if you want to print statements for selected customers, based on the value in this field. For example, to print quarterly statements, you can enter a range of transaction dates for the appropriate quarter and select all customers who have a value of **Quarter** in this field.

6.  If your legal entity prints centralized statements, and your customer accounts are not included in an organization hierarchy, right-click the name of the customer, and then select **View details**. In the **Party** form, view the value in the **Party ID** field. If you want this customer to receive a single statement that includes transactions from multiple legal entities in your organization, follow these steps:
    
    1.  Click the **Relationships** FastTab.
    
    2.  Verify that the customer account for each legal entity is listed.
    
    3.  If a customer account is missing, merge the customer accounts. For more information, see [Merge party IDs for customer accounts across multiple legal entities](merge-party-ids-for-customer-accounts-across-multiple-legal-entities.md).

## Create and print periodic customer statements for a single legal entity

Use this procedure to create and print customer statements periodically. Before you begin, switch to the legal entity that you are printing statements for.

1.  Click **Accounts receivable** \> **Reports** \> **External** \> **Customer account statement**.

2.  On the **General** tab, select the range of dates for which transaction activity is included on the report. For more information, see [Customer account statement report (CustAccountStatementExt)](customer-account-statement-report-custaccountstatementext.md).

3.  Select other options for statement criteria. For more information about these options, see [Customer account statement report (CustAccountStatementExt)](customer-account-statement-report-custaccountstatementext.md).

4.  To show balance information on the report, select the **Show maturity distribution** check box, and select either **Aging period definitions** or **Manual setup of maturity distribution**. If you select **Manual setup of maturity distribution**, the **Printing direction** field controls whether the distribution shows future or past balance information.

5.  Click **Select**. On the **Company range** tab, select the legal entity to print statements for.

6.  On the **Range** tab, specify the customer accounts and customer groups to include transactions for.

7.  If the **Associated payment attachment on account statement** field is available, select a payment slip to print for the customer statement.

8.  On the **Range** tab, if you selected an **Account statement** value for the customer accounts in the **Customers** form, you can select a value to print statements only for customers who have that setting. You can additionally restrict the customer accounts that statements are printed for by selecting customer accounts and customer groups.

9.  Close the query form.

10. Click **Destinations ...**, set printer options, and then close the form.

11. Click **OK** to print the customer statements.

## Create and print periodic customer statements on behalf of multiple legal entities

Use this procedure to create and print customer statements periodically. Before you begin, switch to the legal entity that you use to create centralized customer statements.

A statement for a customer includes information about the customer's transaction activity in other legal entities, if the legal entities use the same party ID for that customer account. The transactions for each legal entity are grouped together on the statement. For more information about how to use the same party IDs across legal entities, see [Merge party IDs for customer accounts across multiple legal entities](merge-party-ids-for-customer-accounts-across-multiple-legal-entities.md).

1.  Click **Accounts receivable** \> **Reports** \> **External** \> **Customer account statement**.

2.  On the **General** tab, select the range of dates for which transaction activity is included on the report. For more information, see [Customer account statement report (CustAccountStatementExt)](customer-account-statement-report-custaccountstatementext.md).

3.  Select other options for statement criteria. For more information about these options, see [Customer account statement report (CustAccountStatementExt)](customer-account-statement-report-custaccountstatementext.md).
    

    > [!NOTE]
    > <P>If you select an option for <STRONG>Associated payment attachment on interest note</STRONG>, the transfer slip is printed only for the current legal entity, not for all legal entities whose transaction activity is included on the statements.</P>



4.  To show balance information on the report, select the **Show maturity distribution** check box, and select either **Aging period definitions** or **Manual setup of maturity distribution**. If you select **Manual setup of maturity distribution**, the **Printing direction** field controls whether the distribution shows future or past balance information.

5.  Click **Select**, and specify the legal entities to include transactions for.
    

    > [!NOTE]
    > <P>By default, the <STRONG>Company range</STRONG> tab displays all legal entities. Legal entities are automatically selected if they are included in an organization hierarchy that includes the legal entity that you are currently using. You can specify any combination of legal entities. However, if you select any legal entities that are not included in the organization hierarchy, transaction activity from those legal entities is not included on statements.</P>



6.  On the **Range** tab, specify the customers and customer groups to include transactions for.
    

    > [!NOTE]
    > <P>The lookup forms for the fields on the <STRONG>Range</STRONG> tab include the records from the first legal entity that is selected on the <STRONG>Company range</STRONG> tab. For example, if legal entities ABC and DEF are selected, the lookup forms display information from legal entity ABC.</P>



7.  If the **Associated payment attachment on account statement** field is available, select a payment slip to print for the customer statement.

8.  If you selected an **Account statement** value for the customer accounts in the **Customers** form, you can select a value to print statements only for customers who have that setting. You can additionally restrict the customer accounts that statements are printed for by selecting customer accounts and customer groups.

9.  Close the query form.

10. Click **Destinations ...**, set printer options, and then close the form.

11. Click **OK** to print the customer statements.

## Send customer account statements by using email

You can send customer account statements to customers by using email. One way to do this is to create a print management setting for each customer account and specify the customer’s email address for the destination. Then, when you generate customer account statements, the statements are sent to the destination that is specified by the print management setting. For information about how to set up a print management setting, see [Set up print management for a customer or vendor](set-up-print-management-for-a-customer-or-vendor.md).

Alternatively, you can set up print management for the **Customer account statement** document at the module level, and then use queries to select customer accounts that have email addresses. For information about how to set up print management for a module, see [Set up print management for a module](set-up-print-management-for-a-module.md).

## See also

[Customer account statement report (CustAccountStatementExt)](customer-account-statement-report-custaccountstatementext.md)

[Merge party IDs for customer accounts across multiple legal entities](merge-party-ids-for-customer-accounts-across-multiple-legal-entities.md)

[(DNK) Set up a payment slip format for customers](dnk-set-up-a-payment-slip-format-for-customers.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

