---
title: Create a project contract
TOCTitle: Create a project contract
ms:assetid: b6130251-e119-4498-8e62-9b8741086bd6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh370701(v=AX.60)
ms:contentKeyID: 36811426
ms.date: 10/06/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create a project contract 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

By using a project contract, you can invoice one or several projects at the same time. The project contract also helps make sure that a uniform invoicing procedure is applied for each subproject in a project structure. Each project that will be invoiced must be associated with a project contract. Settings for a project contract apply to all projects and subprojects that are associated with the project contract.

A project contract can specify one or more sources of funding. This lets you split billing among multiple funders, set up funding limits so funding sources are not billed more than a specified amount, and configure funding rules for charging expenditures. For more information about project contract funding, see [About project contract funding](about-project-contract-funding.md).

## Create a project contract

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **Project contracts**.

2.  On the **Action Pane**, on the **Project contract** tab, in the **New** group, click **Project contract**.

3.  In the **New project contract** form, enter a project contract identifier and name.

4.  In the **Funding type** field, select whether the source for the funding is a customer, an internal organization, a public grant, or, if you have not yet identified the source type, on hold.

5.  In the **Funding source** field, select the funding source that will provide funding for costs that are associated with this project contract. The options are based on the selection in the **Funding type** field.
    

    > [!NOTE]
    > <P>If project costs will be shared among multiple customers, organizations, or grants, you can assign more funding sources in the <STRONG>Project contract details</STRONG> form, on the <STRONG>Funding sources</STRONG> FastTab.</P>



6.  If the sales currency is not automatically entered in the **Sales currency** field based on the selection in the **Funding source** field, select the sales currency to use for the project contract.

7.  Click **OK**.

8.  In the **Project contracts** form, enter information about additional funding sources, funding limits, or funding rules. For more information, see the following section, “Add funding sources, funding limits, or funding rules to a project contract.”

## Add funding sources, funding limits, or funding rules to a project contract

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **Project contracts**.

2.  Select or open a project contract.

3.  On the **Action Pane**, on the **Project contract** tab, in the **Maintain** group, click **Edit**.

4.  In the **Project contracts** form, on the **Funding sources** FastTab, enter information about each funding source that will bear a portion of the costs for the project contract. For more information, see [Assign funding sources to a project contract](assign-funding-sources-to-a-project-contract.md).

5.  On the **Funding limits** FastTab, enter options to define the scope of the funding rules so that a funding source is not invoiced more than a specified amount.

6.  On the **Funding rules** FastTab, define how to allocate charges for the project contract and the part of the project that each funding source should be invoiced for. For more information, see [Set up funding rules for a project contract](set-up-funding-rules-for-a-project-contract.md).


> [!TIP]
> <P>A subproject can inherit the project contract of the parent project. If you change the project contract of a parent project, you can manage which subprojects are affected by using the <STRONG>Update subprojects</STRONG> form. This form opens when you modify a project that has one or more subprojects.</P>



## See also

[About project contract funding](about-project-contract-funding.md)

  


