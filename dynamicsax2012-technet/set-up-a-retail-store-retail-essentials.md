---
title: Set up a retail store (Retail essentials)
TOCTitle: Set up a retail store (Retail essentials)
ms:assetid: afcfe929-f933-41a9-b79f-5bffb5adaaec
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn736935(v=AX.60)
ms:contentKeyID: 62200412
ms.date: 08/15/2014
mtps_version: v=AX.60
f1_keywords:
- MsDynAx060.Forms.RetailStoreTableListPage
- afcfe929-f933-41a9-b79f-5bffb5adaaec
- MsDynAx060.afcfe929-f933-41a9-b79f-5bffb5adaaec
---

# Set up a retail store (Retail essentials) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up a retail store. In Retail essentials, a retail (brick-and-mortar) store is considered a type of warehouse. In the following procedure, you first create a warehouse and define it as a store. You then create a new store and assign the warehouse to it.

After you set up a store, you must add it to an organization hierarchy that is assigned to a purpose. For example, the organization hierarchy can be used for assortments, replenishment, or reporting. For more information, see [Working with organizations and organizational hierarchies (Retail essentials)](working-with-organizations-and-organizational-hierarchies-retail-essentials.md)

To set up a store in Retail essentials, follow these steps:

1.  Click **Retail essentials** \> **Channels** \> **Warehouses**.

2.  Select an existing warehouse, or click **New** to create a new warehouse.

3.  On the **Retail** FastTab, select the **Store** check box.

4.  Enter other information that is required for the warehouse, and then close the form.

5.  Click **Retail essentials** \> **Channels** \> **Retail stores**.

6.  On the **Retail stores** page, on the **Action Pane**, on the **Store** tab, in the **New** group, click **Retail store**.

7.  On the **General** FastTab, enter information in the following fields. All of this information is required.
    
      - **Name** – Type a name for the new store.
    
      - **Store number** – If the **Store number** field is not automatically filled in, enter an ID number for the store.
    
      - **Warehouse** – Select the warehouse that you selected or created in step 2.
    
      - **Store time zone** – Select the time zone for the store location.
    
      - **Real-time Service profile** – Select the Real-time Service profile for the store.
    
      - **Sales tax group** – Select the sales tax group that is used at the store.
    
      - **Default customer** – Select the default customer that is used at the store. Transactions that do not have a specific customer use this customer.

8.  On the **General** FastTab, specify any other settings that you require.
    

    > [!TIP]
    > <P>For information about specific fields, press F1 in the <STRONG>Stores</STRONG> form.</P>



9.  On the other FastTabs, specify any other settings that you require.


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



## See also

[Setting up retail stores (Retail essentials)](setting-up-retail-stores-retail-essentials.md)

[Working with organizations and organizational hierarchies (Retail essentials)](working-with-organizations-and-organizational-hierarchies-retail-essentials.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

