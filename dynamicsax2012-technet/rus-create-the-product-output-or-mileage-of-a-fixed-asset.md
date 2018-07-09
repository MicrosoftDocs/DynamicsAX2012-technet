---
title: (RUS) Create the product output or mileage of a fixed asset
TOCTitle: (RUS) Create the product output or mileage of a fixed asset
ms:assetid: b680b283-ad2b-4855-bc4f-2b0705d51488
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711543(v=AX.60)
ms:contentKeyID: 49387869
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Create the product output or mileage of a fixed asset [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to create the product output or mileage of a fixed asset.

Use the **Product output/mileage** form to create product output or mileage for a fixed asset.

1.  Click **Fixed assets (Russia)** \> **Periodic** \> **Product output/mileage**.

2.  Press CTRL+N to create new product output or mileage for a fixed asset.

3.  In the **FA inventory number** field, select a fixed asset number.

4.  In the **Period** field, select a start date of the period for calculating the product output or mileage for the fixed asset.
    

    > [!NOTE]
    > <P>The date that you specify in this field is used to calculate the depreciation for the specified fixed asset.</P>



5.  In the **Output/mileage** field, enter the number of units that are produced or the distance that is traveled for the specified period.
    

    > [!NOTE]
    > <P>The number of units (mileage) indicated cannot be less than the sum of the units (mileage) that is indicated in the <STRONG>Output/run nontaxable</STRONG> and <STRONG>Output/run export</STRONG> fields.</P>



6.  In the **Output/run export** field, enter the product output or mileage to export for the fixed asset.

7.  In the **Output/run nontaxable** field, enter the product output or mileage for tax-exempt operations for the fixed asset.

8.  Click **Functions** \> **Copy output/run** to open the **Create or copy output/run lines** form and copy lines from previous reporting periods.
    
    –or–
    
    Click **Functions** \> **Copy output/run** to open the **Create or copy output/run lines** form and create lines in the defined reporting period with specified export and tax-exempt details for the fixed asset.

## See also

[(RUS) Product output/mileage (form)](https://technet.microsoft.com/en-us/library/jj733513\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

