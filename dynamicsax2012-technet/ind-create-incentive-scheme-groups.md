---
title: (IND) Create incentive scheme groups
TOCTitle: (IND) Create incentive scheme groups
ms:assetid: 27d303a2-e17b-49f7-bdae-6b91ea24854a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664572(v=AX.60)
ms:contentKeyID: 49385650
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (IND)
- India
- AA
- Advance Authorization
- customs incentive scheme
- EXIM incentive scheme
- India customs
- incentive scheme
- DFIA
- EPCG
- customs scheme group
- Duty Free Import Authorization
- EXIM group
- Export Promotion Capital Goods
- incentive scheme group
- scheme group
audience: Application User
ms.search.region: India
---

# (IND) Create incentive scheme groups 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can group incentive schemes, and then attach the group to import orders and export orders. By using incentive scheme groups, you can apply multiple Advance Authorization (AA), Duty Free Import Authorization (DFIA), and Export Promotion Capital Goods (EPCG) incentive schemes to the same eligible goods.


> [!NOTE]
> <P>The <STRONG>Incentive scheme groups</STRONG> form is available only if the <STRONG>Activate incentive schemes</STRONG> check box is selected in the <STRONG>Sales tax</STRONG> area in the <STRONG>General ledger parameters</STRONG> form.</P>



1.  Click **General ledger** \> **Setup** \> **EXIM** \> **Incentive scheme groups**. In the **Incentive scheme groups** form, click **New**.

2.  On the **Overview** FastTab, in the **Incentive scheme group** field, enter a unique name for the incentive scheme group.

3.  In the **Description** field, enter a description for the group.

4.  In the **Port ID** field, select the EXIM port through which purchased goods are imported and sold goods are exported.

5.  On the **Setup** FastTab, in the **Incentive scheme** field, select an incentive scheme.
    

    > [!NOTE]
    > <P>You can select an incentive scheme only if you have enabled the incentive scheme in the <STRONG>Incentive scheme parameters</STRONG> form. For more information, see <A href="ind-enable-customs-and-exim-incentive-schemes.md">(IND) Enable customs and EXIM incentive schemes</A>.</P>



6.  In the **Product group** field, select the product group for the import and export orders.

7.  In the **Authorization ID** field, select the authorization to add to the incentive scheme group. Information about the authorization that was issued by the customs authority appears in the **License number**, **Import expiration date**, and **Export expiration date** fields.

8.  Press CTRL+N to add another incentive scheme to the incentive scheme group, or, if you have added all the incentive schemes that apply to the incentive scheme group, click **Close**.

The incentive scheme group can be attached to an import order in the **Purchase order** form and to an export order in the **Sales order** form.

## See also

[(IND) Set up tax codes for incentive scheme groups](ind-set-up-tax-codes-for-incentive-scheme-groups.md)

[(IND) Incentive scheme groups (form)](https://technet.microsoft.com/en-us/library/jj664715\(v=ax.60\))

[(IND) Tax codes for incentive schemes (form)](https://technet.microsoft.com/en-us/library/jj664578\(v=ax.60\))

  


