---
title: (POL) Post and print a returned package report
TOCTitle: (POL) Post and print a returned package report
ms:assetid: 8bc3cd83-8cd7-4dd5-b4b1-7716e7d71a06
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ923252(v=AX.60)
ms:contentKeyID: 52075334
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Poland
- returned package
---

# (POL) Post and print a returned package report [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to verify the packages that are issued for customers and to print the **Return packages confirmation** report.

You can use the **Packages at customers** report to verify the packages that are issued to customers. You can use the **Return packages transactions** form to verify the return package transactions for a selected customer. For more information, see [(POL) Return packages transactions (form)](https://technet.microsoft.com/en-us/library/jj923259\(v=ax.60\)).

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Select a customer, and then click the **Collect** tab.

3.  Click **Packages** \> **Packages return** to open the **Return packages confirmation** form.

4.  In the upper pane, press CTRL+N to create a new line.

5.  In the **Date** field, select or enter the transaction date.

6.  In the **Description** field, enter a description of the current journal.

7.  In the lower pane, press CTRL+N to create a new line.

8.  In the **Packaging code** field, select the code for the returned package.
    

    > [!NOTE]
    > <P>When you select the returned package code, the quantity of packages that can be returned by the customer is calculated and updated in the <STRONG>This quantity can be returned</STRONG> field.</P>



9.  In the **Return qty** field, enter the number of units of the item that were returned to inventory.
    

    > [!NOTE]
    > <P>When you enter the quantity, the amount that must be paid to the customer is calculated and updated in the <STRONG>Amount</STRONG> field.</P>



10. Click **Post** to open the **Packages return** form.

11. Select the **Print** check box to print a confirmation for the returned package, if confirmation is required.

12. Click **OK** to save and post the returned package transaction, and to print a confirmation.

13. In the **Return packages confirmation** form, click **Print** to print the **Return packages confirmation** report for all the returned packages.

## See also

[(POL) Set up returnable packages for a customer](pol-set-up-returnable-packages-for-a-customer.md)

[(POL) Register a package and verify package quantity for a sales order](pol-register-a-package-and-verify-package-quantity-for-a-sales-order.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

