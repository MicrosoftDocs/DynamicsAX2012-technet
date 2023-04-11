---
title: Product Builder Route nodes upgrade
TOCTitle: Product Builder Route nodes upgrade
ms:assetid: 075b3510-a835-4609-82e7-2c4155470865
ms:mtpsurl: https://technet.microsoft.com/library/Gg751345(v=AX.60)
ms:contentKeyID: 35132532
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Product Builder Route nodes upgrade 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to map modeling variables assigned to product models and nodes in the modeling tree to fixed values during the upgrade process. The target system does not support modeling variables. Therefore, existing modeling variables must be mapped to fixed values. The fields that are available on the right side of the form can vary, depending on the modeling variables that are allocated for each product model.

**Example**

If a modeling variable is allocated for a resource in a product model, the **Resource (Variable)** field shows the modeling variable. You must then select the fixed resource that you want to map the variable to in the **Resource** field.

If you are upgrading to Microsoft Dynamics AX 2012 R2 or AX 2012 R3, you must identify a data partition when performing this task. If you have configured multiple partitions, the procedure must be repeated for each partition. For more information about data partitions and upgrade, see [Configure partitions](configure-partitions.md).

## To map route variables for upgrade

1.  Click **Prepare application data for preprocessing** \> **Product builder route nodes upgrade**.

2.  In the **Partition key** field, select a partition for preprocessing.

3.  Select a product model in the grid on the left side of the form. Depending on the modeling variables that require mapping, do one of the following in the available fields.
    
      - In the **Resource** field, select the fixed resource to which you want to map the modeling variable shown in the **Resource (Variable)** field.
    
      - In the **Load** field, enter a number for the load that you want to map the modeling variable to.
    
      - In the **Qty. of Resources** field, enter a number for the quantity of resources that you want to map the modeling variable to.
    
      - In the **Job Requirement** field, enter a number for the job requirement that you want to map the modeling variable to.

4.  To mark this item on the preprocessing checklist as completed, and continue to the next item on the preprocessing checklist, click the **Set to ready for upgrade** button.

## See also

[Product Builder - Route Operation nodes with variable allocations to resource fields (form)](https://technet.microsoft.com/library/hh202130\(v=ax.60\))

  


