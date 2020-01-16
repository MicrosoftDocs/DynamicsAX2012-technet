---
title: 'Scenario: Help secure cube data so that managers see only the data for their own team'
TOCTitle: 'Scenario: Help secure cube data so that managers see only the data for their own team'
ms:assetid: c45d649f-747d-46ad-beca-514514062b8e
ms:mtpsurl: https://technet.microsoft.com/library/JJ129500(v=AX.60)
ms:contentKeyID: 46661152
author: Khairunj
ms.date: 06/03/2014
mtps_version: v=AX.60
---

# Scenario: Help secure cube data so that managers see only the data for their own team 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Some managers in your organization may want to use cube data to track and analyze data for their teams. The following sections provide options for implementing security in this scenario.

## Option: Use dynamic security

To implement security so that a manager has access only to the data for his or her own team, use dynamic security practices. For an example of these practices, see the [Dynamic Security in SSAS cube](http://blogs.msdn.com/b/azazr/archive/2008/08/15/dynamic-security-in-ssas-cube.aspx) blog post.

## Option: Create a new role for a specific manager

Some managers in your organization may want to use cube data to track and analyze expenses for their teams. For example, suppose that Ann is a manager in your organization, and she wants to create pivot tables to analyze expenses for her team. The following procedure explains how to create a manager role for Ann in Microsoft SQL Server Analysis Services. The procedure explains how to create the role, grant the role access to the Expense management cube, and restrict the role to the data for Ann’s team.

1.  In SQL Server Management Studio, connect to your instance of Analysis Services.

2.  In the tree view, expand the **Databases** \> **\[Database Name\]** \> **Roles** node.

3.  Right-click the **Roles** node, and then click **New Role**. The **Create Role** window is displayed.

4.  In the left pane, click **General**. Then follow these steps:
    
    1.  Enter a name for the role. For this example, enter **Manager-Ann**.
    
    2.  Enter a description of the role.
    
    3.  Select the **Read definition** check box.

5.  In the left pane, click **Membership**. Then follow these steps:
    
    1.  Click **Add**. The **Select Users or Groups** form is displayed.
    
    2.  Enter Ann’s name in the following format: \[DomainName\]\\\[UserName\]. Click **OK**.

6.  In the left pane, click **Cubes**. To give Ann access to expense information, follow these steps:
    
    1.  In the **Expense management cube** row, select the **Access** cell.
    
    2.  In the list, select **Read**.

7.  In the left pane, click **Dimension Data**. To give Ann access to expense information only for the employees on her team, follow these steps:
    
    1.  In the **Dimension** list, select **Worker**.
    
    2.  In the **Attribute Hierarchy** list, select **Personnel number**. Then select the personnel numbers that are associated with the employees on Ann’s team.
    
    3.  In the **Attribute Hierarchy** list, select **Worker - Name**. Then select the names of the employees on Ann’s team.
    
    4.  In the **Attribute Hierarchy** list, select **Worker**. Then select the names of the employees on Ann’s team.

Ann can now create pivot tables to analyze expenses for her team. For more information about how to create pivot table reports, see [Create a report by using the Excel data connection wizard to connect to a cube](create-a-report-by-using-the-excel-data-connection-wizard-to-connect-to-a-cube.md).

  


