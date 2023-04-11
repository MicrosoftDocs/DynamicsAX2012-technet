---
title: (BRA) Create and post a purchase order for a foreign vendor
TOCTitle: (BRA) Create and post a purchase order for a foreign vendor
ms:assetid: f32e0584-ed77-4ea1-af42-9cacaa38319f
ms:mtpsurl: https://technet.microsoft.com/library/JJ915360(v=AX.60)
ms:contentKeyID: 50874341
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.PurchTable
- Forms.VendEditInvoice
- MsDynAx060.Forms.PurchTable
- MsDynAx060.Forms.VendEditInvoice
audience: Application User
ms.search.region: Brazil
---

# (BRA) Create and post a purchase order for a foreign vendor 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to create and post a purchase order for a foreign vendor. Before you post the purchase order to import items, you must specify the import declaration information (the addition number and import declaration number) to generate an import fiscal document. An import fiscal document records transit information about the items that you import. This document is used to release the items from customs, and to validate the entry of the items in the warehouse of the legal entity.

Before you can create and post the purchase order for a foreign vendor, you must select the **Generate incoming fiscal document** check box on the **Fiscal information** FastTab in the **Vendors** form.


> [!NOTE]
> <P>In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: You can also issue an import fiscal document when you create a purchase order to import services from a foreign vendor.</P>



1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Create a purchase order for a foreign vendor. For more information, see [(BRA) Create and post a purchase order](bra-create-and-post-a-purchase-order.md).

3.  On the **Action Pane**, click **Invoice** \> **Invoice**.

4.  In the **Vendor invoice** form, in the **Lines** area, in the **Addition** field, enter the addition number for the line.
    

    > [!NOTE]
    > <P>In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: When you import a service, it is not mandatory to specify the addition number.</P>



5.  On the **Action Pane**, click **Header view**, and then in the **Foreign trade** FastTab, click **Add import declaration** to open the **Import declaration** form, and then specify the information for the following fields:
    
      - **Import declaration number** – Enter the identification number of the import declaration document.
        

        > [!NOTE]
        > <P>In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: When you import a service, it is not mandatory to specify the import declaration number.</P>

    
      - **Date** – Enter the date when the import declaration is issued by the customs authority.
    
      - **Port** – Select the identification code of the port where the imported item is received.
    
      - **DI type** – Select the import declaration type.
    
      - **Nationalization date** – Enter the date when the ownership of the imported item is transferred to the company in the Brazilian market.
    
      - **Draw back number** – Enter the identification number of the draw back operation.

6.  Close the form.

7.  In the **Vendor invoice** form, on the **Foreign trade** FastTab, in the **Import declaration number** field, select the identification number of the import declaration document.

8.  On the **Action Pane**, click **Post** \> **Post** to post the vendor invoice and generate the import fiscal document.

## See also

[(BRA) Import declaration (form)](https://technet.microsoft.com/library/jj863737\(v=ax.60\))

[(BRA) Purchase order (modified form)](https://technet.microsoft.com/library/jj911277\(v=ax.60\))

[(BRA) Vendors (modified form)](https://technet.microsoft.com/library/jj933505\(v=ax.60\))

[(BRA) Vendor invoice (modified form)](https://technet.microsoft.com/library/jj898464\(v=ax.60\))

[(BRA) Port (modified form)](https://technet.microsoft.com/library/jj923392\(v=ax.60\))

[(BRA) About import fiscal documents](bra-about-import-fiscal-documents.md)

  


