---
title: Void unposted checks
TOCTitle: Void unposted checks
ms:assetid: f4c977f2-0122-427b-89f5-baedac87bd23
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa551642(v=AX.60)
ms:contentKeyID: 37832551
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Void unposted checks 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to void checks. You might be unable to use checks that you previously printed or tried to print. Some unused checks must be voided, such as checks that were damaged during or after printing.

In Microsoft Dynamics AX 2012 R3 or cumulative update 6 or later for AX 2012 R2, if your organization uses positive pay, the check that you are voiding might already be included in a positive pay file. In this case, the voided check is included the next time that a positive pay file is generated for the bank account, and the check is marked as canceled in the positive pay file. For information about how to create a positive pay file, see [Generate and print vendor checks](generate-and-print-vendor-checks.md).


> [!NOTE]
> <P>You can use this procedure only if the checks are not posted.</P>



1.  Open the appropriate payment journal, and then click **Lines**.

2.  Select the lines that you printed checks for.

3.  Click **Payment status** \> **Rejected**. The check numbers are no longer displayed in the journal.

4.  Click **Cash and bank management** \> **Common** \> **Bank accounts**. Select the appropriate bank account, and then click **Checks**.

5.  Verify that checks have been voided correctly. Checks that have been voided a value of **Void** in the **Status** field.

## See also

[Generate and print vendor checks](generate-and-print-vendor-checks.md)

  


