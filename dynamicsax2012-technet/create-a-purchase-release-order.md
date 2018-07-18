---
title: Create a purchase release order
TOCTitle: Create a purchase release order
ms:assetid: 4bbc52c7-9ff7-4f6f-a6d4-0cb1f29ed713
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh545520(v=AX.60)
ms:contentKeyID: 37832501
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create a purchase release order 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A purchase release order is a purchase order that is released from an existing purchase agreement. When you release order lines from a purchase agreement, the commitment terms specified in the purchase agreement are applied to the purchase order.


> [!NOTE]
> <P>If you have selected the <STRONG>Public sector</STRONG> configuration key, you can create a purchase agreement classification that requires direct invoices and prevents release orders from being created for purchase agreements that use the classification. For more information, see <A href="https://technet.microsoft.com/en-us/library/hh802986(v=ax.60)">Agreement classification (form)</A>.</P>



This topic describes two different procedures for creating purchase release orders.


> [!NOTE]
> <P>You can only create a release order from purchase agreements with a status of <STRONG>Effective</STRONG>.</P>



## Create a purchase release order from a purchase agreement


> [!NOTE]
> <P>This procedure can only be used when you have a purchase agreement with commitments for a quantity. Only commitments of the <STRONG>Product quantity commitment</STRONG> type are available in the <STRONG>Create a new release order</STRONG> form. To create a purchase release order from commitments of the <STRONG>Product value commitment</STRONG> type, you must first create a purchase order, and then you can add purchase order lines for these items. Microsoft Dynamics AX then finds the corresponding commitment and releases from the commitment.</P>



1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **Purchase agreements**.
    
    –or–
    
    Click **Accounts payable** \> **Common** \> **Purchase orders** \> **Purchase agreements**.
    
    This opens the **Purchase agreements** list page.

2.  Select the purchase agreement that you want to release from. You can also open the **Purchase agreements** form for the purchase agreement by double-clicking the purchase agreement in the list.

3.  On the **Action Pane**, click **Release order**. This opens the **Create a new release order** form.

4.  In the **Purchase quantity** field, enter a purchase quantity.
    

    > [!NOTE]
    > <P>If the <STRONG>Max is enforced</STRONG> check box is selected for the corresponding purchase agreement line, the purchase quantity cannot exceed the remaining quantity of the commitment in the purchase agreement.</P>

    

    > [!NOTE]
    > <P>If you enter a purchase quantity that conflicts with the default order settings for the item, see the <STRONG>Recommended order quantity</STRONG> column for an alternative quantity that complies with the default order settings, and update the purchase quantity accordingly.</P>



5.  In the **Delivery date** field, enter a delivery date.
    

    > [!NOTE]
    > <P>The delivery date must be in the range that is specified for the commitment by the <STRONG>Effective date</STRONG> and <STRONG>Expiration date</STRONG> fields in the purchase agreement.</P>



6.  Enter product and location dimensions, if they are not already specified.
    

    > [!NOTE]
    > <P>The dimension fields are active and must be specified if the <STRONG>Active</STRONG> check box is selected in the <STRONG>Product dimension groups</STRONG> form.</P>



7.  If you want to specify an alternative delivery address, click the **Select a different address** button next to the **Delivery address** field.

8.  Click **Create** to submit the purchase release order. Submitting the order generates a new purchase order on the **All purchase orders** list page.

## Create a purchase release order from a new purchase order

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.
    
    –or–
    
    Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.
    
    This opens the **All purchase orders** list page.

2.  On the **Action Pane**, click **Purchase order** to create a new purchase order.

3.  In the **Create purchase order** form, select a vendor in the **Vendor account** field.

4.  Expand the **General** FastTab. If any purchase agreements exist for the selected vendor, the purchase agreements appear in the **Purchase agreement ID** field. Select a purchase agreement.

5.  Click **Yes** if you want to transfer the currency and delivery address from the selected purchase agreement. Click **No** if you want to use the default delivery address and currency information for the vendor.

6.  Click **OK**.

7.  On the purchase order line, in the **Item number** field, enter the item number that is specified in the purchase agreement commitment. A link is created between the purchase order line and the purchase agreement commitment.

8.  In the **Quantity** field, enter a purchase quantity.
    

    > [!NOTE]
    > <P>If the <STRONG>Max is enforced</STRONG> check box is selected on the corresponding purchase agreement line, the purchase quantity cannot exceed the remaining quantity of the purchase agreement.</P>



9.  Enter product and location dimensions, if they are not already specified.
    

    > [!NOTE]
    > <P>The dimension fields are active and must be specified if the <STRONG>Active</STRONG> check box is selected in the <STRONG>Product dimension groups</STRONG> form. Active dimensions cannot be changed without causing the link to be removed.</P>



10. In the **Delivery date** field, enter a delivery date by clicking **Line details** \> **Delivery**.
    

    > [!NOTE]
    > <P>The delivery date must be in the range that is specified for the commitment by the <STRONG>Effective date</STRONG> and <STRONG>Expiration date</STRONG> fields in the purchase agreement.</P>



11. Click **Close**.


> [!NOTE]
> <P>If the <STRONG>Price and discount is fixed</STRONG> check box is selected for the corresponding purchase agreement line, you cannot change any price or discount information without causing the link to be removed.</P>




> [!NOTE]
> <P>You cannot change the unit without causing the link to be removed.</P>



## See also

[Purchase order (form)](https://technet.microsoft.com/en-us/library/aa557983\(v=ax.60\))

[Purchase agreements (form)](https://technet.microsoft.com/en-us/library/hh209550\(v=ax.60\))

[Create purchase release order (form)](https://technet.microsoft.com/en-us/library/aa588195\(v=ax.60\))

  


