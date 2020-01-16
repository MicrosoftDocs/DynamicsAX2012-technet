---
title: Mass create quotations
TOCTitle: Mass create quotations
ms:assetid: e764fc5e-3529-49d6-b336-d23db4c6e897
ms:mtpsurl: https://technet.microsoft.com/library/Aa573192(v=AX.60)
ms:contentKeyID: 36059813
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- quotations
- sales
- quotes
- quotation
- quote
- mass
audience: Application User
ms.search.region: Global
---

# Mass create quotations 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If you have to create similar quotations for many different sales targets, you can mass create the quotations instead of creating them one-by-one. You can do this for sales quotations and project quotations. When you mass create any kind of quotation, you must base the quotation on a quotation template.

All mass created quotations are based on your customer or prospect contacts.

1.  Click **Sales and marketing** \> **Periodic** \> **Quotation update** \> **Mass create quotations**.
    
    –or–
    
    Click **Project management and accounting** \> **Periodic** \> **Quotations** \> **Mass create quotations**.

2.  In the **Group ID** field, select a **template group**.

3.  In the **Template name** field, select the **template** that you want to use.

4.  In the **Calculation method** field, select which prices you want to use for the quotations. **Based on current values** gives you the prices on the item card, and **Based on template values** gives you the prices on the selected quotation template.

5.  In the **Expiration date** field, select the expiration date for the quotations. The default value in this field is determined by the number of days that you define in the **Days campaign expires** field on the **Accounts receivable parameters** form.

6.  Click the **Select** button to modify and filter the query that generates the quotations.
    

    > [!NOTE]
    > <P>On the <STRONG>Range</STRONG> tab, in the field that is named <STRONG>Field</STRONG>, you can filter the contacts by, for example, <STRONG>Title</STRONG>, <STRONG>VIP</STRONG> and <STRONG>Direct mail</STRONG> to select the relevant contact persons.</P>
    > <P>If no contacts are selected or filtered, sales quotations for the customer or prospect are sent to all contacts who are associated with this customer or prospect.</P>
    > <P>If no contacts are associated with the customer or prospect, no sales quotations are created.</P>



## See also

[Create template groups](create-template-groups.md)

  


