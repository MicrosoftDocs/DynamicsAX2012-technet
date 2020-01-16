---
title: (IND) Set up incentive scheme parameters for DFIA
TOCTitle: (IND) Set up incentive scheme parameters for DFIA
ms:assetid: bc860ea5-b4d5-446d-bc38-ebfce6d1ccd6
ms:mtpsurl: https://technet.microsoft.com/library/JJ664847(v=AX.60)
ms:contentKeyID: 49386177
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- parameters
- general ledger
- (IND)
- India
- incentive scheme
- DFIA
- Duty Free Import Authorization
audience: Application User
ms.search.region: India
---

# (IND) Set up incentive scheme parameters for DFIA 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Before you can use the Duty Free Import Authorization (DFIA) incentive scheme, you must set up the details of the scheme that pertain to the recording of customs duty and incentive scheme amounts. Use the **Incentive scheme parameters** form to enable the DFIA incentive scheme and enter the details.

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**. Click **Sales tax**, and then on the **General** FastTab, click **Incentive schemes**.

2.  In the **Incentive scheme parameters** form, click **DFIA**.

3.  In the **Activate** field group, select the **Duty Free Import Authorization** check box to enable the DFIA incentive scheme.
    

    > [!NOTE]
    > <P>The fields in the <STRONG>DFIA</STRONG> area become available only after you enable the incentive scheme. If you clear the <STRONG>Duty Free Import Authorization</STRONG> check box after you enter values in the other fields, all fields in the area become unavailable, except this check box. However, the values that you entered in the fields are retained.</P>



4.  In the **Import validity** field group, in the **Period interval** list, select an appropriate time unit for the import validity period. Then, in the **Period** field, enter the validity period to calculate the import expiration date.
    
    For example, you select **Months** in the **Period interval** list and enter **18** in the **Period** field. In this case, the goods must be imported within 18 months of the authorization date.

5.  In the **Export validity** field group, in the **Period interval** list, select an appropriate time unit for the export validity period. Then, in the **Period** field, enter the validity period to calculate the export expiration date.
    
    For example, you select **Months** in the **Period interval** list and enter **24** in the **Period** field. In this case, the goods must be exported within 24 months of the authorization date.

6.  In the **Assessable value pct.** field, enter the percentage that is applied to the export assessable value to calculate the import assessable value.

7.  Select the **Post financial voucher** check box to post the financial entries for the exempt duty amount.

8.  In the **Benefit account** list, select the default account that is used to post the financial entries for the exempt duty amount.

9.  Select the **Allow purchase** check box to allow the purchase of a DFIA authorization.

10. Select the **Allow sale** check box to allow the sale of a DFIA authorization.

11. In the left pane, click **Number sequences**. Then, on the **DFIA internal ID** row, select the number sequence for authorization numbers that are created for new authorizations.

12. On the **DFIA voucher** row, select the number sequence for vouchers that are created when you post transactions for the DFIA.

## See also

[(IND) Setting up the EXIM Duty Free Import Authorization (DFIA) incentive scheme](ind-setting-up-the-exim-duty-free-import-authorization-dfia-incentive-scheme.md)

[(IND) Set up EXIM authorization schemes for DFIA](ind-set-up-exim-authorization-schemes-for-dfia.md)

[(IND) About the EXIM Duty Free Import Authorization (DFIA) incentive scheme](ind-about-the-exim-duty-free-import-authorization-dfia-incentive-scheme.md)

[(IND) Incentive scheme parameters (form)](https://technet.microsoft.com/library/jj677946\(v=ax.60\))

[(IND) Create incentive scheme groups](ind-create-incentive-scheme-groups.md)

[(IND) Set up tax codes for incentive scheme groups](ind-set-up-tax-codes-for-incentive-scheme-groups.md)

[(IND) Incentive scheme groups (form)](https://technet.microsoft.com/library/jj664715\(v=ax.60\))

[(IND) Create incentive scheme groups](ind-create-incentive-scheme-groups.md)

[(IND) Incentive scheme groups (form)](https://technet.microsoft.com/library/jj664715\(v=ax.60\))

[(IND) Set up tax ledger posting groups for DFIA](ind-set-up-tax-ledger-posting-groups-for-dfia.md)

  


