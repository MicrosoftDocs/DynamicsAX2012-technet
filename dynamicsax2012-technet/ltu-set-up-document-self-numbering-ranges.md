---
title: (LTU) Set up document self-numbering ranges
TOCTitle: (LTU) Set up document self-numbering ranges
ms:assetid: bc3767a6-b98c-4679-976d-74fec54200c5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ665174(v=AX.60)
ms:contentKeyID: 49386755
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (LTU) Set up document self-numbering ranges 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You can assign specific number sequences to invoices and packing slips that are generated in the **Accounts receivable**, **Accounts payable**, **Inventory management**, and **Project** modules. You also can specify individual number sequences for different users and user groups, customer and vendor groups, or warehouses. The sequence numbers are printed on the **Invoice register** and the **Packing slip registration journal** reports.

You can also number invoices and packing slips manually. When you enter document numbers manually, you can turn on number verification for invoices and packing slips in **Accounts receivable** to ensure that the numbers are unique. To use number sequences for invoices and packing slips, you must select the **Invoice** and the **Packing slip numbering** by user or user groups. You must specify the module, customer or vendor group, and document type for which the number sequences will be used.

1.  Click **Organization administration** \> **Common** \> **Number sequences** \> **Registers** \> **Counters management**.

2.  Press CTRL+N to create a new record.

3.  In the **Module** field, select the module.

4.  In the **Account code** field, select **Group** or **All** as the account code.

5.  In the **Code** field, select the group code.
    

    > [!NOTE]
    > <P>The group code list is based on the options selected in the <STRONG>Receipt/Expenditure</STRONG> and the <STRONG>Account code</STRONG> fields. The <STRONG>Code</STRONG> field is unavailable if <STRONG>All</STRONG> is selected in the <STRONG>Account code</STRONG> field.</P>



6.  In the **Type** field, select either **Invoice** or **Packing slip**.
    

    > [!NOTE]
    > <P>The <STRONG>Invoice</STRONG> type is used only for <STRONG>Sales</STRONG> or <STRONG>Purchase</STRONG> modules.</P>



7.  Click the **Include to register** check box if the document is to be included in the register.

8.  Click the **Auto numbering** check box to suggest an auto-numbering code in **Sales**, **Purchase**, or **Project order**, if necessary.

9.  Press CTRL+S or close the form.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

