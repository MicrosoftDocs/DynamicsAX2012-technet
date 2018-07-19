---
title: (IND) Create an EXIM EPCG scheme for a technology upgrade EPCG license
TOCTitle: (IND) Create an EXIM EPCG scheme for a technology upgrade EPCG license
ms:assetid: 45cb9452-2dce-4836-aced-45420f35ac62
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664662(v=AX.60)
ms:contentKeyID: 49385736
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (IND)
- india
- EPCG license
- Create EXIM EPCG scheme
- EXIM EPCG scheme
- technology upgrade EPCG license
audience: Application User
ms.search.region: India
---

# (IND) Create an EXIM EPCG scheme for a technology upgrade EPCG license 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can import goods to upgrade existing technology or machinery if you have an Export Promotion Capital Goods (EPCG) license.


> [!NOTE]
> <P>Before you can complete this procedure, the <STRONG>Export Promotion Capital Goods</STRONG> check box must be selected in the <STRONG>Incentive scheme parameters</STRONG> form. For more information, see <A href="ind-set-up-general-ledger-parameters-for-the-epcg-incentive-scheme.md">(IND) Set up general ledger parameters for the EPCG incentive scheme</A>.</P>



1.  Click **General ledger** \> **Common** \> **EXIM EPCG Schemes**. On the **Action Pane**, in the **New** group, click **EXIM EPCG Schemes**.

2.  In the **EXIM EPCG Schemes** form, click **New**.
    
    The **ID** field is filled in automatically, based on the number sequence value that is set in the **Incentive scheme parameters** form. The **Date/time** field displays the current date and time, and the **Status** field displays **Created**.

3.  In the **Port ID** field, select an export-import (EXIM) port.

4.  In the **Authorization basis** field, select **Technology upgrade**.

5.  Click **Importable Items**, and then, in the **Importable Items** form, click **New**.

6.  In the **Item number** field, select the identification number of the importable item.

7.  In the **Unit** field, select the unit of measure of the importable item.

8.  In the **Installation certificate number** field, enter the installation certificate number for the importable item.

9.  In the **Certificate date/time** field, specify the date and time when the installation certificate becomes valid.

10. On the **General** tab, in the **Text** field, enter information about the import.

11. Close the **Importable Items** form.

12. In the **EXIM EPCG Schemes** form, on the **Overview** FastTab, click **Functions**, and then click **Technology upgrade**. In the **Technology upgrade details** form, you can approve the EPCG license for technology upgrade.
    

    > [!NOTE]
    > <P>You can use this option only if the <STRONG>Enable technology upgrade</STRONG> check box is selected in the <STRONG>Incentive scheme parameters</STRONG> form.</P>



13. In the **ID** field, select the authorization ID of the EPCG license for which the technology upgrade is applicable.
    
    The **License number**, **Issue date/time**, **Import value**, and **Annual average** fields display values based on the selected EPCG license ID.
    

    > [!NOTE]
    > <P>The selected EPCG license must satisfy the following conditions:</P>
    > <UL>
    > <LI>
    > <P>The license was active for the minimum period, beginning on the issue date that is specified in the <STRONG>Minimum period</STRONG> field in the <STRONG>EPCG</STRONG> area of the <STRONG>Incentive scheme parameters</STRONG> form.</P>
    > <LI>
    > <P>The minimum export obligation that is specified in the <STRONG>Minimum export pct.</STRONG> field was fulfilled.</P></LI></UL>



14. In the **Approval details** field group, in the **License number** field, enter the EPCG license number for technology upgrade that was issued by the authority.

15. In the **Approval details** field group, in the **Issue date/time** field, specify the date and time when the original EPCG license was issued.

16. In the **Approval details** group, in the **Annual average** field, enter the annual average value of the technology upgrade license number.

17. Approve the license. For more information, see [(IND) Approve an EPCG license](ind-approve-an-epcg-license.md).

18. Reopen the **Technology upgrade details** form, and then click **OK**.

In the **EXIM EPCG Schemes** form, on the **Overview** FastTab, the status for the selected authorization ID is updated to **Approved**.

The status of the original license that is selected in the **Original details** field group in the **Technology upgrade details** form is updated to **Technology upgrade**, and the **Close** check box is selected.

On the **Lines** FastTab, the details of the technology upgrade EPCG license are updated with a license status of **Original**.

## See also

[(IND) Create a primary EPCG license](ind-create-a-primary-epcg-license.md)

[(IND) Approve an EPCG license](ind-approve-an-epcg-license.md)

[(IND) Extend the export obligation period for an EPCG license](ind-extend-the-export-obligation-period-for-an-epcg-license.md)

[(IND) Revalidate an EPCG license for domestic purchasing](ind-revalidate-an-epcg-license-for-domestic-purchasing.md)

[(IND) Redeem an EPCG license](ind-redeem-an-epcg-license.md)

[(IND) Set up tax codes for incentive scheme groups](ind-set-up-tax-codes-for-incentive-scheme-groups.md)

[(IND) Attach an EPCG incentive scheme to an import order](ind-attach-an-epcg-incentive-scheme-to-an-import-order.md)

[(IND) Verify details about the technology upgrade for an EPCG license](ind-verify-details-about-the-technology-upgrade-for-an-epcg-license.md)

  


