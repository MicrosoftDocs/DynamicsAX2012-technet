---
title: (BRA) Set up the configurator definition group
TOCTitle: (BRA) Set up the configurator definition group
ms:assetid: fa4f9d51-23b0-4667-bb82-21cebd5dd4b1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ730983(v=AX.60)
ms:contentKeyID: 49675212
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- configurator definition group
- Definition Group Wizard
- electronic remittance
- electronic return
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up the configurator definition group 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create configurator definition groups by specifying tables and fields that are used in file formats for configurator layout groups, or by exporting data with the Configurator export utility. For more information, see [(BRA) About the configurator](bra-about-the-configurator.md)

You can create a configurator definition group in the following ways:

  - Create a configurator definition group based on a predefined query. For more information, see Set up a definition group based on a predefined query.

  - Create a configurator definition group, and then associate tables and fields with the definition group by using the Definition Group Wizard. For more information, see Set up a configurator definition group by using the wizard.

## Set up a definition group based on a predefined query

Use this procedure to create a configurator definition based on a predefined query. For example, you can use the following predefined queries to create configurator definition groups for payment remittance and return:

  - ElectronicPaymentAPExport\_BR – Create a configurator definition group for vendor payment remittance and return.

  - ElectronicPaymentARExport\_BR – Create a configurator definition group for customer payment remittance and return.

<!-- end list -->

1.  Click **Organization administration** \> **Periodic** \> **Configurator** \> **Configurator definition groups**.

2.  Create a configurator definition group.

3.  On the **Overview** tab, in the **Definition group** field, enter a unique identification code for the configurator definition group.

4.  In the **Name** field, enter a unique name for the configurator definition group.

5.  Select the **Is Query Based** check box to indicate that the configurator group is based on a predefined query.

6.  In the **AOT query title** field, select a predefined query to create the definition group.
    

    > [!NOTE]
    > <P>This field is available only if you select the <STRONG>Is Query Based</STRONG> check box.</P>



## Set up a configurator definition group by using the wizard

You can create a configurator definition group, and then use the Definition Group Wizard to specify the data that is used by the configurator. You can set up the required selections, such as tables, fields, summaries, sorting, and ranges for the configurator definition group.

1.  Click **Organization administration** \> **Periodic** \> **Configurator** \> **Configurator definition groups**.

2.  Create a configurator definition group.

3.  On the **Overview** tab, in the **Definition group** field, enter a unique identification code for the configurator definition group.

4.  In the **Name** field, enter a unique name for the configurator definition group.

5.  Click **Definition wizard** to open the Definition Group Wizard.
    

    > [!NOTE]
    > <P>This button is available only if the <STRONG>Is Query Based</STRONG> check box is not selected.</P>



6.  Follow the instructions in the wizard to create a configurator definition group. For more information, see [(BRA) Definition group wizard (form)](https://technet.microsoft.com/en-us/library/jj863740\(v=ax.60\))

## See also

[(BRA) Set up the configurator layout group](bra-set-up-the-configurator-layout-group.md)

[(BRA) Set up fiscal document types](bra-set-up-fiscal-document-types.md)

[(BRA) Configurator definition groups (form)](https://technet.microsoft.com/en-us/library/jj730968\(v=ax.60\))

  


