---
title: (ESP) Generate Spanish checks
TOCTitle: (ESP) Generate Spanish checks
ms:assetid: 327997ba-a7a3-4960-aab5-0394d1ced056
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg231037(v=AX.60)
ms:contentKeyID: 36056533
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (ESP) Generate Spanish checks [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can print checks that follow the standards that are required for checks in Spain. Use the **Journal voucher** form to generate Spanish checks.

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Select a journal, and then click **Lines**.

3.  Click **Functions** \> **Generate payments**.

4.  In the **Method of payment** field, select a method of payment that uses the **Check** export file format.

5.  In the **Bank account** field, select a bank account that uses the **Spanish check format**.
    

    > [!NOTE]
    > <P>If the currency in the payment journal line is different from the currency of the bank account, you can still generate a check if the check layout is set up to use other currencies.</P>



6.  Click **Dialog** to open the **Payment by check** form.

7.  Select the **Payment advice** check box to print the payment advice report when checks are printed.

8.  Click **OK**.

9.  In the **Generate payments** form, click **OK** to close the form.

## See also

[Print copies of payments as non-negotiable checks](print-copies-of-payments-as-non-negotiable-checks.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

