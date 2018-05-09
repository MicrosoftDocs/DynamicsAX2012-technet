---
title: (RUS) Adjust data in registers manually
TOCTitle: (RUS) Adjust data in registers manually
ms:assetid: 0637b76a-fcb7-4911-aeca-1e561dd6c417
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711357(v=AX.60)
ms:contentKeyID: 49387175
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Adjust data in registers manually 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You can manually add, edit, or delete the calculated register lines.


> [!NOTE]
> <P>You can edit the register lines only if the corresponding register or the dependent registers are in the unapproved status.</P>



1.  Click **General ledger** \> **Journals** \> **Tax register journal**. Click **Lines** to open Register journal lines form

2.  Click **Append** to add new register lines.

3.  Enter the fields, and then click **Save**.
    

    > [!NOTE]
    > <P>When you add a line, the <STRONG>Manual data input</STRONG> field is activated on the <STRONG>General</STRONG> tab.</P>



4.  Select the line that you want to modify, and then click **Change**.

5.  Modify the field values, and then click **Save**.
    

    > [!NOTE]
    > <P>When you modify a line, the <STRONG>Corrected</STRONG> field is automatically activated on the <STRONG>General</STRONG> tab.</P>



6.  To delete approved register lines, clear the **Approved** check box, and then click **Delete**. When the voucher is run, all of the tax register journal lines will be deleted.
    

    > [!NOTE]
    > <P>You can cancel the approval only if all journal lines are unapproved.</P>



7.  Press CTRL+S or close the form.

## See also

[(RUS) Approve the register](rus-approve-the-register.md)

[(RUS) Register journal lines (form)](https://technet.microsoft.com/en-us/library/jj839663\(v=ax.60\))

[(RUS) Create a tax register journal](rus-create-a-tax-register-journal.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

