---
title: (IND) Revalidate an EPCG license for domestic purchasing
TOCTitle: (IND) Revalidate an EPCG license for domestic purchasing
ms:assetid: 4f063203-c9e1-40b1-97dd-809c61cf8c4e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664691(v=AX.60)
ms:contentKeyID: 49385765
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (IND)
- EPCG license
- revalidate
- Revalidate EPCG license
---

# (IND) Revalidate an EPCG license for domestic purchasing 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

To use an Export Promotion Capital Goods (EPCG) license for purchases from indigenous suppliers, you must revalidate the license so that its status is set to **Domestic**.

You can revalidate an EPCG license only when the following conditions are true:

  - The authorization status of the EPCG incentive scheme is **Approved**.

  - No import transactions refer to this EPCG license.

  - The status of the EPCG license is **Original**.

<!-- end list -->

1.  Click **General ledger** \> **Common** \> **EXIM EPCG Schemes**. Open an EPCG scheme that has a status of **Approved**.

2.  In the **EXIM EPCG Schemes** form, on the **Overview** FastTab, select an approved EPCG license.

3.  On the **Lines** FastTab, click **Functions** \> **Revalidation**.

4.  In the **Revalidation details** form, in the **Certificate number** field, enter the certificate number for the EPCG license.

5.  In the **Issue date/time** field, specify the date and time when the certificate was issued.

6.  Click **OK** to close the **Revalidation details** form.

In the **EXIM EPCG Schemes** form, on the **Lines** FastTab, the status for the selected EPCG license is **Domestic**.

## See also

[(IND) Create a primary EPCG license](ind-create-a-primary-epcg-license.md)

[(IND) Create an EXIM EPCG scheme for a technology upgrade EPCG license](ind-create-an-exim-epcg-scheme-for-a-technology-upgrade-epcg-license.md)

[(IND) Approve an EPCG license](ind-approve-an-epcg-license.md)

[(IND) Extend the export obligation period for an EPCG license](ind-extend-the-export-obligation-period-for-an-epcg-license.md)

[(IND) Redeem an EPCG license](ind-redeem-an-epcg-license.md)

[(IND) Attach an EPCG incentive scheme to an import order](ind-attach-an-epcg-incentive-scheme-to-an-import-order.md)

[(IND) EXIM EPCG schemes (form)](https://technet.microsoft.com/en-us/library/jj677817\(v=ax.60\))

[(IND) Revalidation details (form)](https://technet.microsoft.com/en-us/library/jj710940\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

