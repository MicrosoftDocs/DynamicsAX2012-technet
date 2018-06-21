---
title: (POL) Register a package and verify package quantity for a sales order
TOCTitle: (POL) Register a package and verify package quantity for a sales order
ms:assetid: a3394526-79c3-4788-9ad6-f7623b52dfcd
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ923255(v=AX.60)
ms:contentKeyID: 52075337
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- package
- register
- Poland
---

# (POL) Register a package and verify package quantity for a sales order [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can register packages for sales orders and sales order lines. You can then post the packing slip and customer invoice, and print the quantity of the issued packages on the packing slip. You can verify the quantity of the packaged items for a sales order in the **Return packages transactions** form.

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Create a sales order or open an existing sales order, and enter the required details. For more information, see [Sales orders (form)](https://technet.microsoft.com/en-us/library/aa585863\(v=ax.60\)).

3.  Click **Line view**, and create a sales order line for the item that is related to the packaging code. For more information, see [(POL) Set up returnable packages for a customer](pol-set-up-returnable-packages-for-a-customer.md).

4.  On the **Line details** tab, on the **Packing** tab, in the **Packing unit** field, select the packing unit.
    

    > [!NOTE]
    > <P>You must select the same packing unit that is selected for the item in the <STRONG>Packing units</STRONG> form.</P>



5.  On the **Sales order lines** tab, click **Financials** \> **Package issue** to open the **Package issue**. Modify or remove the packages that are automatically calculated for the sales order line.

6.  Close the form.

7.  In the **Sales order** form, on the **Action Pane**, on the **General** tab, click **Package issue** to open the **Package issue** form. You can view the packages that are calculated for all the sales order lines. You can also add extra packages, if additional packages are required.

8.  Close the form.

9.  On the **Pick and pack** tab, click **Packing slip** to open the **Packing slip posting** form and register the packages.

10. Click **Package issue** to open the **Package issue** form. You can view the packages that are generated and add extra packages, if additional packages are required. In the **Deliver now** field, you can modify the quantity of packages to deliver.

11. Close the form.

12. Click **OK** to post the packing slip.
    
    The package issue transactions are posted in the **Return packages transactions** form. The quantity of issued packages is printed on the packing slip.

13. In the **Sales order** form, click **Invoice** \> **Invoice** to open the **Posting invoice** form and register the packages.

14. Click **OK** to post the invoice. The invoice is posted, and the amounts are updated. The deposit amount is calculated based on the deposit prices that are set up for each packaging code. You can view the deposit amount that is posted as a separate transaction in the **Customer transactions** form.

15. Close the forms.

16. Click **Inventory management** \> **Setup** \> **Packing material** \> **Return packages**. Click **Transactions**.

17. In the **Return packages transactions** form, verify the package issue transaction that is posted for each package code.

18. Click **Voucher** to open the **Voucher transactions** form. Verify the customer deposit amounts that are posted to the main account. The main account number is specified in the **Customer posting profiles** form.

## See also

[(POL) Post and print a returned package report](pol-post-and-print-a-returned-package-report.md)

[(POL) Return packages transactions (form)](https://technet.microsoft.com/en-us/library/jj923259\(v=ax.60\))

[(POL) Sales posting (modified form)](https://technet.microsoft.com/en-us/library/jj923256\(v=ax.60\))

[(POL) Packing units (modified form)](https://technet.microsoft.com/en-us/library/jj681858\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

