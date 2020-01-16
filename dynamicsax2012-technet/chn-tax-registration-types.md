---
title: (CHN) Tax registration types
TOCTitle: (CHN) Tax registration types
ms:assetid: 6a74738b-443a-4c6e-9aa8-742f7018655c
ms:mtpsurl: https://technet.microsoft.com/library/JJ714193(v=AX.60)
ms:contentKeyID: 49651302
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (CHN) Tax registration types 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In Microsoft Dynamics AX 2009, value-added tax (VAT) registration numbers are stored in the various party tables, such as the customer table. Microsoft Dynamics AX 2012 R2 and R3 include a new table for tax registration types. During upgrade, VAT registration numbers must be copied to the new tax registration types table and the required references must be added to the party tables.

Use this procedure to upgrade tax registration types for customers and legal entities:

1.  In the **Preprocessing upgrade checklist**, click **Tax registration types** to open the **Tax registration types** form.

2.  In the **Tax registration types** tab, select a tax registration type.

3.  In the **Tax registration types rules** tab, modify the rules for the tax registration type.

4.  In the **Country/region** field, select a country or region.

5.  In the **Authority** field, select a tax authority.

6.  In the **Restricted to** field, if the registration type applies only to a person or an organization, select **Person** or **Organization**. Otherwise, select **None**.

7.  In the **Format** field, specify a format for the tax registration number.

8.  Select the **Can be updated** check box if the registration number for the registration type can be updated after it has been specified.

9.  Select the **Unique** check box if the registration number for the registration type must be unique.

10. Repeat steps 2 to 8, as required.

11. When you have finished, click **Set to ready for upgrade** to close the form.

  


