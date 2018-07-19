---
title: Create a formula rule
TOCTitle: Create a formula rule
ms:assetid: 3b8f33cf-85e0-43c8-b8ac-7f08402aeebe
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa570163(v=AX.60)
ms:contentKeyID: 36931868
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create a formula rule 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use formula rules to set up a specific fixed or calculated value for a variable. The calculations are performed every time that the variables in the calculation are changed.

1.  Repeat the first six steps described in [Create a validation rule](create-a-validation-rule.md).

2.  Select the **Formula setup** tab.

3.  In the **Variable** field, select the variable name.

4.  If the selected variable belongs to the array group, type its index in the **Index** field.

5.  In the **Type** field, select one of the following:
    
      - **Value** – The variable should receive a specific value.
    
      - **Calculated** – The variable value should be calculated according to a specific formula.

6.  If you selected **Value**, select one of the values for the variable in the **Outcomes** field. If you selected **Calculated**, click **Calculated** to create a formula.

7.  Select the **Recalculate** check box if all the rules that contain the selected variable should be recalculated.

  


