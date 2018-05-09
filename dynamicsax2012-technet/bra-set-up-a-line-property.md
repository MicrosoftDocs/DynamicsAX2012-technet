---
title: (BRA) Set up a line property
TOCTitle: (BRA) Set up a line property
ms:assetid: 1cfaf228-f899-4ba5-a86a-e7e1eeca3c94
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ853378(v=AX.60)
ms:contentKeyID: 50396749
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (BRA) Set up a line property 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Project/group line properties** form to create a line property and to select the **Debit note setup** check box to generate debit notes for project categories when expense journals are posted.

1.  Click **Project management and accounting** \> **Setup** \> **Categories** \> **Project categories**.

2.  Create a project category.

3.  In the **Category ID** and **Category name** fields, enter an identification code and a description for the project category.

4.  In the **Category group** field, select a category group that has a transaction type of **Expense**.

5.  Click **Setup** \> **Project/group line properties**.

6.  Create a line property.

7.  In the **Valid for** field, select whether the line property applies to all projects, a group of projects, or an individual project. Select one of the following options:
    
      - **Table** – The line property applies to the project that is selected in the **Project relation** field.
    
      - **Group** – The line property applies to all projects in the project group that is selected in the **Project relation** field.
    
      - **All** – The line property applies to all projects.

8.  In the **Project relation** field, select the project or project group that the line property applies to.
    

    > [!NOTE]
    > <P>This field is available only when you select <STRONG>Table</STRONG> or <STRONG>Group</STRONG> in the <STRONG>Valid for</STRONG> field.</P>



9.  In the **Line property** field, select a line property.

10. Select the **Debit note setup** check box to indicate that a debit note is generated when an expense journal is posted for the selected project category.

## See also

[Project categories (form)](https://technet.microsoft.com/en-us/library/aa582118\(v=ax.60\))

[(BRA) Project/group line properties (modified form)](https://technet.microsoft.com/en-us/library/jj911306\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

