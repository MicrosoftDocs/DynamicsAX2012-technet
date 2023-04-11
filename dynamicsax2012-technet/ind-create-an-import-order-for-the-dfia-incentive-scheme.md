---
title: (IND) Create an import order for the DFIA incentive scheme
TOCTitle: (IND) Create an import order for the DFIA incentive scheme
ms:assetid: 5eca8174-9c81-49c0-bbe7-a22d6d717f70
ms:mtpsurl: https://technet.microsoft.com/library/JJ677854(v=AX.60)
ms:contentKeyID: 49385818
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (IND)
- India
- customs incentive scheme
- EXIM incentive scheme
- India customs
- incentive scheme
- DFIA
- Duty Free Import Authorization
- import order
audience: Application User
ms.search.region: India
---

# (IND) Create an import order for the DFIA incentive scheme 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

After you receive a Duty Free Import Authorization (DFIA) from the customs authority, you can use the authorization to claim exemption of duty on goods that are being imported. Use this procedure to create an import order and attach the DFIA to it.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  On the **Action Pane**, on the **Purchase order** tab, in the **New** group, click **Purchase order**.

3.  In the **Create purchase order** form, in the **Vendor account** field, select the customs vendor, and then select the **Import order** check box.

4.  Enter any additional field values, and then click **OK** to create a new purchase order.
    
    For detailed information about how to create a purchase order, see [Create purchase order (form)](https://technet.microsoft.com/library/aa570189\(v=ax.60\)) and [(IND) Create purchase order (modified form)](https://technet.microsoft.com/library/jj664490\(v=ax.60\)).

5.  Add a purchase order line, and then, at the bottom of the **Line details** FastTab, click the **Setup** tab.

6.  In the **Sales tax** field group, select the item sales tax group and the sales tax group.

7.  At the bottom of the **Line details** FastTab, click the **Tax information** tab.
    
    The **Customs tariff code** field in the **Customs** field group displays the customs tariff code that is associated with the product in the **Released product details** form. If this field is blank, select a customs tariff code to enable the fields in the **EXIM incentive scheme** field group.

8.  In the **EXIM incentive scheme** field group, in the **Incentive scheme group** field, select the incentive scheme group.
    
    The **Port ID** field displays the export-import (EXIM) port that is associated with the selected incentive scheme group in the **Incentive scheme groups** form.
    
    The **Product group** field displays the product group that is associated with the product in the **Released product details** form.
    

    > [!TIP]
    > <P>You can view product information about the import assessable value and the importable quantity balance for the authorization. On the <STRONG>Purchase order lines</STRONG> FastTab, click <STRONG>Purchase order line</STRONG>, and then click <STRONG>EXIM - DFIA</STRONG> to open the <STRONG>Import details</STRONG> form.</P>



9.  Add another purchase order line or, if the purchase order is complete, confirm the purchase order. To confirm the purchase order, click the **Purchase** tab, and then, in the **Generate** field group, do one of the following:
    
      - To confirm and print the purchase order, click **Purchase order**.
    
      - To confirm the purchase order without printing it, click **Confirm**.

  


