---
title: (RUS) Reject a cash order
TOCTitle: (RUS) Reject a cash order
ms:assetid: c5462f16-388d-4781-bca3-95a95e335b9d
ms:mtpsurl: https://technet.microsoft.com/library/JJ711600(v=AX.60)
ms:contentKeyID: 49387924
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Reject a cash order 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You can reject (void) an open cash journal and any cash journals that require confirmation. An incorrect document with a **Confirmed** status can also be rejected. If a voided cash order is posted to the journal, no transaction is created. When you enter the next cash vouchers into the journal, the sequential numbering continues, taking the voided order into account.

1.  Click **Cash and bank management** \> **Setup** \> **Cash and bank management parameters**.

2.  Select the **Use Confirm status** check box to post a cash voucher with confirmation.

3.  Press CTRL+S or close the form.

4.  Click **Cash and bank management** \> **Journals** \> **Slip journal**.
    

    > [!NOTE]
    > <P>For more information, see "Journal header (form)" in the Applications and Business Processes Help.</P>



5.  Select the journal to reject.

6.  Click **Lines** to open the **Journal voucher** form, and select the cash order line to reject.

7.  To reject the cash order, click **Documents approval** \> **Reject**.
    

    > [!NOTE]
    > <P>The cash order must be generated in the slip journal and confirmed using the <STRONG>Documents approval</STRONG> &gt; <STRONG>Confirm</STRONG> button. The <STRONG>Approval status</STRONG> must be <STRONG>Confirmed</STRONG> and the cash order must be created according to the voucher.</P>



8.  After the cash order is rejected, its **Approval status** is displayed as **Rejected**.

9.  Press CTRL+S or close the form.

## See also

[(RUS) Register reimbursement or disbursement slips](rus-register-reimbursement-or-disbursement-slips.md)

[(RUS) Set up a cash journal for cash disbursement and reimbursement](rus-set-up-a-cash-journal-for-cash-disbursement-and-reimbursement.md)

  


