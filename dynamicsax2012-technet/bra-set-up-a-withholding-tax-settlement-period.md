---
title: (BRA) Set up a withholding tax settlement period
TOCTitle: (BRA) Set up a withholding tax settlement period
ms:assetid: 1e487a44-1541-47f3-bb99-a5ae35fed615
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn126101(v=AX.60)
ms:contentKeyID: 52075239
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (BRA) Set up a withholding tax settlement period [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When you collect withholding taxes, you must settle and pay taxes at regular intervals called settlement periods. You can set up a withholding tax settlement period, and then attach one or more withholding tax codes. For more information, see [Sales tax settlement periods (form)](https://technet.microsoft.com/en-us/library/aa633944\(v=ax.60\)).

1.  Click **General ledger** \> **Setup** \> **Withholding tax** \> **Brazil** \> **Withholding tax settlement periods**.

2.  Create a withholding tax settlement period. For more information, see [Set up a sales tax settlement period](set-up-a-sales-tax-settlement-period.md).

3.  In the **Settlement period** field, enter a unique code to identify the withholding tax settlement period.

4.  In the **Description** field, enter a description of the withholding tax settlement period.

5.  In the **Terms of payment** field, select the terms of payment for the withholding tax payments.

6.  In the **Authority** field, select the withholding tax authority to which taxes are reported and paid at the end of a withholding tax settlement period.

7.  In the **Period interval** field, select the settlement period interval from the following options:
    
      - **Days**
    
      - **Months**
    
      - **Years**

8.  In the **Number of units** field, enter the number of period units to define the withholding tax settlement period. The length of each period that is created on the **Periods** tab is equal to the period interval multiplied by the number of units.

9.  In the **From date** and **To date** fields, select the starting date and ending date of the settlement period.
    

    > [!NOTE]
    > <P>After you create the first period, click <STRONG>New period</STRONG> to create the other periods. This ensures that all days are accounted for, and that each day appears in only one period.</P>



## See also

[(BRA) Withholding tax payments inquiry (form)](https://technet.microsoft.com/en-us/library/dn126102\(v=ax.60\))

[(BRA) Withholding tax transactions (form)](https://technet.microsoft.com/en-us/library/dn126112\(v=ax.60\))

[(BRA) Set up an item withholding tax group](bra-set-up-an-item-withholding-tax-group.md)

[(BRA) Calculate withholding tax for the sale of services](bra-calculate-withholding-tax-for-the-sale-of-services.md)

[(BRA) Calculate withholding tax for the purchase of services](bra-calculate-withholding-tax-for-the-purchase-of-services.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

