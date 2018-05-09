---
title: (IND) Create an export order for DBK scheme
TOCTitle: (IND) Create an export order for DBK scheme
ms:assetid: a2161eae-0252-471d-a87a-1d6c125f587c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664726(v=AX.60)
ms:contentKeyID: 49386057
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (IND)
- india
- DBK scheme
- export order
---

# (IND) Create an export order for DBK scheme 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

To apply for duty drawback and settle the duty drawback transactions, you must create an export sales order, post the shipping bill, apply for duty drawback for the export sales order, and then settle the duty drawback transactions.

Update the duty drawback details on the **Line details** FastTab in the **Tax information** area in the **Sales order** form before posting the invoices.

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  On the **All sales orders** list page, on the **Action pane**, on the **Sales order** tab, click **Sales order** to create a new sales order.

3.  In the **Create sales order** form, in the **Customer account** field, select the customs customer. Then select the **Export order** check box.

4.  Enter any additional field values, and then click **OK** to create a new sales order.

5.  Add a sales order line, and then on the **Line details** FastTab, click the **Tax information** tab in the lower pane.

6.  In the **Customs** field group, in the **Customs tariff code** field, select the customs tariff code for the sales order line.

7.  In the **Drawback CENVAT status** field, select one of the following options to indicate whether the manufacturer takes advantage of the CENVAT credit:
    
      - **Availed** – The manufacturer takes advantage of the CENVAT credit.
    
      - **Not availed** – The manufacturer does not take advantage of the CENVAT credit.
    

    > [!NOTE]
    > <P>You can modify the <STRONG>Drawback CENVAT status</STRONG> field only if the following conditions are met:</P>
    > <UL>
    > <LI>
    > <P>The <STRONG>Duty drawback</STRONG> check box is selected in the <STRONG>DBK</STRONG> area in the <STRONG>Incentive scheme parameters</STRONG> form.</P>
    > <LI>
    > <P>The <STRONG>Export order</STRONG> check box is selected in the <STRONG>Create sales order</STRONG> form when you create the sales order.</P></LI></UL>



8.  In the **Drawback rate type** field, select one of the following rate values:
    
      - **All industry rate** – The rate applies to various product categories as a percentage of the Free On Board (FOB) price of the exported products. A value cap is applied to certain product categories.
    
      - **Brand rate** – The rate applies only to special products.
    
      - **Special brand rate** – The rate applies to products when the actual duty paid on the input goods is more than the all industry rate that is fixed for the product.
    

    > [!NOTE]
    > <P>To modify the <STRONG>Drawback rate type</STRONG> and <STRONG>Drawback pct.</STRONG> fields, you must select either <STRONG>Availed</STRONG> or <STRONG>Not availed</STRONG> in the <STRONG>Drawback CENVAT status</STRONG> field.</P>



9.  In the **Drawback pct.** field, enter the drawback percentage to use to calculate the drawback amount.

10. In the **Port ID** field, select the export and import (EXIM) port for the sales order.

11. In the **Product group** field, select the product group that applies to the items in the export order. The product group determines the duty drawback values that apply to the export order lines. A product group must be selected to post an export order.
    

    > [!NOTE]
    > <P>If the quantity of the item on the <STRONG>Sales order lines</STRONG> FastTab is negative, the <STRONG>Drawback CENVAT status</STRONG>, <STRONG>Drawback rate type</STRONG>, and <STRONG>Drawback pct.</STRONG> fields are not available.</P>



12. Post the export order to update the financial entries for the items and the customer account.
    
    For more information about how to post an export sales order, see [(IND) Invoice an export sales order](ind-invoice-an-export-sales-order.md).

## See also

[(IND) Sales orders (modified form)](https://technet.microsoft.com/en-us/library/jj677998\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

