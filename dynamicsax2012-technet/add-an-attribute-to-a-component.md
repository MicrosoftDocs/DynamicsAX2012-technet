---
title: Add an attribute to a component
TOCTitle: Add an attribute to a component
ms:assetid: d3f0819a-9c58-464a-a936-a71725552457
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597254(v=AX.60)
ms:contentKeyID: 39519332
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Add an attribute to a component 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Attributes are the values that you can select for a component when you configure a product. Attributes are grouped as attribute types. For more information, see [Set up attributes and attribute types](set-up-attributes-and-attribute-types.md).

1.  Click **Product information management** \> **Common** \> **Product configuration models**.

2.  Select the product model that the component is assigned to, and then click **Edit** on the **Action Pane**.

3.  Select the component in the component tree on the left side of the **Constraint-based product configuration model details** form, and then click the **Attributes** FastTab.

4.  On the toolbar, click **Add**.

5.  In the **Name** field, enter a name for the attribute.

6.  In the **Description** field, enter a description of the attribute.
    

    > [!NOTE]
    > <P>The name and the description are important, because they enable you to provide information about the attribute to a person who is configuring a product.</P>



7.  In the **Solver name** field, enter the name of the component in Optimization Modeling Language (OML) syntax. The name must start with a letter or an underscore, and cannot contain spaces or special characters such as ampersands (&) and number signs (\#).

8.  The following settings for the attribute are optional:
    
      - To specify the default value for the attribute, select the **Set default** check box. You must then select the default attribute value for the selected attribute type in the **Default value** field.
    
      - If you do not want the attribute to be displayed during a product configuration session, select the **Hidden** check box. You can also specify when the attribute is hidden by entering an expression in the **Condition** field.
    
      - To require that a value be selected for this attribute, select the **Mandatory** check box. You can also specify when the attribute is mandatory by entering an expression in the **Condition** field.
    
      - To display the attribute but not let a user change its value, select the **Read-only** check box. You can also specify when the attribute is read-only by entering an expression in the **Condition** field.
    
      - To specify that the attribute must be considered when the system is determining whether a configuration should be reused, select the **Include in reuse** check box.

## See also

[Attributes (form)](https://technet.microsoft.com/en-us/library/hh242817\(v=ax.60\))

[About product configuration models](about-product-configuration-models.md)

[About reusing configurations](about-reusing-configurations.md)

[Create components](create-components.md)

[Components (form)](https://technet.microsoft.com/en-us/library/hh227490\(v=ax.60\))

  


