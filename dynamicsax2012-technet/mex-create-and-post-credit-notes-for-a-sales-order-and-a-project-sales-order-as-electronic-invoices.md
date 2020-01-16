---
title: (MEX) Create and post credit notes for a sales order and a project sales order as electronic invoices
TOCTitle: (MEX) Create and post credit notes for a sales order and a project sales order as electronic invoices
ms:assetid: 0606f142-a86e-4aa9-92e7-fd2f80adef83
ms:mtpsurl: https://technet.microsoft.com/library/Hh242110(v=AX.60)
ms:contentKeyID: 36055958
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- create
- credit notes
- electronic invoices
- post
- project sales order
- sales order
audience: Application User
ms.search.region: Mexico
---

# (MEX) Create and post credit notes for a sales order and a project sales order as electronic invoices 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Create credit note** and **Posting invoice** forms to create and post a credit note for a sales order or a project sales order as an electronic invoice. You can create and post a credit note only for an invoiced sales order. For more information, see [Sales posting (form)](https://technet.microsoft.com/library/aa550287\(v=ax.60\)).

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.
    
    –or–
    
    Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**.
    

    > [!NOTE]
    > <P>You must select a project in the <STRONG>Projects</STRONG> form, and then click <STRONG>Manage</STRONG> &gt; <STRONG>Item task</STRONG> &gt; <STRONG>Sales order</STRONG> to create a project sales order.</P>



2.  Double-click a sales order that has the **Status** field as **Invoiced**.

3.  In the **Sales order** form, click **Sell** \> **Credit note**.

4.  In the **Create credit note** form, select the **Select all** check box to create a credit note for all the transactions in the sales order.
    

    > [!NOTE]
    > <P>Select the <STRONG>Mark</STRONG> check box to create a credit note for a specific transaction in the sales order.</P>



5.  Click **OK**. The details of the selected transaction are updated with the negative amount in the **Sales order lines** FastTab in the **Sales order** form.

6.  Click **Invoice** \> **Invoice**.

7.  In the **Posting invoice** form, select the **Print invoice** check box to print the credit note after it is posted.

8.  Select the **Send e-mail** check box to send the .pdf and .xml files as email attachments to the customer.

9.  Click **OK** to post the credit note as an electronic invoice. The .pdf and .xml files of the electronic invoice are sent as email attachments to the customer. A copy of the .xml file of the electronic invoice is archived.
    

    > [!NOTE]
    > <P>Click <STRONG>Batch</STRONG> to post the credit note as an electronic invoice by using a batch process.</P>



10. Close the forms.

## See also

[(MEX) Create and post a sales order and a project sales order as electronic invoices](mex-create-and-post-a-sales-order-and-a-project-sales-order-as-electronic-invoices.md)

  


