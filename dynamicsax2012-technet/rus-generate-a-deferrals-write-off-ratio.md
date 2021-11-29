---
title: (RUS) Generate a deferrals write-off ratio
TOCTitle: (RUS) Generate a deferrals write-off ratio
ms:assetid: 0afc695c-f851-4ceb-996d-5be1b817906d
ms:mtpsurl: https://technet.microsoft.com/library/JJ711379(v=AX.60)
ms:contentKeyID: 49387198
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Generate a deferrals write-off ratio 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

To generate a deferrals write-off voucher using the **Linear with factor** method in the **Writing off methods** form, you must first calculate the corresponding write-off ratio.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



## Set up the deferred expenses write-off method

1.  Click **General ledger** \> **Setup** \> **Deferrals** \> **Writing off methods**.

2.  In the **Writing off method** field, enter the write-off method code.

3.  In the **Name** field, enter the method name.

4.  In the **Type** field, select **Linear with factor**.

5.  In the **Writing off period** field, select the write-off period.

6.  In the **Calculation period** field, select the calculation period from the following options:
    
      - **Month** – The deferrals write-off calculation is performed proportionately for the number of months in the given period.
    
      - **Day** – The calculation is performed proportionately for the number of days in the selected period. This allows calculation of the deferrals write-off amount for an incomplete reporting period, based on the number of calendar days in the period.
    
      - **Period** – The calculation is performed proportionately for the number of periods that are defined in the **Writing off period** field.
        

        > [!NOTE]
        > <P>This field is available only if you select <STRONG>Linear</STRONG> or <STRONG>Linear with factor</STRONG> in the <STRONG>Type</STRONG>. The calculation period defines what level of detail to use for the calculation.</P>



7.  In the **Round-off** field, enter the round-off value for the deferrals write-off amount. For example, if you specify the value 0.01, values will be rounded to two decimal places.

## Calculate the deferrals writing off ratio

1.  Click **General ledger** \> **Periodic** \> **Deferrals** \> **Writing off factor calculation**.

2.  Press CTRL+N to create a new line.

3.  In the **Period type** field, select the period type.
    

    > [!NOTE]
    > <P>The <STRONG>End date</STRONG> field is updated automatically based on the period type selected in the <STRONG>Period type</STRONG> field.</P>



4.  In the **Start date** field, select the starting date of the calculation period.

5.  Click **Sequences** to open the **Writing off factor calculation** form.

6.  Click **Calculate all**.
    
    –or–
    
    Click **Calculate marked** to open the **Writing off factor calculation** form.

7.  Select the **Overwrite** check box to recalculate the existing ratios if the deferral's counter calculation has been changed.

8.  Click **OK** to calculate the ratios.
    

    > [!NOTE]
    > <P>The write-off ratios are calculated and recorded in the corresponding deferrals voucher.</P>



## Enter the deferrals write-off ratio

1.  Click **General ledger** \> **Periodic** \> **Deferrals** \> **Writing off factor calculation**. Click **Factors**.

2.  In the **Start date** field, select the starting date of the calculation period.

3.  In the **Expense code** field, select the expense code.

4.  In the **Deferrals group** field, select the deferrals group.

5.  In the **Ratio** field, enter the calculated ratio for the deferral group and expense code.
    
    In the **Normalized amount** field, verify the write-off sum based on the calculated ratio. In the **Base amount** field, verify the calculated amount for the selected period by the deferrals group and expense code.

6.  Click **Print** to open the **Factors for deferrals writing off** form.

7.  Click **OK** to print a report of the calculated deferrals write-off ratios.

## See also

[(RUS) Writing off methods (form)](https://technet.microsoft.com/library/jj711659\(v=ax.60\))

  


