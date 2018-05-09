---
title: Set up shipping carriers
TOCTitle: Set up shipping carriers
ms:assetid: d1c7a21c-04f9-4a9b-b72d-a2936f1da903
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg213688(v=AX.60)
ms:contentKeyID: 36059502
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up shipping carriers 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic applies to features in the **Inventory management** module. It does not apply to features in the [Transportation management](transportation-management.md) module.

Use this information to set up Microsoft Dynamics AX for integration with common shipping carrier software, such as Kewill Clippership, UPS WorldShip, and FedEx Ship Manager.

## Install and configure shipping carrier software

For detailed instructions, consult the documentation provided with the shipping carrier software you are using.

## Enable the shipping carrier feature

1.  Click **System administration** \> **Setup** \> **Licensing** \> **License configuration**.

2.  Expand the **Trade** list.

3.  Select the **Shipping carrier** configuration key.

4.  Click **OK**, and then restart the Microsoft Dynamics AX client.

## Specify the return address for sales documents

Select the return address that will be printed on packing slips and invoices.

1.  Click **Inventory management** \> **Setup** \> **Inventory and warehouse management parameters**.

2.  In the **Return to** field, select the return address to use for shipping documents from the following options:
    
      - **Company** – Use the legal entity address that is specified in the **Legal entities** form.
    
      - **Warehouse** – Use the address of the warehouse from which the shipment is sent.
    
      - **Site** – Use the address of the site from which the shipment is sent.

## Set up miscellaneous charges codes for shipping carriers

You can use existing miscellaneous charges codes or create new ones to use for shipping charges that are transferred from the shipping carrier software. If necessary, create miscellaneous charges codes for the following types of shipping charges:

  - Core freight charges – Used for shipping charges that are based on the weight of the shipment.

  - Ancillary charges – Used for ancillary charges that are applied to a shipment.

  - Handling – Used for handling charges that are applied to a shipment, such as COD. fees.

  - Fuel surcharges – Used for surcharges that are related to the price of fuel and are typically applied to an entire shipment.

