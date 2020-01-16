---
title: 'Scenario: Help prevent employees of one company from viewing cube data for another company'
TOCTitle: 'Scenario: Help prevent employees of one company from viewing cube data for another company'
ms:assetid: c06c0fb0-d9ee-4bc5-9f40-470e42468bae
ms:mtpsurl: https://technet.microsoft.com/library/JJ129501(v=AX.60)
ms:contentKeyID: 46661155
author: Khairunj
ms.date: 06/03/2014
mtps_version: v=AX.60
---

# Scenario: Help prevent employees of one company from viewing cube data for another company 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Your organization may consist of several companies. To help prevent employees of one company from viewing the data for another company by using cubes, we recommend that you create a role for each company in Microsoft SQL Server Analysis Services.

For example, assume that your organization consists of two companies: Contoso, Ltd. and Fabrikam, Inc. You want to prevent accountants in one company from viewing the data for the other company. Therefore, you should modify the default Accountant role and create a new role for each company. The following illustration provides an overview of the tasks that you need to complete.

![Company-specific roles in Analysis Services](images/JJ129501.BI_Scenario1_CompanyRoles(AX.60).gif "Company-specific roles in Analysis Services")

The following sections describe the procedures that you must complete for each role in this scenario.

## Accountant role

The Accountant role was automatically created in the Analysis Services database that you deployed the Microsoft Dynamics AX cubes to. By default, the Accountant role has access to data for all companies. Follow these steps to prevent users who are assigned to the Accountant role from accessing company-specific data.

1.  In SQL Server Management Studio, connect to your instance of Analysis Services.

2.  In the tree view, expand the **Databases** \> **\[Database Name\]** \> **Roles** node.

3.  Right-click the **Accountant** role, and then click **Properties**. The **Edit Role – Accountant** form is displayed.

4.  In the **Select a page** area, click **Dimension Data**.

5.  In the **Dimension** list, select **Company**.

6.  In the **Attribute Hierarchy** list, select **Company**.

7.  Click **Deselect all members**.

8.  In the **Attribute Hierarchy** list, select **Company name**.

9.  Click **Deselect all members**.

10. Click **OK**.

11. Assign all your accountants to the Accountant role. For instructions about how to assign users to this role, see [Grant users access to cubes](grant-users-access-to-cubes.md).

## Accountant-Contoso role

Follow these steps to create a new role that is named Accountant-Contoso. This role has access to data for the Contoso, Ltd. company only.

1.  Create the Accountant-Contoso role in Analysis Services.
    
    For information about how to create the role, see the SQL Server documentation on TechNet or MSDN.

2.  Give the role access to the Contoso, Ltd. company by following these steps:
    
    1.  Right-click the **Accountant-Contoso** role, and then click **Properties**. The **Edit Role – Accountant-Contoso** form is displayed.
    
    2.  In the **Select a page** area, click **Dimension Data**.
    
    3.  In the **Dimension** list, select **Company**.
    
    4.  In the **Attribute Hierarchy** list, select **Company**.
    
    5.  Select the check box for Contoso, Ltd. Then clear all other check boxes.
    
    6.  In the **Attribute Hierarchy** list, select **Company name**.
    
    7.  Select the check box for Contoso, Ltd. Then clear all other check boxes.
    
    8.  Click **OK**.

3.  Assign the accountants for Contoso, Ltd. to the Accountant-Contoso role.

## Accountant-Fabrikam role

Follow these steps to create a new role that is named Accountant-Fabrikam. This role has access to data for the Fabrikam, Inc. company only.

1.  Create the Accountant-Fabrikam role in Analysis Services.
    
    For information about how to create the role, see the SQL Server documentation on TechNet or MSDN.

2.  Give the role access to the Fabrikam, Inc. company by following these steps:
    
    1.  Right-click the **Accountant-Fabrikam** role, and then click **Properties**. The **Edit Role – Accountant-Fabrikam** form is displayed.
    
    2.  In the **Select a page** area, click **Dimension Data**.
    
    3.  In the **Dimension** list, select **Company**.
    
    4.  In the **Attribute Hierarchy** list, select **Company**.
    
    5.  Select the check box for Fabrikam, Inc. Then clear all other check boxes.
    
    6.  In the **Attribute Hierarchy** list, select **Company name**.
    
    7.  Select the check box for Fabrikam, Inc. Then clear all other check boxes.
    
    8.  Click **OK**.

3.  Assign the accountants for Fabrikam, Inc. to the Accountant-Fabrikam role.

## See also

[Granting Dimension Access](http://technet.microsoft.com/en-us/library/ms175421.aspx)

[Granting Custom Access to Dimension Data](http://technet.microsoft.com/en-us/library/ms175366.aspx)

  


