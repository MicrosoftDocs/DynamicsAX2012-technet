---
title: (BRA) Specify fiscal information for a purchase requisition
TOCTitle: (BRA) Specify fiscal information for a purchase requisition
ms:assetid: 20b5b793-2c1a-43cd-9733-76809119e3e3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ910966(v=AX.60)
ms:contentKeyID: 52075241
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- purchase requisition
- BRA
- Brazil
- fiscal information
- purchase requistion form
---

# (BRA) Specify fiscal information for a purchase requisition 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can specify the fiscal information for a purchase requisition by using the **Purchase requisitions** form. Taxes are based on the vendor, item, and fiscal information that is available on a purchase requisition line, such as the Código Fiscal de Operações e Prestações (CFOP) and service code.

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase requisitions** \> **All purchase requisitions**.

2.  Double-click a purchase requisition.

3.  In the **Purchase requisitions** form, on the **Purchase requisition lines** FastTab, click **Details**.

4.  On the **Fiscal information** FastTab, in the **CFOP** field, select the CFOP code for the transaction. The CFOP code or list of CFOP codes that is available depends on the order type, operation type, delivery location of the fiscal establishment, and location of the vendor.
    

    > [!NOTE]
    > <P>This field is available only when the vendor is specified on the purchase requisition line.</P>



5.  In the **CFPS code** field, enter the fiscal operation for services (CFPS) code for the purchase requisition line.

6.  In the **Service code** field, enter the fiscal classification code for services.
    

    > [!NOTE]
    > <P>This field is available only if the purchase requisition is created for a service.</P>



## See also

[(BRA) Purchase requisitions - lines (modified form)](https://technet.microsoft.com/en-us/library/jj923406\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

