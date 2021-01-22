---
title: Configure value substitution maps
TOCTitle: Configure value substitution maps
ms:assetid: f3d81371-ac04-4ef8-b180-8d686b754989
ms:mtpsurl: https://technet.microsoft.com/library/Hh202120(v=AX.60)
ms:contentKeyID: 35949381
author: Khairunj
ms.author: daxcpft
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Configure value substitution maps 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX services and Application Integration Framework (AIF), a value substitution map defines a relationship between two values:

  - An internal value, which is stored by Microsoft Dynamics AX

  - An external value, which is contained in a document that is used in an AIF-based transaction

A lookup table contains lookup entries that map internal values to external values. To create, delete, or modify lookup tables, you can use the **Value substitution maps** form. The way that values are substituted depends on the direction of the document transfer:

  - For inbound transfers, the value that you enter in the **Internal value** field replaces the value that you enter in the **External value** field.

  - For outbound transfers, the value that you enter in the **External value** field replaces the value that you enter in the **Internal value** field.

By using lookup tables, you can substitute one value for another in any field that has a corresponding extended data type (EDT). Each lookup table is associated with a single EDT, but you can create multiple lookup tables for the same EDT. Not every field in a service schema is associated with an EDT. For more information about EDTs, see [Extended Data Types (EDTs)](https://go.microsoft.com/fwlink/?linkid=218225) on MSDN.

The **Pipeline value substitution** form displays a list of the EDTs that are associated with elements for a service operation that you have configured for value substitution. You can also use the **Pipeline value substitution** form to associate a lookup table with a document field.

## Create a lookup table

To create a lookup table, follow these steps.

1.  Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Value substitution maps**.

2.  Click **New**.

3.  In the **Lookup table ID** field, enter a unique identifier for the lookup table.

4.  (Optional) In the **Name** field, enter a descriptive name for the lookup table.

5.  In the **Extended data type name** field, select the EDT that you want to use for value substitution.

6.  On the **Lookup entries** FastTab, click **Add**.

7.  In the **Internal value** field, enter the internal value.

8.  In the **External value** field, enter the corresponding external value.

9.  Repeat steps 6 through 9 for each value substitution entry that you want to create in the lookup table for the EDT that you selected.

10. When you have finished creating lookup entries, close the form.

## Use a lookup table

To use a lookup table that you created to enable value substitution, follow these steps.

1.  Open the **Pipeline value substitution** form:
    
    1.  Create or modify an enhanced integration port:
        
        Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Inbound ports**.
        
        –or–
        
        Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Outbound ports**.
    
    2.  On the **Processing options** FastTab, click **Inbound pipelines** to open the **Inbound pipelines** form.
    
    3.  In the **Service operation ID** field, select the service operation for which you want to configure value substitution.
    
    4.  Click **Add**.
    
    5.  In the **Class name** field, select the **AifValueSubstitutor** component.
    
    6.  Press CTRL+S to save the pipeline configuration.
    
    7.  Click **Configure** to configure the pipeline component.
    
    8.  If you are configuring a pipeline for an outbound port, go to step 2. Otherwise, select a parameter in the **Pipeline value substitution parameter selection** form:
        
          - If the **Parameter name** field contains one parameter, select the parameter.
        
          - If the **Parameter name** field does not contain a parameter, you cannot use the pipeline for value substitution together with the service operation that you selected.
        
          - If the **Parameter name** field contains more than one parameter, select the parameter that represents the document for which you want to perform value substitution. The field contains multiple parameters only if the service is a custom service.
        

        > [!NOTE]
        > <P>Outbound ports do not require a parameter, because the return value of the internal function is the only value that can be returned through an outbound port.</P>

    
    9.  Click **Configure value substitution**.

2.  In the **Element name** field of the **Pipeline value substitution** form, find the name of the element for which you want to enable value substitution.

3.  In the corresponding **Lookup table ID** field, select the unique identifier of the lookup table that you created. The only lookup tables that are available are the tables that you defined for the EDT that is associated with the element. The associated EDT is displayed in the **Extended data type name** field.

4.  Repeat steps 2 through 3 for each value substitution that you want to enable for the service operation.

5.  Close the forms.

## See also

[Configure processing options](configure-processing-options.md)

