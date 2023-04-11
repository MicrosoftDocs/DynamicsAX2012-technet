---
title: (RUS) Set up officials who generate a transportation invoice and a job ticket
TOCTitle: (RUS) Set up officials who generate a transportation invoice and a job ticket
ms:assetid: 7a26496d-2d00-4266-ba86-0ff1639c0ec7
ms:mtpsurl: https://technet.microsoft.com/library/JJ678380(v=AX.60)
ms:contentKeyID: 49387610
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up officials who generate a transportation invoice and a job ticket 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic applies to features in the **Inventory management** module. It does not apply to features in the [Warehouse management](warehouse-management.md) module.

Use the **Officials** form to specify the officials who are involved in the transportation of cargo. You can select the officials who are responsible for intercompany and intracompany transactions.

You must set up records for the officials who are responsible for transportation on both sides of the transactions, so you must set up records for the officials both on the customer or vendor side, and on the company side. This information is required when you generate and print a transportation invoice and a job ticket that are based on a bill of lading. For more information, see [(RUS) About transportation invoices and job tickets that are based on bills of lading](rus-about-transportation-invoices-and-job-tickets-that-are-based-on-bills-of-lading.md).

1.  Click **Organization administration** \> **Setup** \> **Contacts** \> **Officials**.

2.  To set up records for the officials who are responsible for transportation on outgoing documents for customers, click the **Sales orders** tab, and then select **Invoice** or **Invoice - credit-note**.
    
    1.  Create a record for an official. In the **Position** field, select **Customer transportation responsible**.
    
    2.  In the **Name** field, select the customer contact who is responsible for transportation.
    
    3.  Create a record for an official. In the **Position** field, select **Transportation responsible**.
    
    4.  In the **Name** field, select the company contact who is responsible for transportation.

3.  To set up records for the officials who are responsible for transportation on incoming documents for vendors, click the **Purchase orders** tab, and then select **Invoice** or **Invoice - credit-note**.
    
    1.  Create a record for an official. In the **Position** field, select **Vendor transportation responsible**.
    
    2.  In the **Name** field, select the vendor contact who is responsible for transportation.
    
    3.  Create a record for an official. In the **Position** field, select **Transportation responsible**.
    
    4.  In the **Name** field, select the company contact who is responsible for transportation.

4.  To set up records for the officials who are responsible for transportation on incoming or outgoing warehouse documents, click the **Inventory item management** tab, and then select **Issue slip for sales order (M-15)** or **Issue slip for transfer order (M-15)**.
    
    1.  Create a record for an official. In the **Position** field, select **Customer transportation responsible**.
    
    2.  In the **Name** field, select the customer contact who is responsible for transportation.
    
    3.  Create a record for an official. In the **Position** field, select **Transportation responsible**.
    
    4.  In the **Name** field, select the company contact who is responsible for transportation.
        

        > [!NOTE]
        > <P>You can set up a record for a <STRONG>Transportation responsible</STRONG> official only if you selected <STRONG>Issue slip for transfer order (M-15)</STRONG>.</P>


  


