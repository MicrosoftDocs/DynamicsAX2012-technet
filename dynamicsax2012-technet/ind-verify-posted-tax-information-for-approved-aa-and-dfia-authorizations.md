---
title: (IND) Verify posted tax information for approved AA and DFIA authorizations
TOCTitle: (IND) Verify posted tax information for approved AA and DFIA authorizations
ms:assetid: bf82fdcf-070a-4504-b7ae-1dde9db814a3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664836(v=AX.60)
ms:contentKeyID: 49386166
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- posted
- tax information
- (IND)
- India
audience: Application User
ms.search.region: India
---

# (IND) Verify posted tax information for approved AA and DFIA authorizations 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

After an application for an export-import (EXIM) license that is eligible for the Advance Authorization (AA) or Duty Free Import Authorization (DFIA) incentive scheme is approved by the customs authority, use this procedure to view posted tax amounts that are exempt from customs duty. You can also view the ledger accounts and tax codes that were updated when the tax amounts were posted.

1.  Click **General ledger** \> **Common** \> **EXIM Authorization schemes**. On the list page, select an approved authorization for which you want to view posted tax information, and double-click it to open the **EXIM Authorization schemes** form. If necessary, select a different value in the **Authorization type** field.

2.  On the **Lines** FastTab, click **Tax information**.
    
    At the top of the **Posted tax information** form, the **Tax ledger posting group**, **IEC number**, and **Transaction date** fields display information that you entered when you approved, extended, or sold the authorization.
    
    The source of the information in the **Posted tax information** form is indicated in the **License status** field on the **Lines** FastTab in the **EXIM Authorization schemes** form.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>License status</p></th>
    <th><p>Information source</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Original</strong></p></td>
    <td><p><strong>Authorization approval details</strong> form</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Extended</strong></p></td>
    <td><p><strong>Create extension</strong> form</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Sold</strong></p></td>
    <td><p><strong>Authorization sale details</strong> form</p></td>
    </tr>
    </tbody>
    </table>
    
    For information about the **Posted tax information** form, see [(IND) Posted tax information (form)](https://technet.microsoft.com/en-us/library/jj664909\(v=ax.60\)).

3.  To view the posted voucher entries, click the **Voucher** button at the top of the **Posted tax information** form to open the **Voucher transactions** form. The voucher transactions appear for each tax component that you entered in the **Tax component** field when you approved, extended, or sold the authorization.
    
    The sources for the accounts that are used in the ledger postings are as follows:
    
      - The debit is to the account that is specified as the receivable account for the applicable incentive scheme on the **Ledger accounts** FastTab in the **Tax ledger posting groups** form.
    
      - The credit is to the account that is specified as the benefit account for the applicable incentive scheme in the **Incentive scheme parameters** form.
    
    For information about the **Voucher transactions** form, see [Voucher transactions (form)](https://technet.microsoft.com/en-us/library/aa583215\(v=ax.60\)).

## See also

[(IND) Authorization approval details (form)](https://technet.microsoft.com/en-us/library/jj677814\(v=ax.60\))

[(IND) Enter the authorization approval details for DFIA](ind-enter-the-authorization-approval-details-for-dfia.md)

[(IND) Create extension (form)](https://technet.microsoft.com/en-us/library/jj664454\(v=ax.60\))

[(IND) Extend the authorization period for a DFIA license](ind-extend-the-authorization-period-for-a-dfia-license.md)

[(IND) Authorization sale details (form)](https://technet.microsoft.com/en-us/library/jj677924\(v=ax.60\))

[(IND) Record the sale of a DFIA license](ind-record-the-sale-of-a-dfia-license.md)

[(IND) EXIM Authorization schemes (form)](https://technet.microsoft.com/en-us/library/jj664625\(v=ax.60\))

[(IND) Tax ledger posting groups (form)](https://technet.microsoft.com/en-us/library/jj664546\(v=ax.60\))

  


