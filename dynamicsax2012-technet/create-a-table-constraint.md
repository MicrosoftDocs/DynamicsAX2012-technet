---
title: Create a table constraint
TOCTitle: Create a table constraint
ms:assetid: f6409362-123c-4921-9dbf-44ea523405e9
ms:mtpsurl: https://technet.microsoft.com/library/Hh597282(v=AX.60)
ms:contentKeyID: 39519366
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- product configurator
audience: Application User
ms.search.region: Global
---

# Create a table constraint 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create user-defined or system-defined table constraints for components in a product configuration model. You can view or create table constraints on the **Product configuration models** list page. To do so, click **Table constraints** on the **Action Pane**. You can also set up table constraints in the **Constraint-based product configuration model details** form. To do so, click **Maintain table constraints** on the **Constraints** FastTab.

## Create a user-defined table constraint

Before you can set up a user-defined table constraint, the attribute types to include in the constraint must already exist. For more information, see [Attribute types (form)](https://technet.microsoft.com/library/hh227367\(v=ax.60\)).

1.  Click **Product information management** \> **Common** \> **Product configuration models**.

2.  On the **Action Pane**, click **Table constraints**.

3.  Click **New** on the toolbar to start the **New table constraint** wizard.

4.  On the **New table constraint** page, click **Next \>**.

5.  On the **Specify name and type** page, in the **Name** field, enter a name for the table constraint.  
    

    > [!TIP]
    > <P>We recommend that you use Microsoft Solver Foundation syntax for the table constraint name.</P>



6.  Optional: In the **Description** field, enter a description of the table constraint.

7.  Click the **User defined** option, and then click **Next \>**.

8.  On the **Define columns** page, click **New** to specify the attribute types that you want to include in the table constraint.

9.  In the **Attribute type** field, select the attribute type that you want to include in the column.

10. Repeat steps 8 and 9 for each column to create, and then click **Next \>**.

11. On the **Table constraint content** page, enter the combinations of values to allow and then click **Next \>**.  
    

    > [!NOTE]
    > <P>You must use the exact solver values for the attributes that are specified for the attribute type that you selected on the <STRONG>Define columns</STRONG> page.<BR></P>

    

    > [!TIP]
    > <P>It can be helpful to view the attribute values when you are setting up the combinations to allow in a table constraint. To view attribute values, open the <STRONG>Attribute types</STRONG> form, and select the attribute type that you selected for a column in the table constraint.</P>



12. On the **Finish** page, click **Finish**.

## Create a system defined table constraint

1.  Click **Product information management** \> **Common** \> **Product configuration models**.

2.  Select the product configuration model that contains the component to add a table constraint to. On the **Action Pane**, click **Table constraints**.

3.  Click **New** on the toolbar to start the **New table constraint** wizard.

4.  On the **New table constraint** page, and then click **Next \>**.

5.  On the **Specify name and type** page, enter a name for the table constraint in the **Name** field.  
    

    > [!TIP]
    > <P>We recommend that you use Microsoft Solver Foundation syntax for the table constraint name.</P>



6.  Optional: In the **Description** field, enter a description of the table constraint.

7.  Click the **System defined** option to specify the type of constraint to create, and then click **Next \>**.

8.  In the **Select table** field, select the system table that contains the fields to use in the constraint, and then click **Next \>**.

9.  On the **Define columns** page, click **Add** to specify the fields and attribute types to include in the table constraint.

10. In the **Name** field, enter the name of the column and then click **Next \>**.

11. In the **Field name** field, select a field to use in combination with an attribute type. You can select from the fields on the system table that you selected on the **Specify name and type** page.

12. In the **Attribute type** field, select the attribute type that contains the attributes to use in combination with the selected field. Repeat steps 10, 11, and 12 for each column, and then click **Next \>**.

13. On the **Finish** page, click **Finish**.

## See also

[Add a table constraint to a component](add-a-table-constraint-to-a-component.md)

[About system-defined and user-defined table constraints](about-system-defined-and-user-defined-table-constraints.md)

  


