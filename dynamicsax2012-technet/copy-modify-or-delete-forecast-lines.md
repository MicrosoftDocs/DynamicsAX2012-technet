---
title: Copy, modify, or delete forecast lines
TOCTitle: Copy, modify, or delete forecast lines
ms:assetid: c48adcb3-8f27-4c0c-8fc6-8d4f610f7bfa
ms:mtpsurl: https://technet.microsoft.com/library/Aa550733(v=AX.60)
ms:contentKeyID: 36059295
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- copy forecast lines
- delete forecast lines
- edit forecast lines
- process forecast lines
audience: Application User
ms.search.region: Global
---

# Copy, modify, or delete forecast lines 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to process existing forecast transaction lines. You can copy, modify, and delete forecast transaction lines.

1.  Click **Inventory management** \> **Inquiries** \> **Forecast** \> **Supply forecast**.
    
    –or–
    
    Click **Inventory management** \> **Inquiries** \> **Forecast** \> **Demand forecast**.

2.  Click **Edit** to open the **Editing of forecast transactions** form, and then click the **Select** button.

3.  In the query form, click the **Reset** button to clear the selected criteria from the previous query.

4.  On the **Range** tab, select the criteria that identify the source forecast data that you want to copy, modify, or delete. This could include the forecast model, item number, and customer account. Click **OK**. The program runs a query to select all the forecast data that meet your criteria. When this data is selected, you can define how to copy, modify, or delete it by using the **Editing of forecast transactions** form.
    

    > [!WARNING]
    > <P>This step is a prerequisite to using the <STRONG>Editing of forecast transactions</STRONG> form. Without this step, the program selects all forecast lines and updates them. This could result in the unintended duplication of transactions.</P>



5.  In the **Management** field group of the **Editing of forecast transactions** form, select:
    
      - **Copy** - to copy forecast lines to another forecast model.
    
      - **Update** - to modify forecast lines.
    
      - **Delete** - to delete forecast lines.

6.  Use the **Modifications in field** field group to change the parameters of the forecast. Select the check box of the parameter, and then select from the available options.
    
    **Example**
    
    Select the **Model** check box and select a forecast model number. Existing forecast lines are copied to the selected forecast model.

7.  Use the **Change of period** field group to move the forecast start and end dates forward or backward. Select the check box and use the quantity and period fields to define the time period for moving the forecast dates. You can also enter a negative quantity to move the starting date forward.
    
    **Example**
    
    Select the check box, enter 6, and select **Months** to delay the forecast transaction starting date by 6 months.

8.  Use the **Correct field** field group to update the actual forecast data.
    
      - In the **Field** field, select the criterion that you want to change.
    
      - In the **Factor** field, enter a multiplication factor to apply to the criterion that you select, or enter an addition or subtraction constant.
    
    **Example**
    
    Select **Quantity**, and enter a factor of 1.5 to multiply the item quantity by 1.5. Enter a constant of -25 to decrease the item quantity by 25 units.

9.  Click **OK** to apply the changes.

## See also

[Edit forecast transactions (form)](https://technet.microsoft.com/library/aa590281\(v=ax.60\))

[Create forecast lines](create-forecast-lines.md)

  


