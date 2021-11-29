---
title: (IND) Approve an EPCG license
TOCTitle: (IND) Approve an EPCG license
ms:assetid: 86e7c671-61d3-4225-998a-776b32637398
ms:mtpsurl: https://technet.microsoft.com/library/JJ677989(v=AX.60)
ms:contentKeyID: 49385952
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (IND)
- india
- EPCG license
- Approve EPCG license
- EPCG license approval
audience: Application User
ms.search.region: India
---

# (IND) Approve an EPCG license 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Before you can assign an Export Promotion Capital Goods (EPCG) incentive license to import and export orders, you must approve it. To approve an EPCG license, you assign exportable items and vendors to the EPCG license. You also set up export obligation periods and add bank guarantee details for the EPCG license.

1.  Click **General ledger** \> **Common** \> **EXIM EPCG Schemes**. Open an EPCG scheme that has a status of **Created**.

2.  In the **EXIM EPCG Schemes** form, on the **Overview** FastTab, click **Functions** \> **Approve**.

3.  In the **Approval EPCG schemes** form, on the **Authorization information** FastTab, in the **License number** field, enter the EPCG license number that was assigned to your organization. Enter information in the remaining fields in the **Approval details** and **Currency** field groups.

4.  In the **Export obligation** field group, enter the license details for importing and exporting items for the EPCG incentive scheme.

5.  On the menu bar, click **Exportable items**.

6.  In the **Exportable items** form, select the items that qualify for export under the terms of the EPCG incentive license, and then close the form.

7.  In the **Approval EPCG schemes** form, click **Export obligation period**.

8.  In the **Create export obligation periods** form, click **New**. Enter a description of the export obligation period. By default, the period interval is years. Enter the remaining details for the export obligation period.
    

    > [!NOTE]
    > <P>The sum of the periods in the <STRONG>Units</STRONG> field must equal the total obligation period that you select in the <STRONG>Approval EPCG schemes</STRONG> form. Also, the percentage for all periods must be less than or equal to 100.</P>



9.  Close the **Create export obligation periods** form.

10. In the **Approval EPCG schemes** form, click **Vendor details**.

11. In the **Vendor details** form, select the vendors from whom you will be importing items for the EPCG incentive scheme.

12. Close the **Vendor details** form.

13. In the **Approval EPCG schemes** form, click **Bank guarantee details**.

14. In the **Bank guarantee details** form, enter the guarantee information for the bank that you use to pay for imported items.

15. In the **Approval EPCG schemes** form, click **OK**.

The EPCG license is approved only under the following conditions:

  - The value for the remaining percentage is zero in the **Create export obligation periods** form.

  - The total value of the units is equal to the value of the total export obligation in the **Create export obligation periods** form.

  - The export obligation amount in the **Approval EPCG schemes** form is equal to the value in the **Total export obligation amount** field in the **Create export obligation periods** form.

  - The value in the **Obligation period** field in the **Approval EPCG schemes** form is equal to the value in the **Total export obligation period** field in the **Create export obligation periods** form.

## See also

[(IND) About the EXIM Export Promotion Capital Goods (EPCG) incentive scheme](ind-about-the-exim-export-promotion-capital-goods-epcg-incentive-scheme.md)

[(IND) Create a primary EPCG license](ind-create-a-primary-epcg-license.md)

[(IND) Approval EPCG schemes (form)](https://technet.microsoft.com/library/jj710885\(v=ax.60\))

  


