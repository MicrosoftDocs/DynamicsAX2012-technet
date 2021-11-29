---
title: (IND) About calculating TDS based on PAN availability
TOCTitle: (IND) About calculating TDS based on PAN availability
ms:assetid: 88e88c5b-efea-4550-b438-b832bdb56429
ms:mtpsurl: https://technet.microsoft.com/library/JJ678001(v=AX.60)
ms:contentKeyID: 49385961
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) About calculating TDS based on PAN availability 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When you apply tax deducted at source (TDS) to vendor payments, you must specify the vendor’s Permanent Account Number (PAN). If the PAN is not available, TDS is calculated at the highest rate.

You can verify a vendor’s Permanent Account Number (PAN) availability in the **Vendors** form, on the **Tax information** FastTab. If the **Status** field is set to **Applied**, **Invalid**, or **Not available**, the TDS is calculated at the highest rate.

When you generate vendor statements or reports, the PAN status of the vendor, as it is recorded in the system at the time of reporting, is included in the statement or report. The PAN status for the vendor is a part of what determines the rate of the TDS.

## Set up TDS calculation for vendors

Complete the following tasks to calculate and deduct TDS for vendors:

  - Set up general ledger parameters. For more information, see [(IND) General ledger parameters (modified form)](https://technet.microsoft.com/library/jj677901\(v=ax.60\)).

  - Set up a chart of accounts.

  - Set up withholding tax groups and withholding tax components. For more information, see [(IND) Withholding tax groups (modified form)](https://technet.microsoft.com/library/jj677874\(v=ax.60\)), and [(IND) Withholding tax components (form)](https://technet.microsoft.com/library/jj664790\(v=ax.60\)).

  - Set up withholding tax component groups and withholding tax authorities. For more information, see [(IND) Set up withholding tax component groups for TDS tax types](ind-set-up-withholding-tax-component-groups-for-tds-tax-types.md), [(IND) Withholding tax component groups (form)](https://technet.microsoft.com/library/jj678017\(v=ax.60\)), [(IND) Set up withholding tax authorities for TDS tax types](ind-set-up-withholding-tax-authorities-for-tds-tax-types.md), and [(IND) Withholding tax authorities (form)](https://technet.microsoft.com/library/jj664871\(v=ax.60\)).

  - Set up withholding tax settlement periods and withholding tax reporting types.

You must also complete the following procedures to calculate and deduct TDS based on PAN availability:

  - [(IND) Set up withholding tax codes for TDS tax types](ind-set-up-withholding-tax-codes-for-tds-tax-types.md)

  - [(IND) Define withholding tax information for vendors](ind-define-withholding-tax-information-for-vendors.md)

  


