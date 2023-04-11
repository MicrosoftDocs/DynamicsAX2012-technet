---
title: (IND) Calculate sales tax on a sales order
TOCTitle: (IND) Calculate sales tax on a sales order
ms:assetid: 7db941ff-36e6-4fb0-b917-5d06980d0e81
ms:mtpsurl: https://technet.microsoft.com/library/JJ677975(v=AX.60)
ms:contentKeyID: 49385939
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Calculate sales tax on a sales order 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When you invoice a purchase order or a sales order, a product receipt is created. A product receipt resembles the goods receipt note that is specific to India.

When you create a sales order, the tax form type, the sales tax group, and the item sales tax group are displayed in the line details of the sales order line. The tax type and groups are based on the values that are attached to the sales order.

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**. On the **Action Pane**, on the **Sales order** tab, in the **New** group, click **Sales order**.

2.  In the **Create sales order** form, enter the required details.

3.  On the **Line details** FastTab, on the **Setup** tab, in the **Sales tax group** field, select the sales tax group to use when calculating the sales tax for the sales order.

4.  In the **Item sales tax group** field, select the group of sales tax codes that is calculated for an item.

5.  On the **Sales order lines** FastTab, click **Add line**.

6.  In the **Item number** field, select the item number.

7.  In the **Quantity** field, enter the quantity of the item. You can view the amount details in the following fields:
    
      - **Net amount** – The net amount of the transaction. If the amount for the quantity is preceded by the negative sign, the net amount on the order line is also a negative value. Therefore, the **Assessable value** field also displays an amount with a negative value.
    
      - **Assessable value** – The net amount and the charges on the order line, if the taxable basis of a tax code is the assessable value. The values in this field can be changed, and the amount can be a positive or negative value.
        
        For example, an order line is created for 100 pieces of an item that is priced at the rate of INR 12. The net amount is INR 1,200. However, additional charges for the order line are INR 200 for freight and INR 300 for insurance. If the basis of calculation of a tax code is the assessable value that is displayed in the **Formula designer** form, the **Assessable value** field displays 1,700. This is the sum of 1,200 + 200 + 300. If the insurance is changed to INR 600, the basis of calculation of the sales tax is 2,000. This is the sum of 1200 + 200 + 600.
        
        If a sales order line has –10 items that cost INR 100 each, the net value and the assessable value of the order line are INR –1,000.
    
      - **Max. retail price** – On the **Line details** FastTab, on the **Price and discount** tab, this field automatically displays the maximum retail price. However, the value in this field can be modified. The debit or credit type of the value in the **Max. retail price** field must be based on the quantity and value of the item. You cannot enter a negative value in the **Max. retail price** field.

8.  On the **Line details** FastTab, on the **Tax information** tab, in the **Location** field, select the appropriate address. The address of the organization is displayed in the **Address** field. Based on the selection, the corresponding tax registration number is displayed in the **Registration number** field.

9.  In the **Sales tax** group, in the **Form type** field, select the type that is relevant to the state code of the customer.

10. On the **Sales order lines** FastTab, click **Financials** \> **Maintain charges** to attach the charges code to the item lines, and then close the form.

11. On the **Action Pane**, on the **Sell** tab, in the **Tax** group, click **Sales tax** to open the **Temporary sales tax transactions** form and view the details of the sales tax amount for the transaction that is displayed.

12. Click the **Adjustment** tab to adjust the sales tax amount, if it is required, and then click **Apply**.

13. Click **Formula designer**. In the **Formula designer** form, the calculation expression that is defined for each tax code in the item sales tax sales group is displayed. The fields in this form cannot be modified.

## See also

[(IND) Sales orders (modified form)](https://technet.microsoft.com/library/jj677998\(v=ax.60\))

[(IND) Formula designer (form)](https://technet.microsoft.com/library/jj677983\(v=ax.60\))

[(IND) Temporary sales tax transactions (modified form)](https://technet.microsoft.com/library/jj664487\(v=ax.60\))

  


