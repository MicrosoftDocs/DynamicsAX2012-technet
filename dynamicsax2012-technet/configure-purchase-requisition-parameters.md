---
title: Configure purchase requisition parameters
TOCTitle: Configure purchase requisition parameters
ms:assetid: 5eba02e2-e783-426c-aaa7-c46922c6d86b
ms:mtpsurl: https://technet.microsoft.com/library/Hh209127(v=AX.60)
ms:contentKeyID: 36057583
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- purchase requisition
- purchase requistions
audience: Application User
ms.search.region: Global
---

# Configure purchase requisition parameters 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you create purchase requisitions, you can configure the purchase requisition control rule to set the parameters that are used to process purchase requisitions. By using the purchase requisition control rule, you can do the following:

  - Identify the fields on a purchase requisition that must contain a value before it can be submitted for review.

  - Enforce order quantity restrictions.

  - Set the requested date as the accounting date on purchase requisitions.

  - Select whether to allow preparers to change the delivery address on a purchase requisition.

If you do not configure the purchase requisition control rule, the default parameters for processing purchase requisitions applies. No fields on the purchase requisition will require a value before the purchase requisition can be submitted for workflow, no order quantity restrictions will be enforced, the requested date and the accounting date can differ, and a preparer will be permitted to change the delivery address on a purchase requisition.

## Configure purchase requisition parameters

1.  Click **Procurement and sourcing** \> **Setup** \> **Policies** \> **Purchasing policies**.

2.  On the **Purchasing policies** list page, open or create a purchasing policy.

3.  In the **Purchasing policy** form, on the **Policy rules** FastTab, in the **Policy rule type:** list, select **Purchase requisition control rule**, and then click **Create policy rule**.

4.  In the **Purchase requisition control rule** form, view or enter the date range for which the purchase requisition control rule is valid.

5.  On the **Workflow submission** FastTab, set the workflow requirement for each purchase requisition line field in the list. Select one of the following options:
    
      - **Not required** – The selected field does not require a value before the requisition can be submitted for review. This is the default setting.
    
      - **Required** – The selected field must contain a valid value before the requisition can be submitted for review.
    
      - **Conditional** – When certain conditions are met, the selected field must contain a valid value before the requisition can be submitted for review. If you select this setting, use the conditions pane to define the conditions that apply.

6.  On the **Order quantities** FastTab, set the order quantity restrictions that apply to purchase requisition lines. Select or clear the check box for the following options:
    
      - **Enforce maximum order quantity restrictions** – If this check box is selected, users cannot override the maximum quantity that is specified for the item on a purchase requisition. If a user specifies a quantity that is larger than the maximum quantity allowed, the quantity is automatically reset to the maximum quantity.
        
        If this check box is cleared, users can override the maximum quantity, but a message is displayed to say that the quantity exceeds the maximum quantity allowed.
    
      - **Enforce minimum order quantity restrictions** – If this check box is selected, users cannot override the minimum order quantity that is specified for the item on a purchase requisition. The quantity is automatically reset to the required minimum quantity.
        
        If this check box is cleared, users can override the minimum quantity, but a message is displayed to say that the quantity does not meet the required minimum.
    
      - **Enforce multiple order quantity restrictions** - If this check box is selected, users can enter a quantity that does not match the specified multiple for item quantity. However, a message is displayed, and the quantity is automatically rounded up to match the required multiple.
        
        If this check box is cleared, users can enter a quantity that does not match the specified multiple for item quantity. However, a message is displayed, and users can round the quantity up to match the required multiple.
    
    For more information about how to configure order settings for a product, see [Order settings (form)](https://technet.microsoft.com/library/hh209541\(v=ax.60\)).

7.  On the **Dates** FastTab, select the **Use requested date as accounting date:** check box to use the requested date as the default accounting date.
    
    If the check box is selected, the accounting date field becomes read-only and the accounting date is always the same as the requested date on the purchase requisition. The accounting date is used for ledger control and budget posting. It is also used to determine whether the requester has permission to enter purchase requisitions in that fiscal period.

8.  On the **Address** FastTab, select the **Allow new delivery address** check box to allow a preparer to enter a new delivery address for a line item on a purchase requisition.

## See also

[Purchase requisition control rule (form)](https://technet.microsoft.com/library/hh208589\(v=ax.60\))

  


