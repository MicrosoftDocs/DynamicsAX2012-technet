---
title: Assign batch attributes to a potency item
TOCTitle: Assign batch attributes to a potency item
ms:assetid: 20930921-5b41-41ba-b7b8-6fdf6ddbe779
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ838725(v=AX.60)
ms:contentKeyID: 50120608
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- item
- batch
- batch attributes
- potency
---

# Assign batch attributes to a potency item 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to set up a batch attribute to identify an item as a potency item. A potency item is an item that has a specific concentration of an active ingredient.

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Select an item, and then on the **Action Pane**, click **Edit**.

3.  In the **Released product details** form, click the **Manage inventory** FastTab.

4.  In the **Potency** field group, in the **Base attribute** field, select the base attribute for the potency item.
    
    The **Target** field is updated with the optimal value for the attribute that you specified in the **Target** field in the **Batch attributes** form.
    

    > [!NOTE]
    > <P>You can select only the batch attributes that meet the following two conditions:</P>
    > <UL>
    > <LI>
    > <P>The batch attributes are associated with the selected item in the <STRONG>Product specific</STRONG> form.</P>
    > <LI>
    > <P>The batch attributes are assigned the <STRONG>Fraction</STRONG> or <STRONG>Integer</STRONG> attribute type in the <STRONG>Attribute type</STRONG> field in the <STRONG>Batch attributes</STRONG> form.</P></LI></UL>



5.  Select the **Fixed attribute** check box to set the base attribute as a fixed attribute.
    

    > [!NOTE]
    > <P>If inventory transactions are created for the item, the <STRONG>Fixed attribute</STRONG> check box is not available.</P>



6.  In the **Record the attribute value** field, select one of the following options to specify when you can enter a value for the attribute:
    
      - **Receipt entry** – Specify the actual value of the attribute when you create a purchase order, register a batch order, or report a batch order as finished.
    
      - **Quality order result** – Specify the actual value of the attribute when you enter test results in a quality order.

## See also

[About potency management](about-potency-management.md)

[(PM) Released product details (form)](https://technet.microsoft.com/en-us/library/hh352306\(v=ax.60\))

[Create a batch attribute](create-a-batch-attribute.md)

[Batch attributes (form)](https://technet.microsoft.com/en-us/library/hh209255\(v=ax.60\))

[Add a batch attribute to an item](add-a-batch-attribute-to-an-item.md)

[Product specific (form)](https://technet.microsoft.com/en-us/library/hh227369\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

