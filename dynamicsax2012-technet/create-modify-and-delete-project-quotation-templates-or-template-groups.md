---
title: Create, modify, and delete project quotation templates or template groups
TOCTitle: Create, modify, and delete project quotation templates or template groups
ms:assetid: cebd2664-f8f8-4924-9cc7-f4a2b22218fa
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Bb220752(v=AX.60)
ms:contentKeyID: 36059471
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- project quotation template
- quotation template
- template group
- sales quotation template
audience: Application User
ms.search.region: Global
---

# Create, modify, and delete project quotation templates or template groups 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you create quotation templates, you must create template groups. Quotation templates must be organized into template groups before they can be used.

## Create a quotation template group

1.  Click **Project management and accounting** \> **Setup** \> **Quotations** \> **Quotation template groups**.

2.  In the **Quotation template groups** form, click **New**.

3.  In the **Group ID** field, enter a unique name for the template group.

4.  In the **Description** field, enter a description of the template group.

## Create a project quotation template

1.  Click **Project management and accounting** \> **Common** \> **Quotations** \> **Project quotations**.

2.  On the **Action Pane**, on the **Quotation** tab, in the **New** group, click **Project quotation**.

3.  In the **Create quotation** form, in the **Account type** list, select a prospect.

4.  Do one of the following:
    
      - If you selected the account type **Prospect**, select an prospect ID in the **Prospect** field.
    
      - If you selected the account type **Customer**, select options in the **Customer account** and **Invoice account** fields.
    

    > [!NOTE]
    > <P>Because this template is available to several business accounts based on different criteria than the criteria in this form, it is not important which business account you select.</P>



5.  Click **OK**.

6.  In the **Project quotation** form, on the **Action Pane**, on the **Project quotation** tab, in the **Show** group, click **Header view**.

7.  On the **Setup** FastTab, in the **Group ID** field, select a template group.

8.  In the **Template name** field, type a name for the template that you are creating. If you are ready to begin using the template, select the **Active** check box.
    

    > [!NOTE]
    > <P>If you do not want the template to be available for use now, clear the <STRONG>Active</STRONG> check box. You can return to this record and enable the template for use when you are ready.</P>

    

    > [!IMPORTANT]
    > <P>You must specify a template name before you add lines to the template. You cannot change a quotation to a template after you have added lines to it.</P>



9.  On the **Action Pane**, on the **Project quotation** tab, in the **Show** group, click **Line view**.

10. On the **Lines** pane, click **Add line** to create an item line for the quotation template.

11. Select a transaction type, project category, line property, unit price, and any other options that you want to specify.

12. Repeat steps 8 and 9 for each item line that is required for the quotation template.

## Modify a project quotation template

You can modify an existing project quotation template after it has been created by editing the information on the selected quotation template lines.

## Delete templates

1.  Click **Project management and accounting** \> **Common** \> **Quotations** \> **Project quotations**.

2.  In the **Show** filter, select **Templates**.

3.  Select the template that you want to delete.

4.  On the **Action Pane**, on the **Quotation** tab, in the **Maintain** group, click **Delete**.


> [!NOTE]
> <P>You cannot mass delete quotation templates. If you select templates when you mass delete quotations, the templates are not transferred to the <STRONG>Delete quotations</STRONG> form.</P>



## See also

[Quotation template groups (form)](https://technet.microsoft.com/en-us/library/aa615258\(v=ax.60\))

[Project quotation (form)](https://technet.microsoft.com/en-us/library/aa557295\(v=ax.60\))

  


