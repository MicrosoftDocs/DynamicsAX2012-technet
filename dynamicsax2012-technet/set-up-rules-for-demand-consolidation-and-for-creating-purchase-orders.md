---
title: Set up rules for demand consolidation and for creating purchase orders
TOCTitle: Set up rules for demand consolidation and for creating purchase orders
ms:assetid: 94707a11-df77-4de6-898c-529634109b1c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh209386(v=AX.60)
ms:contentKeyID: 36058599
ms.date: 04/27/2016
mtps_version: v=AX.60
---

# Set up rules for demand consolidation and for creating purchase orders [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to define the policy rules that are used when you convert purchase requisitions to purchase orders.


> [!NOTE]
> <P>This topic includes information about features that were added or changed for cumulative update 6 or later for Microsoft Dynamics AX 2012 R2. This information also applies to AX 2012 R3.</P>



You can perform the following tasks:

  - Set criteria that are used to determine when a separate purchase order must be created for a purchase requisition line.

  - Define the price tolerance rules that are used to route approved purchase requisitions back through the review process when the price of an item in an internal catalog increases.

  - Identify which approved purchase requisitions must be processed manually, and whether those purchase requisitions are eligible for demand consolidation.

  - Configure the processing rules that are applied to a purchase requisition when it fails validation because of a vendor error or a price tolerance error.

  - In Microsoft Dynamics AX 2012 R3 or cumulative update 6 or later for AX 2012 R2, you can indicate how prices and discounts for catalog items should be determined when an approved purchase requisition is converted to a purchase order. You can either transfer prices and discounts directly from the purchase requisition, or you can use trade agreements to calculate the prices and discounts.


> [!NOTE]
> <P>Public sector entities that use commitments to manage budget reservations cannot create purchase orders from purchase requisitions. For more information, see <A href="fra-about-commitments-public-sector.md">(FRA) About commitments (Public sector)</A>.</P>



### Set up rules for demand consolidation and for creating purchase orders

1.  Click **Procurement and sourcing** \> **Setup** \> **Policies** \> **Purchasing policies**.

2.  On the **Purchasing policies** list page, select an existing purchasing policy, or create a new purchasing policy.
    
    For more information about how to create a purchasing policy, see [Key tasks: Create purchasing policies](key-tasks-create-purchasing-policies.md).

3.  In the **Purchasing policy** form, on the **Policy rules** FastTab, select **Purchase order creation and demand consolidation rule** in the **Policy rule type:** list, and then click **Create policy rule**.

4.  On the **General** tab, enter the date range that the policy rule is valid for.

5.  Click the **Purchase order split** tab, and then define the parameters that determine when purchase requisition lines are split into separate purchase orders. You can split purchase requisition lines based on the requester, line type, or procurement category.
    

    > [!NOTE]
    > <P>If the legal entity, vendor, or currency differs on the purchase requisition lines, a separate purchase order is automatically created.</P>



6.  Click the **Price/discount transfer** tab to indicate how the prices and discounts for catalog items should be determined when you convert approved purchase requisitions to purchase orders. Select one of the following options:
    
      - **Only if no trade agreement** – Prices and discounts are transferred from the purchase requisition only if there is no applicable trade agreement or base price. If a trade agreement or base price exists for the item or vendor, the prices and discounts are recalculated based on the trade agreement or the base price and applied to the purchase order. Unless otherwise specified, this is the default behavior.
    
      - **Always** – Prices and discounts are always transferred from the purchase requisition.
    
    You can also allow the method for price and discount transfer to be changed for an individual purchase requisition, regardless of the price/discount transfer rule that is defined. The change can only be done by a reviewer or approver after the requisition is submitted to workflow. Select the **Allow manual override per purchase requisition line** check box if you want to enable this capability.
    
    This control is not available in versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012 R2.

7.  Click the **Price tolerance** tab. Then set the maximum amount that the net amount on a line item on a purchase requisition can increase between the time that the purchase requisition is approved and the time that the purchase order is created. The net amount is calculated by using the following formula: ((quantity \* (unit price – discount)/price unit) + purchase miscellaneous charges) \* (100 – discount percent)/100.
    
    Purchase requisition lines that exceed the price tolerance that you set are held for manual processing. The rules that you configure on the **Error processing** tab determine how the purchase requisition lines are processed.
    

    > [!NOTE]
    > <P>These settings only apply to purchase requisition lines for internal catalog items that are not included in either a request for quotation or a consolidation opportunity. For these line items, the price is calculated when the purchase order is created. The calculation is based on the default price, trade agreements, and purchase agreements that are valid at the time that the purchase order is created.</P>