For more information, see [Charges code (form)](https://technet.microsoft.com/en-us/library/aa598932\(v=ax.60\)).

1.  Click **Accounts receivable** \> **Setup** \> **Charges** \> **Charges code**.

2.  Select or create a miscellaneous charges code.

3.  Click the **Posting** FastTab.

4.  Select the **Customer/Vendor** debit type.

5.  Select the **Ledger account** credit type and the **Order, freight** posting type, and then select a credit posting account.

6.  Repeat steps 2 through 5 for the remaining miscellaneous charges codes that you will use for shipping charges.

## Set up carrier company information for shipping carriers

Set up a code to represent the carrier company and account information for each of the warehouses or other locations from which you ship goods. Later, you can assign an account code to a mode of delivery that represents shipments from each warehouse. For more information, see [Carrier company (form)](https://technet.microsoft.com/en-us/library/hh209693\(v=ax.60\)).

1.  Click **Inventory management** \> **Setup** \> **Shipping carrier** \> **Carrier company**.

2.  Select a carrier and enter a tracking number URL.

3.  Select the vendor account for the shipping carrier.

4.  On the **General** FastTab, select a miscellaneous charges code for each of the fields.

5.  On the **Accounts** FastTab, enter an account code and select a carrier company.

6.  In the **Carrier account number** field, enter the number that is used by the carrier to bill your organization.

7.  In the **Currency** field, enter the currency code that represents the currency that is used by the carrier software. This currency is assigned to all charges that are received from the carrier software for this account when the packing slip is posted.

8.  If you are using the Kewill Clippership shipping carrier software interface, in the **Ship via company** field, enter the index number that corresponds to the shipping company that will be used.

## Set up carrier service IDs for shipping carriers

Specify an identifier for each type of service that you use. Set up the codes that are required by the shipping carrier interface. Later, you can assign a carrier ID to a mode of delivery that represents a type of service, such as Ground or 2-Day Air.

1.  Click **Inventory management** \> **Setup** \> **Shipping carrier** \> **Carrier IDs**.

2.  In the **Carrier ID** field, enter the carrier ID, such as FO6A, that is required by the carrier interface that you use.

3.  Enter a description of the carrier service, and select a carrier company and a carrier interface ID.

4.  Press CTRL+N and repeat steps 2 and 3 for the remaining carrier services that you use.

## Set up modes of delivery for shipping carriers

Specify shipping carrier information for each mode of delivery that requires a shipping carrier.

1.  Click **Sales and marketing** \> **Setup** \> **Distribution** \> **Modes of delivery**.

2.  Select a mode of delivery.

3.  On the **Setup** FastTab, select the type of shipping service that is used for the selected mode of delivery. This information is used to sort information on reports.

4.  Select a carrier ID. This information is used by the shipping carrier software to process the shipment.

5.  If the mode of delivery originates from a specific warehouse or shipping location, select a carrier account code. For more information, see [Carrier company (form)](https://technet.microsoft.com/en-us/library/hh209693\(v=ax.60\)).

6.  Repeat steps 2 through 5 for the remaining modes of delivery.

## Set up terms of delivery for shipping carriers

Set up terms of delivery that can be assigned to sales orders to determine which types of shipping charges are passed on to your customers as miscellaneous charges.

1.  Click **Sales and marketing** \> **Setup** \> **Distribution** \> **Terms of delivery**.

2.  Select a terms of delivery record.

3.  On the **Setup** FastTab, select the types of freight charges to move from the shipping carrier software to miscellaneous charges for the selected delivery terms:
    
      - **Not applicable** – The customer is not charged for freight.
    
      - **N/A - third party/collect** – The customer is not charged for freight on the invoice. To bill a third party, you must enter a third-party account and a third-party address. To bill the customer using their own shipping carrier account (collect), you must enter an account.
    
      - **Core** – The customer is charged only for basic freight charges from the shipping carrier software.
    
      - **Ancillary and handling** – The customer is charged only for additional charges from the shipping carrier software that are designated as ancillary or handling.
    
      - **Core, ancillary, and handling** – The customer is charged for all charges from the shipping carrier software.

4.  To waive the shipping charges if the invoice amount exceeds a certain amount, select the **Apply free minimum** check box and enter the minimum sales invoice amount in the **Apply free minimum** field. This is the sales amount before taxes, freight, and miscellaneous charges.

## Set up customer information for shipping carriers

You can specify default shipping information for each customer account.

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Double-click a customer account and then click the **Addresses** FastTab.

3.  Select an address and then click **Edit**.

4.  If a third party is billed for freight directly by the shipping carrier, select **Third-party shipping address** in the **Purpose** field and enter information on the **Address** FastTab for the third party's billing address for freight charges. This information is transferred to the shipping carrier software when sales orders for the customer are processed.

5.  Click the **Delivery** FastTab and then select a mode of delivery.

6.  If you do not want a return address to appear on documents, select the **Blind shipment** check box. Your legal entity or warehouse return address information will not be printed on the packing slip or invoice for this customer.

7.  If the address is located in a residential area, select the **Residential destination** check box. The shipping carrier might use a different schedule for delivery to a residential destination.

8.  You can enter the customer's account number for the shipping carrier that is associated with the carrier ID. The carrier ID and carrier account number are copied to sales orders when they are created.

9.  Click **OK**.

10. If the customer should be charged a fuel surcharge, click the **Invoice and delivery** FastTab in the **Customers** form, and then select the **Charge fuel surcharge** check box.

## Activate shipping carrier interfaces

When you have completed the other setup tasks, activate the shipping carrier interfaces that you use.

1.  Click **Inventory management** \> **Setup** \> **Shipping carrier** \> **Carrier interface**.

2.  Select the **Enabled** check box for each shipping carrier that you use.

3.  Select the **Test mode** check box for each shipping carrier that you use. When you have confirmed that the setup is correct, clear this check box.

## See also

[About integration with shipping carriers](about-integration-with-shipping-carriers.md)

[About sales order information for shipping carriers](about-sales-order-information-for-shipping-carriers.md)

[Post packing slips and update information for shipping carriers](post-packing-slips-and-update-information-for-shipping-carriers.md)

[Carrier interface (form)](https://technet.microsoft.com/en-us/library/hh209394\(v=ax.60\))

[Carrier company (form)](https://technet.microsoft.com/en-us/library/hh209693\(v=ax.60\))

[Carrier ID (form)](https://technet.microsoft.com/en-us/library/hh209608\(v=ax.60\))

[Inventory and warehouse management parameters (form)](https://technet.microsoft.com/en-us/library/aa587658\(v=ax.60\))

[Modes of delivery (form)](https://technet.microsoft.com/en-us/library/aa619881\(v=ax.60\))

[Terms of delivery (form)](https://technet.microsoft.com/en-us/library/aa575567\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

