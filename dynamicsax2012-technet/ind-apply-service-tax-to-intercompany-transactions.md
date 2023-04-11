---
title: (IND) Apply service tax to intercompany transactions
TOCTitle: (IND) Apply service tax to intercompany transactions
ms:assetid: bdbd5fff-5bc1-4ef6-a710-780977f81de0
ms:mtpsurl: https://technet.microsoft.com/library/JJ664850(v=AX.60)
ms:contentKeyID: 49386180
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Apply service tax to intercompany transactions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



Using intercompany transactions allows you to create a corresponding purchase order or a sales order in an endpoint intercompany when you create a sales order or a purchase order in an intercompany.


> [!NOTE]
> <P>The invoice amount of the sales order should be the same as the invoice amount of the purchase order that is created automatically in the intercompany.</P>



The service tax can be calculated for a sales order or a purchase order in the intercompany transactions.

When you create a sales order or a purchase order in an intercompany, you can modify the fields under the **Service tax** field group on the **Tax information** tab in both the original order and in the order that is created automatically in the endpoint intercompany.

**Example**

Suppose a purchase order is created for item A for an intercompany vendor. The sales tax group and the item sales tax group for the purchase order have the following common tax codes:

Service tax = 12% on the line amount

E-cess = 2% on service tax

SHE cess = 1% on service tax

The line amount for the purchase order is INR 10,000.

An intercompany sales order is created automatically for item A. The sales tax group and the item sales tax group for the sales order have the same tax codes as selected in the purchase order.

In this case, the invoice amount of the sales order will be INR 11,236. The intercompany sales order is posted and the invoice amount of the purchase order is also INR 11,236. So, the purchase order is also posted.

Also, if the sales order that is created automatically has tax code, service tax = 12% on the line amount, and the E-cess = 2% on service tax, then the invoice amount in the sales order will be INR 11,224.

You cannot post the related purchase order because the invoice amount in the purchase order is INR 11,236, which is not the same as the invoice amount of the intercompany sales order.

1.  Click **Organization administration** \> **Common** \> **Number sequences** \> **Number sequences**. Click **Number sequences**.

2.  Complete the required setup for the intercompany in the two companies, Intercompany1 and Intercompany2.

3.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. click **Purchase order** and then, create a purchase order in Intercompany1.

4.  Click the **Setup** tab in the lower pane and select an item sales tax group in the **Item sales tax** group field. The sales tax group and the item sales tax group must have common tax codes of the service tax type.

5.  Click the **Tax information** tab in the in the lower pane to view the following fields under the **Service tax** field group. You can modify the values in the fields listed below.
    
      - **STC number**
    
      - **Service code**
    
      - **GTA service category**

6.  Save the purchase order.

7.  A sales order is created automatically in Intercompany2. You can modify the sales order, as needed, to match the purchase order. Verify the following information:
    
      - The invoice amount must be the same in both the purchase order and in the sales order.
    
      - The sales tax group and the item sales tax group must have common tax codes of the type service tax in the purchase order. The sales order must also have the same sales tax group and the item sales tax group as selected in the purchase order.

8.  Post the sales order in Intercompany2.

9.  Post the purchase order in Intercompany1.

## See also

[(IND) Purchase orders (modified form)](https://technet.microsoft.com/library/jj664798\(v=ax.60\))

  


