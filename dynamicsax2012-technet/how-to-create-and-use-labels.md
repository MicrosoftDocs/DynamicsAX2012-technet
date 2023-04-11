---
title: 'How to: Create and Use Labels'
TOCTitle: 'How to: Create and Use Labels'
ms:assetid: 2017ee25-394b-47c1-9432-9bd5e333a402
ms:mtpsurl: https://technet.microsoft.com/library/Aa620083(v=AX.60)
ms:contentKeyID: 35241543
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# How to: Create and Use Labels 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You should use labels to specify the user interface text for forms and reports. Labels are created in the Label Editor, and then used in text-based properties in the Application Object Tree (AOT) or in X++ code.

The **Label** property determines the name of a report or form. It can be set on table fields, extended data types, or a report or form in the AOT. It is recommended that you set the property on an extended data type so the label is inherited by any object that references the extended data type.

To create a new label, you must create or update a label file. For more information, see [How to: Create a Label File](https://technet.microsoft.com/library/aa844896\(v=ax.60\)).

A label can be up to 2000 characters long. For guidelines on the content of labels, see [Best Practices for Labels](https://technet.microsoft.com/library/aa586081\(v=ax.60\)) and [HelpText Guidelines](https://technet.microsoft.com/library/aa884538\(v=ax.60\)).

## Procedures

### ![Aa620083.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Aa620083.collapse_all(en-us,AX.60).gif")Adding a new label

New labels are added in the Label Editor. If you are using version control, you will have to check out the label file before you add a new label. For more information, see [Label Editor](https://technet.microsoft.com/library/aa617477\(v=ax.60\)).

### To add a label using the Label Editor

1.  Click **Tools** \> **Label** \> **Label editor**.

2.  Type the string you want to use for the label in the **Find what** box, and then click **Find now**.

3.  If a label containing the text already exists, check whether you can reuse this label or whether you should create a new semantic instance.
    
    1.  Look at the **Description** field so see whether there are any notes about the use of the label.
    
    2.  Click the **Used by** button to see where the label is already used in the application.

4.  To create a new label, press CTRL+S to save the text in the **Find what** box as a new label.
    
    Your new label will be allocated a label ID. Use this to refer to the label in code or in the property window for an item in the AOT.

5.  Add a comment in the **Description** field to describe the semantic use of your new label. You should also use this field to add notes that may be helpful to translators.

6.  Save your changes.

### ![Aa620083.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Aa620083.collapse_all(en-us,AX.60).gif")Using labels

### To use a label in the property sheet in the AOT

1.  In the AOT, right-click the object you want to define a label for, and then click **Properties**.

2.  Type the string you want to use in the **Label** property.

3.  Click the Label icon ![Label icon](images/Aa620083.IDELBLBT(en-us,AX.60).gif "Label icon") to open the Label Editor, and then click **Find now** to search for the text in the existing label files.

4.  Select the label from the search results, and then click **Paste label**.

### To use a label in X++ code

  - Click the Insert label icon ![Insert Label Icon](images/Aa620083.idelblicon(en-us,AX.60).gif "Insert Label Icon") in the X++ editor.

## See also

[How to: Find a Label](https://technet.microsoft.com/library/cc624360\(v=ax.60\))

  
**Announcements:** New book: "Inside Microsoft Dynamics AX 2012 R3" now available. Get your copy at the [MS Press Store](https://www.microsoftpressstore.com/store/inside-microsoft-dynamics-ax-2012-r3-9780735685109).

