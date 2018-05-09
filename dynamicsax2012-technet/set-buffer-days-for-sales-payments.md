---
title: Set buffer days for sales payments
TOCTitle: Set buffer days for sales payments
ms:assetid: 0fe68c63-993c-4db5-86f9-3d7bae9b3cbc
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242136(v=AX.60)
ms:contentKeyID: 36056022
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- buffer days
- general buffer days
- invoice frequency
- sales payments
---

# Set buffer days for sales payments 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can specify how many days are allowed for a grace period before a sales payment is due.


> [!NOTE]
> <P>Buffer days for sales payments apply to time-and-material projects only.</P>



1.  Click **Project management and accounting** \> **Setup** \> **Project management and accounting parameters**.

2.  In the **Project parameters** form, in the left pane, click **Forecast**.

3.  In the **General buffer days** field, enter a number of buffer days.

**Example**

In the **Project contracts** form, you select **Monthly** in the **Invoice frequency** field, which means that the invoice date of the forecast is set to the end of the current month according to the project date.

The project date is set to March 16, 2010.

The invoice date is set to March 31, 2010.

In the **Project parameters** form, 4 is entered in the **General buffer days** field.

The payment is due on April 4, 2010, which is March 31, 2010 + 4 days.

## See also

[Specify the invoice frequency for an existing project contract](specify-the-invoice-frequency-for-an-existing-project-contract.md)

[Project management and accounting parameters (form)](https://technet.microsoft.com/en-us/library/aa599440\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

