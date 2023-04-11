---
title: Update vendor batch details during purchase registration
TOCTitle: Update vendor batch details during purchase registration
ms:assetid: 7a8e0d32-82b3-44f2-8cbf-a8f613ecfe2f
ms:mtpsurl: https://technet.microsoft.com/library/Hh352214(v=AX.60)
ms:contentKeyID: 36687849
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- update vendor batch details
- update vendor batch information
- vendor batch details
- vendor batch information
audience: Application User
ms.search.region: Global
---

# Update vendor batch details during purchase registration 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to update vendor batch details for a product during the registration of purchase orders. To use this feature, the following conditions must be true:

  - The batch dimension for the product must be active.

  - The item model group must be set up for vendor batch updates. In the **Item model groups** form, on the **Setup** tab, select the **Purchase Registration** check box.

If a product meets these requirements, and you click **Post all** in the **Inventory registration** form, the **Vendor batch details** form is displayed.

1.  In the **Vendor batch details** form, select the inventory batch to update.

2.   In the **Vendor batch date** field, select the date when the vendor specifies the batch was created. To use this vendor batch date as the batch date for this inventory batch, select the **Use vendor date** check box.

3.  In the **Vendor expiry date** field, select the date when the vendor specifies the batch expires. To use the vendor expiration date as the batch expiration date for this inventory batch, select the **Use vendor expiry date** check box.

4.  In the **Country/region of Origin 1** and **Country/region of Origin 2** fields, select the first country and second country of origin, if this information is provided by the vendor. This information may be used to meet Country of Origin Labeling (COOL) requirements. This is used as information only.

5.  In the **Vendor batch number** field, enter the batch or lot number that is specified by the vendor.

6.  Save the changes.

## See also

[Inventory registration (form)](https://technet.microsoft.com/library/aa615731\(v=ax.60\))

[Item model groups (form)](https://technet.microsoft.com/library/aa577092\(v=ax.60\))

  


