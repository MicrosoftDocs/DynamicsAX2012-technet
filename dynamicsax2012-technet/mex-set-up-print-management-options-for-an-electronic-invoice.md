---
title: (MEX) Set up print management options for an electronic invoice
TOCTitle: (MEX) Set up print management options for an electronic invoice
ms:assetid: 8cb8f8ff-6ea3-48f2-be97-6860e9e206fd
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh209349(v=AX.60)
ms:contentKeyID: 36058483
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (MEX)
- set up
- print management
- electronic invoice
---

# (MEX) Set up print management options for an electronic invoice [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Print management setup** and **Print destination settings** forms to set up print management options for an electronic invoice. You can also set up print management options for a customer or vendor to override the print management destination setup for different modules.

1.  Click **Accounts receivable** \> **Setup** \> **Forms** \> **Form setup**.

2.  Click **Print management setup**.

3.  Right-click a module name, and then click **Expand all**. The document types for the selected module are displayed.
    
    Select an original record of an invoice type (sales order invoice, free text invoice, or project invoice), and then in the right pane, click the **Destination** lookup button \> **Printer setup**.

4.  In the **Print destination settings** form, select **File** in the left pane, and then in the **File name** field, type Invoice.

5.  In the **File format** field, select **PDF**, and then click **OK**.
    

    > [!NOTE]
    > <P>Verify that the <STRONG>Destination</STRONG> field in the <STRONG>Print management setup</STRONG> form is updated with <STRONG>File: Invoice.pdf</STRONG>.</P>



6.  Close the forms.

## See also

[About print management processing](about-print-management-processing.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

