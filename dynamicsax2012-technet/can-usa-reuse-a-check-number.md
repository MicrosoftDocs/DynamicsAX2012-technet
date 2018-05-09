---
title: (CAN, USA) Reuse a check number
TOCTitle: (CAN, USA) Reuse a check number
ms:assetid: ada2b2b3-d70d-4bac-b3ef-06904a55bed9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg243102(v=AX.60)
ms:contentKeyID: 36058929
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (CAN, USA) Reuse a check number 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can reuse check numbers if you enabled the functionality when you set up bank parameters. For example, if a check is damaged while it is being printed, you can print the same check number on a new check. The original information is voided and replaced with the reprinted check information.


> [!NOTE]
> <P>(CAN, USA) This functionality is available only to legal entities whose primary address is in the United States or Canada.</P>



1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.
    
    –or–
    
    Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Select a journal, and then click **Lines**.

3.  Click **Payment status** \> **Set status of the payment to None for vendor payment journal**. The payment status is changed to **None**.

4.  To reprint the check, in the **Journal voucher** form, click **Functions** \> **Generate payments**.

5.  In the **Method of payment** field, select a method of payment with **Check** as the export format.

6.  Select the **Show format dialog** check box, and then click **OK** to open the **Payment by check** form.
    

    > [!NOTE]
    > <P>You can verify that the check number is the same check number that was on the original check.</P>



7.  Click **OK**. The check is printed again with the same check number that was used previously.

8.  Close the forms to save your changes.

## See also

[(CAN, USA) Set up a bank parameter to reuse check numbers](can-usa-set-up-a-bank-parameter-to-reuse-check-numbers.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

