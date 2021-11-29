---
title: (IND) Record the approval details for a DFIA or AA license
TOCTitle: (IND) Record the approval details for a DFIA or AA license
ms:assetid: 2c4c458d-9daa-42d5-89b8-8b8b935278f5
ms:mtpsurl: https://technet.microsoft.com/library/JJ664588(v=AX.60)
ms:contentKeyID: 49385664
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (IND)
- india
- DFIA approval
- AA approval
- Advance Authorization approval
- approval details
- approve AA
- approve Advance Authorization
- approve authorization
- approve DFIA
- approve EXIM
- EXIM approval
- Duty Free Import Authorization approval
- approve Duty Free Import Authorization
- authorization approval
audience: Application User
ms.search.region: India
---

# (IND) Record the approval details for a DFIA or AA license 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

After you receive approval from the customs authority for an export-import (EXIM) incentive scheme authorization, use this procedure to enter the approval details in Microsoft Dynamics AX.

1.  Click **General ledger** \> **Common** \> **EXIM Authorization schemes**. In the **Status** column, select an authorization that has a status of **Applied**, and then, on the **Action Pane**, in the **Functions** group, click **Approve**.

2.  In the **Authorization approval details** form, on the **Approval details** FastTab, in the **Authorization number** and **Issue date** fields, enter the reference ID and the date for the authorization.
    
    The dates in the **Import expiration date** and **Export expiration date** fields are calculated from the combination of the issue date and the validity periods that are defined in the **Import validity** and **Export validity** field groups in the **Incentive scheme parameters** form for the relevant incentive scheme.
    
    If the calculated import or export expiration date is not the last day of the month, the expiration date is rounded to the last day of the month.

3.  If the authorization is transferable, select the **Transferable** check box. The authorization must be transferable for you to sell or split it when the export obligation is fulfilled.

4.  In the **Import assessable value** field, enter the extended cost, insurance, and freight (CIF) value for the authorization. Then, in the **Export assessable value** field, enter the extended Free On Board (FOB) value for the authorization.

5.  On the **Tax information** FastTab, in the **Tax ledger posting group** field, select the ledger posting group to use for posting customs duties.

6.  In the **IEC number** field, enter the organization’s Importer Exporter Code (IEC) number.

7.  In the **Transaction date** field, select the date on which to post the authorization to the ledger.

8.  On the **Tax** tab, press CTRL+N to create a new row, and then, in the **Tax component** field, select the component of the tax ledger posting group for which you are entering the amount and the posting information. After you select the tax component, the ledger account that is specified in the **Tax ledger posting groups** form for the incentive scheme’s receivable account appears in the **Ledger account** field.

9.  In the **Amount** field, enter the exempt duty amount in the accounting currency.

10. Select the offset account to use for posting the exempt duty amount. By default, the account that is selected in the **Benefit account** field for the incentive scheme in the **Incentive scheme parameters** form appears in this field, but you can change it.

11. In the **Tax code** field, select the tax code to use for posting the exempt duty amount.

12. Press CTRL+N to add a new row on the **Tax** tab, or, if you have finished entering amounts and tax codes for tax components, click **OK**. The following message appears:
    
    **You are about to approve the authorization license. After approval no changes can be made to this authorization. Do you want to continue?**
    
    Click **Yes** to update the status of the authorization to **Approved**.

To view the details that you specified for the authorization, open the **EXIM Authorization schemes** form, and then, on the **Lines** FastTab, click **Tax information**. The **Posted tax information** form displays the information that you entered in the **Tax ledger posting group**, **IEC number**, **Transaction date**, and **Tax component** fields.

  