8.  Click the **Error processing** tab, and then configure the processing rule that is applied to a purchase requisition if it fails validation during purchase order creation because of a vendor error or a price tolerance error. Select one of the following options:
    
      - **No action** – The purchase requisition lines remain on the **Release approved purchase requisitions** form. The status of the purchase requisition lines remains **Approved**. However, the errors must be resolved before a purchase order can be generated for the purchase requisition lines.
    
      - **Cancel the purchase requisition line** –The purchase requisition lines are canceled. The requester can create a new purchase requisition for the canceled lines if he or she still wants to request the line items.
    
      - **Create a new purchase requisition line** – The purchase requisition lines are canceled. New purchase requisitions are then created that contain only the purchase requisition lines that failed validation. When the new purchase requisitions are created, they have a status of **Draft**. These purchase requisitions can be resubmitted for review after the validation errors have been resolved. The preparer for the purchase requisition lines is notified that the lines were canceled, and that new purchase requisitions were created for the purchase requisition lines that failed.

9.  Click the **Manual purchase order creation** tab. Then define the parameters that determine whether a purchase requisition must be manually processed, or whether it can be automatically converted into a purchase order. The parameters can apply to internal catalog items, external catalog items, or non-catalog items. Select one of the following options:
    
      - **Manually create purchase orders** – Manually create purchase orders for all purchase requisitions.
    
      - **Automatically create purchase orders** – Automatically create purchase orders for all approved purchase requisitions. No purchase requisitions are held for manual purchase order creation.
    
      - **Automatically create purchase orders except under these conditions** – Manually create purchase orders for purchase requisitions that match the criteria that you define. All other purchase requisitions that are approved are automatically converted to purchase orders.
        
        If you select **Automatically create purchase orders except under these conditions**, you can add procurement categories and vendors to specify which approved purchase requisition lines are held for manual processing. This option can apply to internal catalog items, external catalog items, and non-catalog items. When you select a procurement category, any subcategories for that procurement category are also selected. Select the **All** option for a specific type of purchase requisition line to hold all lines of that line type for manual processing.

10. If you want purchase orders to be automatically created from approved purchase requisitions when the batch job for purchase order generation runs, select the **Run automatic purchase order creation as a batch job** check box. This check box applies only to purchase requisitions that do not require manual processing. By running automatic purchase order generation as a batch job, you can schedule this activity at a time when resources are less constrained.

11. If the **Prepayment required** check box is selected on the purchase requisition lines, select the **When the requisition is set up for prepayment** check box to hold approved purchase requisitions for manual processing. Purchase requisitions that are held for manual processing can be filtered so that you can view only those purchase requisition lines that require prepayment.
    

    > [!NOTE]
    > <P>After the prepayment purchase order is created for the purchase requisition line, and the prepayment purchase order is invoiced, a prepayment journal voucher is created. For more information about prepayments and the prepayment journal vouchers, see <A href="about-prepayments-and-prepayment-journal-vouchers.md">About prepayments and prepayment journal vouchers</A>.</P>



12. Click the **Demand consolidation** tab, and then define the parameters that determine whether purchase requisitions that are manually processed can be considered for purchase requisition consolidation. The parameters can apply to internal catalog items, external catalog items, or non-catalog items. Select one of the following options:
    
      - **Do not allow demand consolidation** – No approved purchase requisition lines are eligible for demand consolidation. This option is selected by default and applies only to purchase requisition lines that require manual processing for purchase order creation.
    
      - **Always allow demand consolidation** – All approved purchase requisition lines are eligible for demand consolidation.
        

        > [!IMPORTANT]
        > <P>If you select the <STRONG>Always allow demand consolidation</STRONG> option on the <STRONG>Demand consolidation</STRONG> tab, but you select the <STRONG>Automatically create purchase orders</STRONG> option on the <STRONG>Manual purchase order creation</STRONG> tab, all purchase requisitions are held for manual processing.</P>

    
      - **Allow demand consolidation under these conditions** – Set the criteria that determine whether approved purchase requisition lines are eligible for demand consolidation. For each type of purchase requisition line, you can set the criteria by procurement category and vendor.
        
        If you select **Allow demand consolidation under these conditions**, you can set the criteria by procurement category and vendor for each type of purchase requisition line. When you select a procurement category, any subcategories for that procurement category are also selected. If you select the **All** option for a specific line type, all purchase requisition lines of that line type are eligible for demand consolidation.

## See also

[Purchase order creation and demand consolidation rule (form)](https://technet.microsoft.com/en-us/library/hh209698\(v=ax.60\))

[Key tasks: Consolidate purchase requisitions](key-tasks-consolidate-purchase-requisitions.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

