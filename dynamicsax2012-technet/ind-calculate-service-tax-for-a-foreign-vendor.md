---
title: (IND) Calculate service tax for a foreign vendor
TOCTitle: (IND) Calculate service tax for a foreign vendor
ms:assetid: 597175e2-8e99-4e21-98cc-0c073257fd9c
ms:mtpsurl: https://technet.microsoft.com/library/JJ677834(v=AX.60)
ms:contentKeyID: 49385799
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.PurchTable
- MsDynAx060.Forms.PurchTable
audience: Application User
ms.search.region: India
---

# (IND) Calculate service tax for a foreign vendor 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012_

Use the **Purchase order** form to create and post an import purchase order. You can calculate the service tax on goods of type **Service** that you import from a foreign vendor.

The service tax fields are available only if you do the following:

  - Select the **Service tax** check box on the **Sales tax** tab in the **General ledger parameters** form.

  - Set up the vendor as a foreign vendor in the **Vendors** form. Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**. Double-click a vendor account. In the **Vendors** form, on the **Tax information** FastTab, select the **Foreign vendor** check box.

<!-- end list -->

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Select or create a purchase order for a foreign vendor. For more information, see [(IND) Create import purchase orders](ind-create-import-purchase-orders.md).

3.  In the **Purchase order** form, on the **Action Pane**, in the **Maintain** group, click **Edit**.

4.  In the **Purchase order lines** area, select an item of type **Service**.

5.  On the **Line details** FastTab, on the **Tax information** tab, in the **Service** field group, the **Recoverable/Expense on tax settlement** check box is selected by default. A selected check box indicates that the service tax is posted to the recoverable account or expense account only when the tax is settled. You can clear the check box if a service tax is not applicable for the selected item.

6.  In the **Service code** field, select the service code that is attached to the item of type **Service**.
    

    > [!NOTE]
    > <P>In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: The accounting code for the service is updated in the <STRONG>Accounting code</STRONG> field based on the service code that you select. For more information, see <A href="ind-set-up-service-codes-for-service-goods.md">(IND) Set up service codes for service goods</A>.</P>



7.  Depending on the version that you are using, do one of the following:
    
      - In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: In the **Service category** field, select one of the following options to indicate the service category for the journal line:
        
          - **Inward** – Select this option when you purchase goods from a vendor.
        
          - **Inter unit or input** – Select this option either when you transfer goods between two units within your legal entity, or when you transfer goods from the legal entity to a subcontractor for additional processing. For example, you can select this option when the goods are manufactured in one unit and then transferred to the packing unit of your legal entity.
        
          - **Others** – Select this option for other service categories. The input tax amount for this category is posted to the expense account instead of the recoverable account or the interim recoverable account.
    
      - In Microsoft Dynamics AX 2012 R2: In the **GTA service category** field, select one of the following options to indicate the category of Goods Transport Agency (GTA) service:
        
          - **Inward** – Select this option when you purchase goods from a vendor.
        
          - **Outward - inter unit/input** – Select this option either when you transfer goods between two units within your legal entity, or when you transfer goods from the legal entity to a subcontractor for additional processing.
        
          - **Others** – Select this option for all other categories of GTA services.

8.  On the **Setup** tab, in the **Sales tax** field group, select a sales tax group and an item tax group for the selected line.

9.  On the **Purchase** tab, in the **Tax** group, click **Sales tax** to view the calculation of the service tax in the **Sales tax transactions** form.

10. Post the details of the purchase order.

The service tax is calculated from the sales tax group and the item sales tax group that you selected for the import order lines.

## See also

[(IND) Activate service tax parameters](ind-activate-service-tax-parameters.md)

[(IND) Calculate service tax for a purchase order](ind-calculate-service-tax-for-a-purchase-order.md)

  


