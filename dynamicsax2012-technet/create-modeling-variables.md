---
title: Create modeling variables
TOCTitle: Create modeling variables
ms:assetid: f7b77e3c-fdd3-40cd-a044-e9d09a374bd0
ms:mtpsurl: https://technet.microsoft.com/library/Aa499809(v=AX.60)
ms:contentKeyID: 36676421
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create modeling variables 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

For you to use modeling variables in a product model, you must create them in the **Modeling variables** form. Before you create a set of modeling variables, consider which parameters are most important for the definition of the configured item.


> [!NOTE]
> <P>This information applies only to Product builder.</P>



## Create modeling variables

1.  Click **Product information management** \> **Setup** \> **Product builder** \> **Modeling variables**.

2.  Press CTRL+N to create a new line.

3.  Type the variable name in the **Variable** field.
    

    > [!NOTE]
    > <P>Variable names must start with a letter.</P>



4.  Select the variable type in the **Data type** field.

5.  Type the description.

6.  Select the **General** tab and then type the help text for the modeling variable.

## Additional steps for Table variables

For **Table** modeling variables, you must complete additional fields on the **General** tab.

1.  In the **Reference** field group, select the Microsoft Dynamics AX 2012 table from which data should be retrieved in the **Table** field.
    

    > [!NOTE]
    > <P>Do not use tables containing more than 255 values for the field you are going to use.</P>



2.  In the **Field name** field, select the name of the table field from which data should be retrieved.

3.  In **Additional field**, select a field name to be shown in the lookup list.

4.  If you want only some of the values found in the table, click **Range** and in the form that opens, specify which table values that you want the user to be able to select from during item configuration.

5.  Close the window to return to the General tab.

## See also

[Modeling variables (form)](https://technet.microsoft.com/library/aa592160\(v=ax.60\))

  


