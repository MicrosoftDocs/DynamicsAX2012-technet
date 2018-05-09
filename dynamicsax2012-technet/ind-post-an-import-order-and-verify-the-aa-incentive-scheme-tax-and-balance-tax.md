---
title: (IND) Post an import order and verify the AA incentive scheme tax and balance tax
TOCTitle: (IND) Post an import order and verify the AA incentive scheme tax and balance tax
ms:assetid: 84a1eccd-0019-4b64-976e-1cb1b0b9980b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677981(v=AX.60)
ms:contentKeyID: 49385944
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Post an import order and verify the AA incentive scheme tax and balance tax 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to verify the details about the amount of incentive scheme tax and balance tax for a license that was issued for the Advance Authorization (AA) incentive scheme, and to correct the amounts if they do not match the vendor invoice. When you finish verifying and correcting amounts, you can post the import order.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. Select the purchase order, and then, on the **Action Pane**, on the **Purchase order** tab, in the **Maintain** group, click **Edit**.

2.  In the **Purchase order** form, on the **Action Pane**, click the **Customs** tab. Then, in the **Maintain** group, click **Invoice registration**.

3.  In the **Invoice registration** form, in the **Import invoice number** field, select the import invoice number, and then click **Update**. Close the **Invoice registration** form.

4.  In the **Purchase order** form, on the **Action Pane**, click the **Customs** tab. Then, in the **Generate** group, click **Bill of entry**.

5.  In the **Bill of entry** form, on the **Parameters** tab, in the **Parameters** area, select the **Bill of entry** check box. In the **Number** field, select the bill of entry number.

6.  On the **Overview** tab, in the **Import invoice number** field, select the import invoice number for the vendor.
    
    The association between the vendor and the import invoice number is maintained in the **Vendor account setup** form. You can access this form by clicking **Setup** in the **Import invoice number** form.

7.  Click **Tax**. In the **Temporary sales tax transactions** form, review the amount of incentive scheme tax and balance tax. Also, compare the calculated tax amount to the invoiced tax amount. If the amounts do not match, enter the correct amount in the **Total actual tax amount in customs currency** field.
    
    Close the **Temporary sales tax transactions** form.
    
    For more information about the fields in this form, see [(IND) Temporary sales tax transactions (modified form)](https://technet.microsoft.com/en-us/library/jj664487\(v=ax.60\)).

8.  In the **Bill of entry** form, on the **Setup** tab, in the **Bill of entry date** field, select the date when the goods entered the country. Click **OK** to post the bill of entry and to close the **Bill of entry** form.

9.  In the **Purchase order** form, on the **Action Pane**, click the **Invoice** tab. Then, in the **Generate** group, click **Invoice**.

10. In the **Vendor invoice** form, in the **Default quantity for lines** field, select **Bill of entry quantity**, and then enter any additional values.

11. On the **Action Pane**, in the **Actions** group, click **Post**. Select the posting settings, and then click **Post**.

After you post the invoice, you can view the details of the import order by using the **Import details** form. You can access the form in several ways, which include the following:

  - In the **Purchase order** form, at the top of the **Purchase order lines** FastTab, click **Purchase order line**, and then, in the **View** group, click **EXIM - AA**.

  - Click **General ledger** \> **Common** \> **EXIM Authorization schemes**. Select the authorization, and then, on the **Action Pane**, in the **Inquiry** group, click **Import details**.

## See also

[(IND) Purchase orders (modified form)](https://technet.microsoft.com/en-us/library/jj664798\(v=ax.60\))

[(IND) Manage purchase orders](ind-manage-purchase-orders.md)

[(IND) Create an import order and apply the AA incentive scheme to the import order](ind-create-an-import-order-and-apply-the-aa-incentive-scheme-to-the-import-order.md)

[(IND) Process purchase transactions and bills of entry](ind-process-purchase-transactions-and-bills-of-entry.md)

[(IND) Create an importer invoice number for import orders](ind-create-an-importer-invoice-number-for-import-orders.md)

[(IND) Update the import order line quantity after updating the invoice registration](ind-update-the-import-order-line-quantity-after-updating-the-invoice-registration.md)

[(IND) Set up a bill of entry number for import orders](ind-set-up-a-bill-of-entry-number-for-import-orders.md)

[(IND) Bill of entry number (form)](https://technet.microsoft.com/en-us/library/jj664729\(v=ax.60\))

[(IND) Verify tax amounts for an incentive scheme by using a bill of entry journal](ind-verify-tax-amounts-for-an-incentive-scheme-by-using-a-bill-of-entry-journal.md)

[(IND) Bill of entry journal (form)](https://technet.microsoft.com/en-us/library/jj677988\(v=ax.60\))

[(IND) Generate bills of entry inquiries for import orders](ind-generate-bills-of-entry-inquiries-for-import-orders.md)

[(IND) Post bills of entry for import orders](ind-post-bills-of-entry-for-import-orders.md)

[(IND) Tax transactions (form)](https://technet.microsoft.com/en-us/library/jj710906\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

