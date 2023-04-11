---
title: (BEL) Transfer vendor invoice transactions and generate an Intrastat declaration
TOCTitle: (BEL) Transfer vendor invoice transactions and generate an Intrastat declaration
ms:assetid: b73513e0-a939-49a6-94d7-c911d43e71e1
ms:mtpsurl: https://technet.microsoft.com/library/Hh242757(v=AX.60)
ms:contentKeyID: 36059100
author: tfehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Belgium
- intrastat
- vendor invoice
audience: Application User
ms.search.region: Belgium
---

# (BEL) Transfer vendor invoice transactions and generate an Intrastat declaration 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you can transfer vendor invoice transactions and generate an Intrastat declaration, you must create and post vendor invoices from invoice journals or invoice registers that contain Intrastat information for your vendors. For more information, see [(BEL) Create and post a vendor invoice journal and a vendor register with Intrastat information](bel-create-and-post-a-vendor-invoice-journal-and-a-vendor-register-with-intrastat-information.md).

1.  Click **Organization administration** \> **Periodic** \> **Foreign trade** \> **Intrastat**.

2.  Click **Transfer BE**.

3.  Select the **Vendor invoice** check box and click **OK** to transfer the vendor invoice transactions to the **Intrastat** form.

4.  In the **Intrastat** form, click **Output** \> **Diskette BE** to open the **Create Intrastat diskette in Belgian layout** form, and enter the required details. For more information, see [(BEL) Make diskette for Intrastat in Belgian layout (class form)](https://technet.microsoft.com/library/aa620219\(v=ax.60\)).

5.  Click **OK** to generate the Intrastat declaration.
    

    > [!NOTE]
    > <P>If you select a shipment batch date that includes a reversed invoice containing Intrastat information, the reversed invoice is reversed and transferred.</P>



6.  Close the form to save your changes.

## See also

[(BEL) Approve or cancel vendor register invoices with Intrastat information](bel-approve-or-cancel-vendor-register-invoices-with-intrastat-information.md)

[Reverse a transaction](reverse-a-transaction.md)

  


