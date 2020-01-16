---
title: Prepare financial dimension framework for upgrade
TOCTitle: Prepare financial dimension framework for upgrade
ms:assetid: d5fd4c31-fc51-49ea-8118-8e782c4bad98
ms:mtpsurl: https://technet.microsoft.com/library/Gg731971(v=AX.60)
ms:contentKeyID: 35132913
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- prepare financial dimension framework
---

# Prepare financial dimension framework for upgrade 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A main account category is a classifier of a main account. A financial dimension is a financial data classifier that is created from the parties, locations, products, and activities in an organization, and that is used for management reporting.

In Microsoft Dynamics AX 2009, you could create ledger account categories and financial dimensions for each company. In Microsoft Dynamics AX 2012, the main account categories and financial dimensions that you create are shared, and can be used by any of the legal entities that are set up in Microsoft Dynamics AX.


> [!NOTE]
> <P>Dimension focuses have been renamed to financial dimension sets and are shared by the legal entities that are set up in the <STRONG>Legal entities</STRONG> form. Therefore, the financial dimension sets can be used by any of those legal entities. Financial dimension sets in Microsoft Dynamics AX 2012 differ from the dimension sets in previous releases.</P>



In versions earlier than Microsoft Dynamics AX 2012, in the **Tax dimension** field, in the **General ledger parameters** form, you could select one of three standard financial dimensions to be used as expense and income codes. In Microsoft Dynamics AX 2012, the association of financial dimensions with expense and income codes was updated to agree with the new financial dimensions framework. Therefore, you need to link the expense and income codes table (RTax25ProfitTable) to the financial dimensions table (DimensionAttribute) so that you can select the appropriate financial dimension in the **Dimension transfer** field in Microsoft Dynamics AX 2012 R2.

If you are upgrading to Microsoft Dynamics AX 2012 R2 or AX 2012 R3, you must identify a data partition when performing this task. If you have configured multiple partitions, the procedure must be repeated for each partition. For more information about data partitions and upgrade, see [Configure partitions](configure-partitions.md).

Use the **Prepare financial dimension framework for upgrade** form to select the main account categories and financial dimension sets that will be shared by the legal entities.

1.  Click **Prepare financial dimension framework for upgrade** to open the **Prepare financial dimension framework for upgrade** form.

2.  In the **Partition key** field, select a partition for preprocessing.

3.  In the **Available company accounts** field in the **Ledger account categories** field group, select the company account that contains the main account categories that will be available as shared main account categories.
    

    > [!NOTE]
    > <P>This field is available only if you are upgrading from Microsoft Dynamics AX 2009.</P>



4.  In the **Generate shared dimension focuses** field, select how to create financial dimension sets:
    
      - **For each company account** – All the financial dimension sets that currently are set up for the accounts in each company will be available as shared financial dimension sets.
    
      - **Specific company account** – Only the financial dimension sets for the accounts in the company that you select in the **Available company accounts** field in the **Dimension focuses** field group will be available as shared financial dimension sets.

5.  If you selected **Specific company account**, select the company account that contains the financial dimension sets that will be shared. Otherwise, continue to step 5.

6.  In the **Dimension numbers** field group, in the **Available company accounts** field, select the company account on which to base the financial dimension numbers for agreements.

7.  Select the **Link tax dimensions** check box to link the expense and income codes table (RTax25ProfitTable) to the financial dimensions table (DimensionAttribute) so that you can select the appropriate financial dimension in the **Dimension transfer** field.

8.  Optional: Click **Upgrade validation** for the **Ledger account categories** field group to display the ledger account categories that have upgrade errors.
    

    > [!NOTE]
    > <P>This button is available only if you are upgrading from Microsoft Dynamics AX 2009.</P>



9.  Optional: Click **Upgrade validation** for the **Dimension focuses** field group to display the shared financial dimensions sets and the upgrade error status of each financial dimension set.

10. Optional: Click **Upgrade validation** for the **Dimension numbers** field group to display the financial dimension numbers and the upgrade error status of each financial dimension number.

11. Click **Set to ready for upgrade** to select this checklist item as ready for upgrade.


> [!WARNING]
> <P>Do not change financial dimension names after you start the <STRONG>Preprocessing upgrade checklist</STRONG>, and before the update is completed.</P>


  


