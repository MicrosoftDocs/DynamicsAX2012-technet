---
title: Unit conversions
TOCTitle: Unit conversions
ms:assetid: 2615f7b2-4cd5-4e18-865f-192aac23fbdf
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg751370(v=AX.60)
ms:contentKeyID: 35132583
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Unit conversions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Unit conversions define formulas for converting between units of measure. One unit conversion can be associated with each unit of measure.

Use the **Preprocess unit conversions** form to define how you want company-specific unit conversions that exist for company-specific units of measure to be consolidated for shared units of measure.


> [!NOTE]
> <P>You must complete the definition of shared units of measure before you can start this task.</P>
> <UL>
> <LI>
> <P>Click <STRONG>Units</STRONG> to define shared units of measure.</P></LI></UL>



If you are upgrading to Microsoft Dynamics AX 2012 R2 or AX 2012 R3, you must identify a data partition when performing this task. If you have configured multiple partitions, the procedure must be repeated for each partition. For more information about data partitions and upgrade, see [Configure partitions](configure-partitions.md).

## Company-specific unit conversions are consolidated

Each company-specific unit of measure that was created in earlier versions of Microsoft Dynamics AX may have an associated unit conversion. The shared units of measure that you define are based on company-specific units of measure. The associated unit conversions may differ from company to company. The unit conversions can differ in one or more of the following aspects: factor, additional quantity, or rounding information. You must consolidate the unit conversions for each shared unit of measure.


> [!NOTE]
> <P>You may change the factor, additional quantity, or rounding information for a shared unit conversion, so that it differs from the factor, additional quantity, or rounding information in the company-specific unit conversion. In this case, the existing data in the system is updated to reflect the changes.</P>



## Consolidate the unit conversions for the shared units of measure

When you start preprocessing unit conversions, all conversions for each shared unit of measure are listed in the **Preprocess unit conversions** form. Before you can consolidate the list of conversions, you must make sure that the factor, additional quantity, and rounding information are identical for each unit conversion. For example, if the conversion from centiliters (cl) to deciliters (dl) is specified on two lines, and the rounding information is different on each line, you must align the rounding information for the cl to dl conversion.

1.  Click **Unit conversions** to open the **Preprocess unit conversions** form.

2.  In the **Partition key** field, select a partition for preprocessing.

3.  In the **Factor**, **Additional quantity**, and **Round-off** fields, verify that the information is identical if more than one line has the same conversion formula.
    

    > [!TIP]
    > <P>Click <STRONG>Product number</STRONG> or <STRONG>From unit (shared)</STRONG> to change the sort order of the columns.</P>

    

    > [!NOTE]
    > <P>An additional quantity can be used only with units that belong to the temperature unit class.</P>



4.  Click **Validate** to check for validation errors.

5.  After you resolve all validation errors, click **Set to ready for upgrade**.

## See also

[Units](units.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

