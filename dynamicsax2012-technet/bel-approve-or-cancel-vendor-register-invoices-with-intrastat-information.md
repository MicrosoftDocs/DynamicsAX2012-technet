---
title: (BEL) Approve or cancel vendor register invoices with Intrastat information
TOCTitle: (BEL) Approve or cancel vendor register invoices with Intrastat information
ms:assetid: 48539928-e604-40fe-99be-2a417461e4c2
ms:mtpsurl: https://technet.microsoft.com/library/Hh242399(v=AX.60)
ms:contentKeyID: 36056923
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Belgium
- approve
- vendor invoice
audience: Application User
ms.search.region: Belgium
---

# (BEL) Approve or cancel vendor register invoices with Intrastat information 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can approve or cancel a vendor invoice that contains Intrastat information after the invoice has been registered and posted for approval. For more information, see [(BEL) Create and post a vendor invoice journal and a vendor register with Intrastat information](bel-create-and-post-a-vendor-invoice-journal-and-a-vendor-register-with-intrastat-information.md).

1.  Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice approval journal**.

2.  Press CTRL+N to create a new journal. For more information, see [Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md).

3.  Click **Lines** to open the **Journal voucher** form.

4.  Click **Find vouchers** to open the **Find vouchers** form, which lists the invoice vouchers that are posted to temporary accounts pending approval.

5.  Select the invoice vouchers that contain Intrastat information. Click **Select** to move the selected vouchers to the lower pane, and then click **OK** to transfer them to the **Invoice approval journal** form.
    
    You can also click **Select all** and then click **OK** to select and transfer all the vouchers to the **Invoice approval journal** form.

6.  Select a voucher in the upper pane of the **Journal voucher** form. You can view the transaction lines that are created when the voucher is posted in the lower pane.

7.  If the invoice does not need to be linked to an outstanding purchase order that contains Intrastat information, click **Post** \> **Post** to approve and post the invoice. If the invoice does need to be linked to an outstanding purchase order, click **Functions** \> **Purchase order**, and then click **Post** \> **Post** to approve and post the invoice. If the Intrastat information in the invoice is incorrect and the invoice cannot be approved, click **Functions** \> **Cancel**.
    
    You can reverse a posted invoice. For more information, see [Reverse a transaction](reverse-a-transaction.md).

8.  Close the forms to save your changes.

## See also

[Posting restrictions (form)](https://technet.microsoft.com/library/hh227598\(v=ax.60\))

[Journal voucher - Invoice register (form)](https://technet.microsoft.com/library/aa575517\(v=ax.60\))

[Journal voucher - Invoice journal (form)](https://technet.microsoft.com/library/aa616218\(v=ax.60\))

[(BEL) Transfer vendor invoice transactions and generate an Intrastat declaration](bel-transfer-vendor-invoice-transactions-and-generate-an-intrastat-declaration.md)

  


