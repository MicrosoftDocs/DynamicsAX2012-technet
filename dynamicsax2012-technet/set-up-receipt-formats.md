---
title: Set up receipt formats
TOCTitle: Set up receipt formats
ms:assetid: 28b7d91d-efe5-4c3a-83ec-56ba365117c3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh580594(v=AX.60)
ms:contentKeyID: 39519078
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Set up receipt formats 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

You can create and modify form layouts to control how receipts, invoices, and other documents are printed. Retail includes a form layout designer that you can use to easily and graphically create and modify different kinds of form layouts.


> [!IMPORTANT]
> <P>You must set up form layouts and receipt profiles to print receipts and other documents from Microsoft Dynamics AX for Retail POS. You can include multiple form layouts in a receipt profile, and then assign the receipt profile to a printer by modifying a hardware profile. For more information about how to set up receipt profiles, see <A href="set-up-receipt-profiles.md">Set up receipt profiles</A>.</P>



## Set up a receipt format

1.  Click **Retail** \> **Setup** \> **POS** \> **Receipt formats**.

2.  In the **Receipt format** form, click **New** to create a new form layout, or select an existing form layout.

3.  In the **Receipt format** field, enter an identifier for the form layout, and then select the type of receipt that this layout is used for. You can also enter a description and short name for the receipt in the **Title** field.

4.  On the **General** FastTab, set the following print options:
    
      - **Print as slip** – Select this check box to print a form as a slip.
    
      - **Use Windows printer** – Select this check box to indicate that a Windows printer is used to print receipts from Retail POS.
    
      - **Windows printer name** – Type the name of the network host of the Windows printer. The path must be in Universal Naming Convention (UNC) format: *\\\\servername\\sharename*.
    
      - **Print behavior** – Select when the receipt is printed from Retail POS. You can specify that a receipt is always printed or never printed, or that the cashier chooses whether a receipt is printed.

## Design a receipt format

Use the form layout designer to graphically create the layout of the form document. The **Receipt format designer** form has three sections: **Header**, **Lines**, and **Footer**. Some types of form layout use elements from all three sections, whereas other types use elements from only one or two sections. To view the elements that are available for each section, click the appropriate button in the navigation pane on the left side of the form.

1.  Click **Retail** \> **Setup** \> **POS** \> **Receipt formats**.

2.  In the **Receipt format** form, select a form layout, and then click **Designer**.

3.  To create the elements of the form, select the **Header**, **Lines**, or **Footer** section, and then drag an element from the section to the workspace. Most elements contain variables, which are automatically populated with data from the database. Other elements, such as **Text**, let you print custom text on the receipt.
    

    > [!WARNING]
    > <P>You can specify how many lines each of the three sections spans by adjusting the number in the lower-right corner of the section. To make it easier to modify a section, increase the height of the section by dragging the sizing bar at the bottom of the section. The height of the section on the workspace does not affect the number of lines on the actual receipt.</P>



4.  After you drag the element to the workspace, set the properties for the part in the **Object information** pane at the bottom of the form. Enter one or more of the following settings:
    
      - **Align** – Set the alignment of the field to either **Left** or **Right**.
    
      - **Fill char** – Specify the white-space character. By default, an empty space is used, but you can enter any character.
    
      - **Prefix** – Type the value that appears at the beginning of the field. This setting only applies **Lines** section of the layout.
    
      - **Characters** – Specify the maximum to the elements in the number of characters for the variable. If the text in the field is longer than the number of character that you specify, the text is truncated to fit the field.
    
      - **Variable** –This checkbox is selected automatically if the element is a variable and cannot be customized.
    
      - **Font type** –Set the font style to either **Normal** or **Bold**. Bold letters use two times the space that normal letters use. Therefore, some characters may be truncated.
    
      - **Delete** – Click this button to remove the selected part from the form layout.

## See also

[About setting up Retail POS](about-setting-up-retail-pos.md)

[Receipt formats (form)](https://technet.microsoft.com/en-us/library/hh597228\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

