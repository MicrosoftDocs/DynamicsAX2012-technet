---
title: (IND) Set up general ledger parameters for an EXIM AA incentive scheme
TOCTitle: (IND) Set up general ledger parameters for an EXIM AA incentive scheme
ms:assetid: 6a913e17-049b-4ae7-aa7a-508277cd3a5e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677897(v=AX.60)
ms:contentKeyID: 49385860
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- general ledger parameters
- (IND)
- india
- AA
- Advanced Authorization
- incentive scheme
---

# (IND) Set up general ledger parameters for an EXIM AA incentive scheme 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Setting up general ledger parameters is the first step for setting up an advance authorization (AA) incentive scheme. You must also set up tax ledger posting groups and export-import (EXIM) ports. For more information about those steps, see [(IND) Set up tax ledger posting groups](ind-set-up-tax-ledger-posting-groups.md) and [(IND) Set up EXIM ports](ind-set-up-exim-ports.md).

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  In the left pane, click **Sales tax**, and then, at the top of the **General** FastTab, click **Incentive schemes**.
    

    > [!NOTE]
    > <P>The <STRONG>Incentive schemes</STRONG> button is available only if the <STRONG>Activate incentive schemes</STRONG> check box is selected at the bottom of the <STRONG>General</STRONG> FastTab.</P>



3.  In the **Incentive scheme parameters** form, in the left pane, click **Advance Authorization**, and then select the **Advance Authorization** check box.
    

    > [!NOTE]
    > <P>If you clear the <STRONG>Advance Authorization</STRONG> check box after you select values in the other fields in the <STRONG>Advance Authorization</STRONG> area, all fields other than the <STRONG>Advance Authorization</STRONG> check box become unavailable. However, the fields retain their values. If you select the <STRONG>Advance Authorization</STRONG> check box again, the fields become available with their retained values.</P>



4.  In the **Import validity** field group, in the **Period interval** field, select the time unit to use for the period of time that an AA is valid for imports. In the **Period** field, specify the period of time that an AA is valid for imports. Enter a number in the units that you selected in the **Period interval** field.

5.  In the **Export validity** field group, in the **Period interval** field, select the time unit to use for the period of time that an AA is valid for exports. In the **Period** field, specify the period of time that an AA is valid for exports. Enter a number in the units that you selected in the **Period interval** field.

6.  In the **Import** field group, in the **Assessable value pct.** field, enter the cost, insurance, and freight (CIF) value percentage to be applied on the export assessable value to calculate the import assessable value.
    

    > [!NOTE]
    > <P>The CIF value is based on the Freight On Board (FOB) value, which is based on government regulations.</P>



7.  In the **Posting** field group, select the **Post financial voucher** check box to post financial entries for the AA scheme.
    

    > [!NOTE]
    > <P>Under normal business practices, the accounting of tax that is saved to a benefit account is not recorded for AA. However, Microsoft Dynamics AX has extended this flexibility to AA. Therefore, select this check box only if your company accounting policy calls for recording the tax that is saved to the benefit account for AA.</P>



8.  In the **Benefit account** field, select the account number for posting in the ledger.

9.  In the **Authorization Purchase/Sale** field, select the **Allow purchase** check box to allow the purchase of an AA license. Select the **Allow sale** check box to allow the sale of an AA license.

10. In the left pane, click **Number sequences**.

11. In the **Number sequence code** field for **Advance Authorization voucher**, select the unique key for vouchers that is used when posting AA incentive scheme transactions.

12. In the **Number sequence code** field for **Advance Authorization internal ID**, select the unique key for the internal identification of advance authorizations. The key is used when creating new authorizations.

## See also

[(IND) About the EXIM Advance Authorization (AA) incentive scheme](ind-about-the-exim-advance-authorization-aa-incentive-scheme.md)

[(IND) Set up tax ledger posting groups](ind-set-up-tax-ledger-posting-groups.md)

[(IND) Set up EXIM ports](ind-set-up-exim-ports.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

