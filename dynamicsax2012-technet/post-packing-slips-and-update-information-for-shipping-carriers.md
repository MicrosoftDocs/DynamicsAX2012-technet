---
title: Post packing slips and update information for shipping carriers
TOCTitle: Post packing slips and update information for shipping carriers
ms:assetid: b0556c9a-0fa5-4896-8bcb-51cae2804ad5
ms:mtpsurl: https://technet.microsoft.com/library/Gg232390(v=AX.60)
ms:contentKeyID: 36058961
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Post packing slips and update information for shipping carriers 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic applies to features in the **Inventory management** module. It does not apply to features in the [Warehouse management](warehouse-management.md) module.

Use this information to post packing slips and update shipping carrier information for sales orders. If the **Shipping carrier** configuration key is selected, shipping information for a sales order must be transferred to the shipping carrier software from Microsoft Dynamics AX before the invoice for the sales order can be posted.

You can view shipping information in the sales **Packing slip journal** form and in the **Carrier transaction information** form.


> [!NOTE]
> <P>If the <STRONG>Test mode</STRONG> check box is selected for the shipping carrier software interface, the <STRONG>Test mode</STRONG> form is displayed for each packing slip that you post. Use this form to enter information to simulate the information that you would receive from the shipping carrier software. When you are satisfied that shipping carrier information is set up correctly in Microsoft Dynamics AX, clear the <STRONG>Test mode</STRONG> check box to enable the system to transfer information from the shipping carrier software.</P>



## Post packing slips using logistics

Use this procedure to post packing slips for shipments.

1.  Use the **Sales order** form in Microsoft Dynamics AX to post the picking list and print picking slips.

2.  Use the picking slips to pick the items and take the goods to the shipping area.

3.  Use the **Packing slip posting** form in Microsoft Dynamics AX to enter packing slip information and print a packing slip. When you post the packing slip, information about the sales order and shipment is transferred to the shipping carrier software. To do this, follow these steps:
    
    1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.
    
    2.  Select an open sales order. On the Action Pane, click the **Pick and pack** tab, and then click **Packing slip**.
    
    3.  In the **Packing slip posting** form, select the **Posting** and **Print packing slip** check boxes.
    
    4.  Clear the **Print COD** and **Print shipping labels** check boxes.
        

        > [!NOTE]
        > <P>You can enter information in the fields on the <STRONG>Bill of lading</STRONG> tab, but it is not transferred to the shipping carrier software. This tab is available only if the <STRONG>Shipments</STRONG> configuration key is selected and if <STRONG>Packing slip update</STRONG> or <STRONG>Both</STRONG> is selected in the <STRONG>Bill of lading</STRONG> field in the <STRONG>Accounts receivable parameters</STRONG> form.</P>

    
    5.  In the lower pane, make any changes that are needed.
    
    6.  Click **OK**. The packing slip is printed and posted. Information is transferred to the shipping carrier software. You can view the shipment information in the **Packing slip journal** form.

4.  Use the shipping carrier software to verify information about the shipment, including shipping charges and package weight, and to print shipping labels.

5.  Use the shipping carrier software to process packages, generate labels, and transfer information to Microsoft Dynamics AX. You can view the information in the **Carrier transaction information** form.

## Post packing slips using warehouse management

Use this procedure to post packing slips for shipments that are picked and packed using warehouse management. This procedure assumes that you have already created output orders, posted picking lists, and printed picking slips. When you post the packing slip, information about the sales order and shipment is transferred to the shipping carrier software.

1.  Click **Inventory management** \> **Common** \> **Shipments**.

2.  Use the **Packing slip posting** form in Microsoft Dynamics AX to enter packing slip information and print a packing slip. To do this, follow these steps:
    
    1.  Select a shipment and then click **Functions** \> **Packing slip**.
    
    2.  Select the **Posting** and **Print packing slip** check boxes.
    
    3.  Clear the **Print COD** and **Print shipping labels** check boxes.
        

        > [!NOTE]
        > <P>You can enter information in the fields on the <STRONG>Bill of lading</STRONG> tab, but it is not transferred to the shipping carrier software. This tab is available only if the <STRONG>Shipments</STRONG> configuration key is selected.</P>

    
    4.  In the lower pane, make any changes that are needed.
    
    5.  Click **OK**. The packing slip is printed and posted. Information is transferred to the shipping carrier software. You can view the shipment information in the **Packing slip journal** form.

3.  Use the shipping carrier software to verify information about the shipment, including shipping charges and package weight, and to print shipping labels.

4.  Use the **Shipment** form to select a shipment and then click **Process shipment**. The following things occur:
    
      - Information is transferred to Microsoft Dynamics AX. You can view this information in the **Carrier transaction information** form.
    
      - If the order is COD, the invoice is posted and printed so that it can be included with the packing slip.
    
      - If the order is paid by credit card and the **Credit card authorization** check box in the **Accounts receivable parameters** form is selected, credit card information is submitted to the credit card company.
        

        > [!NOTE]
        > <P>If the card is approved, the invoice is posted and printed so that it can be included with the packing slip. If the card is rejected, a message is displayed and the invoice is not printed. You can remove the shipment from additional processing, and then notify the employee who is responsible for invoicing that the credit card was rejected.</P>

    
      - For the invoices that are posted, shipping charges are moved to the invoice as miscellaneous charges. For more information, see [About sales order information for shipping carriers](about-sales-order-information-for-shipping-carriers.md).

## See also

[About integration with shipping carriers](about-integration-with-shipping-carriers.md)

[About sales order information for shipping carriers](about-sales-order-information-for-shipping-carriers.md)

[Sales orders (form)](https://technet.microsoft.com/library/aa585863\(v=ax.60\))

[Packing slip journal (form)](https://technet.microsoft.com/library/aa548967\(v=ax.60\))

[Carrier transaction information (form)](https://technet.microsoft.com/library/hh209503\(v=ax.60\))

  


