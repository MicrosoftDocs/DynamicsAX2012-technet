---
title: Mass create quotations from a campaign
TOCTitle: Mass create quotations from a campaign
ms:assetid: 8e4f3c5a-81f1-43d4-a7b8-7328475a59ee
ms:mtpsurl: https://technet.microsoft.com/library/Aa498358(v=AX.60)
ms:contentKeyID: 36058516
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Mass create quotations from a campaign 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

1.  Click **Sales and marketing** \> **Periodic** \> **Quotation update** \> **Mass create quotations**.

2.  On the **General** tab, in the **Group ID** field, select a template group.

3.  In the **Template name** field, select a template.

4.  In the **Calculation method** field group, select an option to define the prices that you want to use for the quotations:
    
      - **Based on current values** – Use the prices on the item card.
    
      - **Based on template values** – Use the prices that are specific to the selected quotation template.

5.  In the **Expiration date** field, select the expiration date for the quotations. The default value in this field is determined by the number of days that you define in the **Days campaign expires** field in the **Accounts receivable parameters** form.

6.  Click the **Select** button to modify and filter the query that generates the quotations.
    

    > [!NOTE]
    > <P>You can filter the contacts by using the <STRONG>Title</STRONG>, <STRONG>VIP</STRONG> and <STRONG>Direct mail</STRONG> fields to select the relevant contacts.</P>
    > <P>If no contacts are selected or filtered, sales quotations for the customer or business relation are sent to all contacts who are associated with this customer or business relation.</P>
    > <P>If no contacts are associated with the customer or business relation, no sales quotations are created.</P>



## See also

[Mass create quotations](mass-create-quotations.md)

  


