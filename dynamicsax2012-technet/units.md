---
title: Units
TOCTitle: Units
ms:assetid: 5ba464ef-65f9-4cc9-91bb-525524a94138
ms:mtpsurl: https://technet.microsoft.com/library/Gg731802(v=AX.60)
ms:contentKeyID: 35132647
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Units 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A unit of measure is a standard base or a derived division of quantity that is used for measurement or exchange. For example, when you enter an order in Microsoft Dynamics AX, you specify both a quantity and the unit of measure that the quantity represents.

Use the **Preprocess units** form to define how existing company-specific units of measure are mapped to shared units of measure.


> [!NOTE]
> <P>You must set a system language before you can start this task.</P>



If you are upgrading to Microsoft Dynamics AX 2012 R2 or AX 2012 R3, you must identify a data partition when performing this task. If you have configured multiple partitions, the procedure must be repeated for each partition. For more information about data partitions and upgrade, see [Configure partitions](configure-partitions.md).

## Shared units of measure replace company-specific units of measure

Shared units of measure replace the company-specific units of measure that are used in previous versions of Microsoft Dynamics AX. You must map each company-specific unit of measure that exists to a unit of measure that is shared across companies.


> [!NOTE]
> <P>You can change a shared unit of measure so that it differs from the company-specific unit of measure in the number of decimal places or in the description. The existing data in the system is updated so that it reflects the changes.</P>



## Map company-specific units of measure to shared units of measure

When you start preprocessing units of measure, the **Preprocess units** form lists all units of measure from all existing companies. When you map units of measure from different companies to one set of shared units of measure, you must align information such as the number of decimal places. This information must be aligned for each unit of measure.

1.  Click **Units** to open the **Preprocess units** form.

2.  In the **Partition key** field, select a partition for preprocessing.

3.  In the **Unit (shared)** field, select the symbol that represents the shared unit of measure. Repeat this step for each line.
    

    > [!TIP]
    > <P>Click <STRONG>Automatic assignment</STRONG> to automatically assign each company-specific unit of measure to a new shared unit of measure. When you click <STRONG>Automatic assignment</STRONG>, the value of the <STRONG>Unit</STRONG> field is copied to the <STRONG>Unit (shared)</STRONG> field on all lines where the <STRONG>Unit (shared)</STRONG> field is blank. However, you can manually change the value of the <STRONG>Unit (shared)</STRONG> field.</P>

    

    > [!TIP]
    > <P>We recommend that you use the international symbols for units of measure. For more information, see <A href="http://ts.nist.gov/weightsandmeasures/publications/appxc.cfm">General Tables of Units of Measurements</A>.</P>



4.  Confirm that the values of the **Description** and **Decimals** fields are the same for every company.
    
    To consolidate a unit of measure from two companies, you select the same unit symbol in the **Unit (shared)** field on each line. The values of the **Description** and **Decimals** fields may be different on each line. You must align the values of these fields for each shared unit of measure. When the values of these fields are identical, the system can identify the lines that must be merged during the upgrade.
    

    > [!NOTE]
    > <P>If units of measure from different companies have identical unit symbols, but the values of the <STRONG>Decimals</STRONG>, <STRONG>System of units</STRONG>, and <STRONG>Description</STRONG> fields are different, the mapping cannot be completed. In the <STRONG>Preprocess units</STRONG> form, you can use one of the following methods to resolve the issue:</P>
    > <UL>
    > <LI>
    > <P>Change the values of the <STRONG>Decimals</STRONG>, <STRONG>System of units</STRONG>, and <STRONG>Description</STRONG> fields, so that they are the same for all units that have the same symbol.</P>
    > <LI>
    > <P>Change the values of the <STRONG>Unit (shared)</STRONG> fields, so that they are different for the units that have different properties.</P></LI></UL>
    > <P>The solution that you choose depends on the company setup. If the properties of the units of measure differ by mistake, you can align the values of the fields for the properties. If the properties must remain different, you must change one of the unit symbols.</P>

    

    > [!TIP]
    > <P>To filter the contents of a column, select a field, and then click <STRONG>Filter By Selection</STRONG> on the toolbar. For example, to identify all lines that use the unit symbol kg, select the <STRONG>Unit (shared)</STRONG> field that has this value.</P>



5.  In the **Unit class** field, select a classification for the unit of measure.
    

    > [!TIP]
    > <P>The unit class represents a logical grouping of units of measure, such as area or quantity. The unit classes specify base units and standard units. Base units can be used to streamline the setup of a conversion.</P>

    

    > [!NOTE]
    > <P>When you start preprocessing units of measure, all units that are derived from existing units of measure are assigned to the <STRONG>Undefined</STRONG> class. For each shared unit of measure, you must select a unit class other than <STRONG>Undefined</STRONG>. For a shared unit of measure, the unit class must be identical on every line that is associated with the unit of measure.</P>



6.  In the **System of units** field, verify that the appropriate system of units is applied.
    
    The field is set to **None** when company-specific units of measure are created manually. For units such as box and piece, **None** is an appropriate system of units. However, if **None** is not appropriate for a unit of measure, select **Metric** or **United States customary units**. Examples of units of measure that use the **None** category are Box and Pieces.
    

    > [!NOTE]
    > <P>For a shared unit of measure, the system of units must be identical on every line that is associated with the unit of measure.</P>



7.  Click **Validate** to check for validation errors before you set the units of measure to ready for upgrade.

8.  After you resolve all of the validation errors, click **Set to ready for upgrade**.

## See also

[System parameters](system-parameters.md)

  


