---
title: (IND) Set up general ledger parameters for the EPCG incentive scheme
TOCTitle: (IND) Set up general ledger parameters for the EPCG incentive scheme
ms:assetid: 6c38aa6e-be2f-41c5-8ec8-500bd8c3ba64
ms:mtpsurl: https://technet.microsoft.com/library/JJ677907(v=AX.60)
ms:contentKeyID: 49385883
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- general ledger parameters
- (IND)
- india
- EPCG
- EPCG incentive scheme
audience: Application User
ms.search.region: India
---

# (IND) Set up general ledger parameters for the EPCG incentive scheme 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Before you can use the Export Promotion Capital Goods (EPCG) incentive scheme, you must set up the details of the scheme that pertain to the recording of customs duty and incentive scheme amounts. Use the **Incentive scheme parameters** form to enable the EPCG incentive scheme and enter the details.

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  In the left pane, click **Sales tax**, and then, on the **General** FastTab, click **Incentive schemes**.

3.  In the **Incentive scheme parameters** form, click **EPCG**.

4.  In the **Activate** field group, select the **Export Promotion Capital Goods** check box to enable the EPCG incentive scheme.
    

    > [!NOTE]
    > <P>The fields in the <STRONG>EPCG</STRONG> area become available only after you enable the incentive scheme. If you clear the <STRONG>Export Promotion Capital Goods</STRONG> check box after you enter values in the other fields, all fields in the area become unavailable except this check box. However, the values that you entered in the fields are retained.</P>



5.  In the **Import validity** field group, in the **Period interval** field, select the time unit to use for the import validity period. Then, in the **Period** field, enter the validity period to use to calculate the import expiration date.
    
    For example, if you select **Months** in the **Period interval** list and enter **18** in the **Period** field, the goods must be imported within 18 months of the authorization date.

6.  In the **Export obligation** field group, select options in the following fields:
    
      - **Basis** – The basis for deriving the export obligation for the EPCG license. You can choose **FOB** (Free on Board), **NFE** (Net Foreign Exchange earnings), or **Duty saved**.
    
      - **CIF factor** – The factor by which to multiply the cost, insurance, and freight (CIF) value of capital goods to determine the export obligation amount.
    
      - **Period interval** – The period type for which the incentive scheme is valid. This type is used in conjunction with the value in the **Period** field to determine the deadline for exporting the goods.
    
      - **Period** – The period to use to calculate the export expiration date. For example, if **Months** is displayed in the **Period interval** field, and you enter **24** in the **Period** field, the goods must be exported within 24 months of the authorization date.
    
      - **Maximum utilization pct.** – The percentage to use to calculate the maximum allowable import value.
    
      - **Use customs exchange rate** – Whether to use the customs exchange rate to derive the import value and export obligation amount.

7.  In the **Technology upgrade** group, select options in the following fields:
    
      - **Enable technology upgrade** – Select the check box to activate the technology upgrade process for the EPCG scheme.
    
      - **Minimum period** – The period to use to calculate the technology upgrade expiration date. For example, if **Years** is displayed in the **Period interval** field, and you enter **8** in the **Minimum period** field, the technology upgrade must be completed within eight years of the authorization date.
    
      - **Minimum export pct.** – The minimum export percentage to be met for the technology upgrade.

## See also

[(IND) About EPCG incentive schemes for export orders](ind-about-epcg-incentive-schemes-for-export-orders.md)

[(IND) Create an export order for an EPCG incentive scheme](ind-create-an-export-order-for-an-epcg-incentive-scheme.md)

[(IND) Attach an EPCG incentive scheme to an import order](ind-attach-an-epcg-incentive-scheme-to-an-import-order.md)

  


