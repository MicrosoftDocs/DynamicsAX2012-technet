---
title: Fixed units
TOCTitle: Fixed units
ms:assetid: af7beca8-1903-41b2-855e-e1cd52ae2381
ms:mtpsurl: https://technet.microsoft.com/library/Gg731896(v=AX.60)
ms:contentKeyID: 35132813
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Fixed units 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

System units define the units for length, mass, and volume that appear as suggested units of measure in Microsoft Dynamics AX.

Use the **Preprocess fixed units** form to set up the system units.


> [!NOTE]
> <P>You must define shared units of measure before you can begin this task.</P>



If you are upgrading to Microsoft Dynamics AX 2012 R2 or AX 2012 R3, you must identify a data partition when performing this task. If you have configured multiple partitions, the procedure must be repeated for each partition. For more information about data partitions and upgrade, see [Configure partitions](configure-partitions.md).

## Shared system units replace fixed units

System units that are shared across all companies now replace fixed units, which were used in earlier versions of Microsoft Dynamics AX.

## Set up system units

1.  Click **Fixed units** to open the **Preprocess fixed units** form.

2.  In the **Partition key** field, select a partition for preprocessing.

3.  In the **Length**, **Mass**, and **Liquid volume** fields, select the system units that you want to use.
    

    > [!NOTE]
    > <P>The units that you select must belong to the unit classes for length, mass, and liquid volume. You assign units of measure to unit classes in the <STRONG>Preprocess units</STRONG> form.</P>



4.  Click **Validate** to check for validation errors.

5.  After you resolve all validation errors, click **Set to ready for upgrade**.

  


