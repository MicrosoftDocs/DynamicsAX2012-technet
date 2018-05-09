---
title: (BRA) Set up taxation origin for items
TOCTitle: (BRA) Set up taxation origin for items
ms:assetid: b74e8659-0ecd-438e-8226-82e163f2aac7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ710601(v=AX.60)
ms:contentKeyID: 49384490
ms.date: 04/25/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.EcoResProductDetailsExtended
- Forms.EcoResProductPerCompanyListPage
- BRA
- Brazil
- BR-00043
- taxation origin
---

# (BRA) Set up taxation origin for items 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up the taxation origin for items. This information is used when you post an incoming or outgoing fiscal document.

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Double-click a product, or on the **Action Pane**, click **Product** to create a released product. For more information, see [Key tasks: Release products](key-tasks-release-products.md) and [Key tasks: Define products](key-tasks-define-products.md).

3.  Depending on the version that you are using, do one of the following:
    
      - In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: In the **Released product details** form, on the **Fiscal information** FastTab, in the **Taxation origin** field, select one of the following options to indicate the taxation origin for the released product:
        
          - **National, not related to codes 3 to 5**
        
          - **Imported, direct import, not related to code 6**
        
          - **Imported, acquired in internal market, and not related to code 7**
        
          - **National, import content greater than 40 percent**
        
          - **National, production compliant with Decreto-Lei nº 288/67, and laws nºs 8.248/91, 8.387/91, 10.176/01 e 11.484/07**
        
          - **National, import content lower than or equal to 40 percent**
        
          - **Imported, direct import, no similar item in internal market, and included in the CAMEX list and natural gas**
        
          - **Imported, acquired in internal market, with no similar in country/region, and included in the CAMEX list and natural gas**
    
      - In Microsoft Dynamics AX 2012 R2: In the **Released product details** form, on the **Fiscal information** FastTab, in the **Taxation origin** field, select **National (produced in country/region)**, **Direct import (produced abroad)**, or **Import acquired internally (produced abroad)** as the taxation origin for the product.

## See also

[(BRA) Brazilian parameters (form)](https://technet.microsoft.com/en-us/library/jj822920\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

