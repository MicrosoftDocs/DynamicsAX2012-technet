---
title: Set up workers (Retail essentials)
TOCTitle: Set up workers (Retail essentials)
ms:assetid: 791a7d96-8406-4214-a1d5-5e0bcf478da4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn736902(v=AX.60)
ms:contentKeyID: 62200379
ms.date: 11/13/2014
mtps_version: v=AX.60
f1_keywords:
- MsDynAx060.Forms.HcmWorkerListPage
---

# Set up workers (Retail essentials) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up your employees as workers in Retail essentials.

Before you can set up workers, you must create the permission groups that you will assign the workers to. These groups specify the actions that workers can perform in Microsoft Dynamics AX for Retail POS at the stores. For more information, see [Set up permission groups and operations (Retail essentials)](set-up-permission-groups-and-operations-retail-essentials.md).

1.  Click **Retail essentials** \> **Employees** \> **Workers**.

2.  On the **Workers** list page, on the **Worker** tab, on the **Action Pane**, in the **New** group, click **Hire new worker**.

3.  In the **Create new worker** form, enter the worker’s first, middle, and last names. In the **Job** field, select the job that the worker is hired to do, such as **Cashier** or **Manager**. Enter the date that the worker’s employment starts, and then click **Hire new worker**.
    

    > [!NOTE]
    > <P>In the <STRONG>Worker</STRONG> form, on the <STRONG>Profile</STRONG> link, on the <STRONG>Worker summary</STRONG> FastTab, the <STRONG>Personnel number</STRONG> field can be automatically populated, based on the number sequence that is set up for workers. The worker then uses this personnel number to log on to the point of sale (POS) system.</P>



4.  In the **Address books** field, select the address book to assign the worker to.

5.  Click the **Retail** link, and then, on the **Screen layout** FastTab, click **Add**. In the **Screen layout ID** field, select the POS screen layout if the worker uses a special screen layout on the POS system. If the worker uses the POS screen layout that is assigned to the store, leave this field blank.

6.  On the **Retail** FastTab, under **POS authentication**, in the **Password** field, specify the password that the worker uses to log on to the POS system.

7.  To select a POS permission group for the worker, click the **POS permissions** link.

8.  In the **POS position permissions** form, follow one of these steps:
    
      - In the **Position** field, select a position for the worker. You must assign the worker to a position. Otherwise, the worker does not have appropriate access to the POS system.
    
      - Select the **Override permissions** check box, and then either select a permission group in the **POS permission group** field or select the check boxes for the appropriate permissions.

9.  Enter any other appropriate information in the **Profile**, **Employment**, and **Retail** sections.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

