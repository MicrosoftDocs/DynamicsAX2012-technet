---
title: Set up receipt formats (Retail essentials)
TOCTitle: Set up receipt formats (Retail essentials)
ms:assetid: 0139ba32-192b-4c9a-9b6b-a54f89453594
ms:mtpsurl: https://technet.microsoft.com/library/Dn716035(v=AX.60)
ms:contentKeyID: 62200300
author: Khairunj
ms.date: 08/15/2014
mtps_version: v=AX.60
f1_keywords:
- MsDynAx060.Forms.RetailFormLayoutDesigner
---

# Set up receipt formats (Retail essentials) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to create and modify form layouts to control how receipts, invoices, and other documents are printed. Retail essentials includes a form layout designer that you can use to easily and graphically create and modify various kinds of form layout.

**Prerequisite**: Before you can print receipts and other documents from Retail essentials, you must set up form layouts and receipt profiles. You can include multiple form layouts in a receipt profile, and then assign the receipt profile to a printer by modifying a hardware profile. For more information about how to set up receipt profiles, see [Set up receipt profiles (Retail essentials)](set-up-receipt-profiles-retail-essentials.md).


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



## Set up a receipt format

1.  Click **Retail essentials** \> **Channels** \> **Setup** \> **POS** \> **Receipt formats**.

2.  In the **Receipt formats** form, click **New** to create a new receipt format, or select an existing format.

3.  In the **Receipt format** field, enter an identifier for the receipt format, and then select the type of receipt that this format is used for. You can also enter a description and short name for the receipt format in the **Title** field.

4.  On the **General** FastTab, set the following print options:
    
      - **Prompt question** – Select this check box to prompt the cashier to confirm that the receipt format should be used.
    
      - **Print as slip** – Select this check box to print a form as a slip.
    
      - **Print behavior** – Select an option to specify when the receipt is printed from Retail essentials. You can specify that a receipt is always printed or never printed, or that the cashier chooses whether a receipt is printed.

## Design a receipt format

Use the receipt format designer to graphically create the layout of the form document. The **Receipt format designer** form has three sections: **Header**, **Lines**, and **Footer**. Some types of form layout use elements from all three sections, whereas other types use elements from only one or two sections. To view the elements that are available for each section, click the appropriate button in the navigation pane on the left side of the form.

1.  Click **Retail essentials** \> **Channels** \> **Setup** \> **POS** \> **Receipt formats**.

2.  In the **Receipt formats** form, select a receipt format, and then click **Designer**.

3.  To create the elements of the form, select the **Header**, **Lines**, or **Footer** section, and then drag an element from the section to the workspace. Most elements contain variables that are automatically populated with data from the database. Other elements, such as **Text**, let you print custom text on the receipt.
    
    <table>
    <colgroup>
    <col style="width: 100%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><img src="images/Ee355075.alert_security(AX.60).gif" title="Security note" alt="Security note" /><strong>Security Note</strong></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>You can specify how many lines each section spans by adjusting the number in the lower-right corner of the section. To make it easier to modify a section, you can increase the height of the section on the workspace by dragging the sizing handle at the bottom of the section. The height of the section on the workspace does not affect the number of lines on the actual receipt.</p></td>
    </tr>
    </tbody>
    </table>


4.  After you drag an element to the workspace, set the properties for the element in the **Object information** pane at the bottom of the form. Enter one or more of the following settings:
    
      - **Align** – Set the alignment of the field to either **Left** or **Right**.
    
      - **Fill character** – Specify the white-space character. By default, a space is used, but you can enter any character.
    
      - **Prefix** – Type the value that appears at the beginning of the field. This setting applies only to the **Lines** section of the layout.
    
      - **Characters** – Specify the maximum number of characters for the variable in the element. If the text in the field is longer than the number of character that you specify, the text is truncated to fit.
    
      - **Variable** –This check box is selected automatically if the element is a variable and cannot be customized.
    
      - **Font type** –Set the font style to either **Normal** or **Bold**. Bold letters use two times as much space as normal letters. Therefore, some characters might be truncated.
    
      - **Delete** – Click this button to remove the selected element from the form layout.

## See also

[Set up receipt options (Retail essentials)](set-up-receipt-options-retail-essentials.md)

[Setting up Retail POS (Retail essentials)](setting-up-retail-pos-retail-essentials.md)

  


