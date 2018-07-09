---
title: (IND) Post the import order and verify the DFIA incentive scheme tax and balance tax
TOCTitle: (IND) Post the import order and verify the DFIA incentive scheme tax and balance tax
ms:assetid: 95a39f52-22c4-4b58-99c6-a4ecd59ae991
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678051(v=AX.60)
ms:contentKeyID: 49386013
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (IND)
- India
- incentive scheme
- DFIA
- import order
- incentive
- scheme tax
---

# (IND) Post the import order and verify the DFIA incentive scheme tax and balance tax [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to post the import order for a Duty Free Import Authorization (DFIA) after you receive the goods. You can adjust the calculated tax amount to match the invoiced tax amount, if necessary.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Select the purchase order, and then, on the **Action Pane**, on the **Purchase order** tab, in the **Maintain** group, click **Edit**.

3.  In the **Purchase order** form, on the **Action Pane**, click the **Customs** tab. In the **Maintain** group, click **Invoice registration**.

4.  In the **Invoice registration** form, in the **Import invoice number** field, select the import invoice number, and then click **Update**. Close the **Invoice registration** form to return to the **Purchase order** form.

5.  On the **Action Pane**, on the **Customs** tab, in the **Generate** group, click **Bill of entry**.

6.  In the **Bill of entry** form, on the **Parameters** tab, in the **Parameters** area, select the **Bill of entry** check box.

7.  In the **Number** field, select the bill of entry number.

8.  On the **Overview** tab, in the **Import invoice number** field, select the import invoice number for the vendor. The association between the vendor and the import invoice number is maintained in the **Vendor account setup** form, which is accessed by clicking **Setup** in the **Import invoice number** form.
    

    > [!IMPORTANT]
    > <P>You can view the calculated tax amount and compare it to the invoiced tax amount by clicking <STRONG>Tax</STRONG> to open the <STRONG>Temporary sales tax transactions</STRONG> form. You can also adjust the tax amount, if necessary, by changing the amount in the <STRONG>Total actual tax amount in customs currency</STRONG> field.</P>



9.  Click the **Setup** tab, and then, in the **Bill of entry date** field, select the date that the goods entered the country.

10. Click **OK** to post the bill of entry and close the **Bill of entry** form.

11. In the **Purchase order** form, on the **Action Pane**, on the **Invoice** tab, in the **Generate** group, click **Invoice**.

12. In the **Vendor invoice** form, in the **Default quantity for lines** field, select **Bill of entry quantity**.

13. Enter any additional values, and then, on the **Action Pane**, in the **Actions** group, click **Post**.

14. In the **Select the posting settings** form, select the posting settings, and then click **Post**.

After you post the invoice, you can view the details of the import order by using the **Import details** form. You can access the form in several ways, including the following:

  - In the **Purchase order** form, at the top of the **Purchase order lines** FastTab, click **Purchase order line**, and then, in the **Display** group, click **EXIM - DFIA**.

  - In **General ledger**, open the **EXIM Authorization schemes** list page. Select the authorization, and then, on the **Action Pane**, in the **Inquiry** group, click **Import details**.

## See also

[(IND) Set up a bill of entry number for import orders](ind-set-up-a-bill-of-entry-number-for-import-orders.md)

[(IND) Post bills of entry for import orders](ind-post-bills-of-entry-for-import-orders.md)

[(IND) Create an importer invoice number for import orders](ind-create-an-importer-invoice-number-for-import-orders.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

