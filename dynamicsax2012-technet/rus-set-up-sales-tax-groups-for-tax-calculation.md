---
title: (RUS) Set up sales tax groups for tax calculation
TOCTitle: (RUS) Set up sales tax groups for tax calculation
ms:assetid: 33631c01-71aa-41c6-9829-65491fe9aa5c
ms:mtpsurl: https://technet.microsoft.com/library/JJ665259(v=AX.60)
ms:contentKeyID: 49387347
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up sales tax groups for tax calculation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Sales tax groups** form to set up sales tax groups for customers and vendors. The tax codes that you assign to the sales tax group do not relate to the items in your inventory.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax groups**.

2.  Press CTRL+N to create a new line, and enter the required details.
    

    > [!NOTE]
    > <P>For more information, see "Set up and use a sales tax group" and "Sales tax groups (form)" in the Application and Business Processes help.</P>



3.  In the **Sales tax group** field, enter a sales tax group code.

4.  In the **Description** field, enter a name that describes the sales tax group.

5.  In the **Sales tax group setup** field, select **Sales tax codes**.
    

    > [!NOTE]
    > <P><STRONG>Sales tax jurisdiction</STRONG> is selected only if the company conducts business in the United States of America.</P>



6.  In the **Rounding by** field, select the adjustment criteria for the sales tax codes of a sales tax group from the following options:
    
      - **Sales tax codes** – The tax amount is determined for each line and is then added up for each tax code.
    
      - **Sales tax code combinations** – Tax amounts are arranged in groups for all lines with the same tax codes, and then the tax amounts are adjusted.

7.  Click the **Setup** tab, and then press CTRL+N to create a new line and specify all tax codes to be included in the new sales tax group.
    

    > [!NOTE]
    > <P>The same tax code can be included in several sales tax groups.</P>



8.  Press CTRL+S or close the form.
    

    > [!NOTE]
    > <P>Click <STRONG>General ledger</STRONG> &gt; <STRONG>Reports</STRONG> &gt; <STRONG>Reconciliation</STRONG> &gt; <STRONG>Sales tax</STRONG> &gt; <STRONG>Sales tax</STRONG>.</P>



## See also

[(RUS) Set up item sales tax groups for tax calculation](rus-set-up-item-sales-tax-groups-for-tax-calculation.md)

  


