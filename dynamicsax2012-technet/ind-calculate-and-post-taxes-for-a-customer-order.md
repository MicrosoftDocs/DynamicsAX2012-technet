---
title: (IND) Calculate and post taxes for a customer order
TOCTitle: (IND) Calculate and post taxes for a customer order
ms:assetid: a453d52b-adc3-4b1c-b773-5ee97a229940
ms:mtpsurl: https://technet.microsoft.com/library/Dn268484(v=AX.60)
ms:contentKeyID: 54917023
author: Khairunj
ms.date: 05/06/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.SalesTable
- IN - 00015
audience: Application User
ms.search.region: India
---

# (IND) Calculate and post taxes for a customer order 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the following procedure to calculate and post taxes for a retail customer order.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 1 for AX 2012 R2.</P>



1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Select the sales order that you created in Retail POS. For more information, see [View store transactions](view-store-transactions.md).

3.  On the **Action Pane**, on the **Sell** tab, click **Charges** to open the **Charges transactions** form.

4.  Create a charges transaction. For more information, see [View store transactions](view-store-transactions.md).

5.  On the **Tax information** tab, in the **Location** field, select the location of the legal entity. The **Address** field is updated with the address information in the **Legal entities** form. The **STC number** field is updated with information from the **Manage tax information** form. For more information, see [Legal entities (form)](https://technet.microsoft.com/library/hh242860\(v=ax.60\)) and [(IND) Manage tax information (form)](https://technet.microsoft.com/library/jj664802\(v=ax.60\)).

6.  In the **Tax information** field, select the tax information for the legal entity, and then close the form.

7.  In the **Sales order** form, on the **Invoice** tab, click **Invoice**.

8.  In the **Posting invoice** form, click **OK** to post the sales invoice.


> [!NOTE]
> <P>You can also set up the tax information for a sales quotation in the <STRONG>Charges transactions</STRONG> form. On the <STRONG>All quotations</STRONG> list page, on the <STRONG>Action Pane</STRONG>, on the <STRONG>Quote</STRONG> tab, click <STRONG>Maintain charges.</STRONG></P>


  


