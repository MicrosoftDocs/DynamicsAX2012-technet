---
title: Create direct deliveries
TOCTitle: Create direct deliveries
ms:assetid: ebe33658-f6c4-4192-92a9-6466244643db
ms:mtpsurl: https://technet.microsoft.com/library/Aa551512(v=AX.60)
ms:contentKeyID: 39519355
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- drop ship
- drop shipment
- create a purchase order directly from a sales order
audience: Application User
ms.search.region: Global
---

# Create direct deliveries 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to send ordered products directly to the customer from the vendor.

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.
    
    –or–
    
    Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Create a sales order.

3.  In the **Sales order** form, on the **Action Pane**, on the **Sales order** tab, click **Direct delivery** to open the **Create direct delivery** form.
    
    The **Create direct delivery** form lists all sales order lines in the sales order and includes the preferred vendors.
    

    > [!NOTE]
    > <P>You can set up a preferred vendor for an item per site, warehouse, location, color, size, and configuration on the <STRONG>General</STRONG> tab in the <STRONG>Item coverage</STRONG> form. You can access the <STRONG>Item coverage</STRONG> form from the <STRONG>Released products</STRONG> list page. For more information, see <A href="https://technet.microsoft.com/library/aa619147(v=ax.60)">Item coverage (form)</A>.</P>



4.  If needed, change the vendor account number in the **Vendor account** field.

5.  Select the **Include all** check box if you want to create direct deliveries for all the sales order lines in the form. You can also select individual lines by clicking the **Include** check box for each sales order line.
    

    > [!NOTE]
    > <P>If a portion of the ordered quantity has already been delivered, then you must split the remaining quantity. Create a new line with the quantity that needs to be directly delivered and subtract that quantity from the quantity on the original line. For example, if the original quantity was 15 and five have been delivered, you must create a new line for the remaining quantity of 10, and then reduce the original quantity by that amount.</P>



6.  Select or clear the parameters in the uppermost part of the form and then click **OK** when you are finished.
    
    A purchase order is created in the **Purchase order** form.

All updates to the selected sales order lines are now performed by using the **Purchase order** form except for invoicing. You must still invoice your customer manually.

## See also

[Sales orders (form)](https://technet.microsoft.com/library/aa585863\(v=ax.60\))

  


