---
title: Unit texts
TOCTitle: Unit texts
ms:assetid: c26ff11e-ec41-47cd-b1cf-95736a790e7f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731921(v=AX.60)
ms:contentKeyID: 35132849
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Unit texts 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Unit texts are printed on external documents such as invoices. If no unit text is associated with a unit of measure, the symbol of the unit of measure is applied.

Use the **Preprocess unit texts** form to define how company-specific unit texts that exist are consolidated to a set of shared language-specific unit texts.

From Microsoft Dynamics AX onwards, the language is shared between companies and there is only one shared language. For this reason, text in external documents is not automatically printed in company-specific languages. To accommodate this change and preserve a representation of, for example units of measure, in different languages, you must create new unit texts. The new unit texts must be created for each unit of measure in each of the languages that you want to be represented.

If you are upgrading to Microsoft Dynamics AX 2012 R2 or AX 2012 R3, you must identify a data partition when performing this task. If you have configured multiple partitions, the procedure must be repeated for each partition. For more information about data partitions and upgrade, see [Configure partitions](configure-partitions.md).

## Set the unit texts for different languages

When you start preprocessing unit texts, all unit texts associated with each unit of measure are listed in the **Preprocess unit texts** form. In cases where there is more than one unit text per language for a shared unit of measure, the texts must be aligned so that there is only one text per language.

1.  Click **Unit texts** to open the **Preprocess unit texts** form.

2.  In the **Partition key** field, select a partition for preprocessing.

3.  Verify the text in the **Unit** field. If there is more than one unit text per language associated with a unit, you must align the texts.
    

    > [!TIP]
    > <P>To align unit texts, change the content of the <STRONG>Unit</STRONG> fields.</P>



4.  Click **Validate** to check for validation errors before you set the unit texts to ready for upgrade.

5.  Click **Set to ready for upgrade** when you have resolved all validation errors.

  


