---
title: Set up offline profiles (Retail essentials)
TOCTitle: Set up offline profiles (Retail essentials)
ms:assetid: d551e524-2b83-4dc2-a135-95a008406452
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn736960(v=AX.60)
ms:contentKeyID: 62200437
ms.date: 12/17/2014
mtps_version: v=AX.60
---

# Set up offline profiles (Retail essentials) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up offline profiles to specify which data is synchronized between a retail store database and the offline databases at point-of-sale (POS) registers. Each offline profile consists of several *offline scopes*. Offline scopes define the order in which data is synchronized, and which database tables are synchronized.

Retail essentials includes a default offline profile that is named "Default pr." The offline scopes that are included in the default offline profile are similar to the organization of jobs in **Retail scheduler**. You can set up custom offline profiles to fit your business needs.


> [!WARNING]
> <P>You can modify the default offline profile that is included with Retail essentials. However, if you modify a store's offline profile after you create the store's offline databases, you must run the Store Database Utility again on all the registers in the store to reprovision the offline databases for those registers.</P>



## Set up an offline profile

Use this procedure to set up an offline profile.

1.  Click **Retail essentials** \> **Channels** \> **Setup** \> **POS** \> **Profiles** \> **Offline profiles**.

2.  Press CTRL+N to create a new offline profile, or select an existing profile.

3.  In the **Name** field, type a name for the profile. In the **Description** field, type a description.

4.  On the **Offline tables** FastTab, click **Add**, or select an existing offline scope.

5.  In the **Description** field, select an offline scope.
    
    To create a new offline scope or modify an existing one, see the procedure “Set up an offline scope” in the following section.

6.  On the **Offline products** FastTab, select whether to include all assorted products or a limited amount of products in the profile. If you select to only include a limited amount, enter the product information.

7.  On the **Offline customers** FastTab, select whether to include all available customers or only a limited amount. If you select to include only a limited amount of customers, enter the customer information.

8.  If you are using Commerce Runtime (CRT), on the **SQLite device configuration** FastTab, enter the appropriate information.

9.  Repeat steps 4 through 8 for each offline scope that is included in the offline profile.

## Set up an offline scope

Use this procedure to set up the offline scope for an offline profile.

1.  Click **Retail essentials** \> **Channels** \> **Setup** \> **POS** \> **Profiles** \> **Offline profiles**.

2.  In the **Name** field, select an offline profile.

3.  Click **Offline scope**.

4.  In the **Offline scope** form, in the **Synchronization direction** field, specify the direction in which data is moved during synchronization. Select one of the following options:
    
      - **Download** – Data is only downloaded from the store database to the offline databases.
    
      - **Upload** – Data is only uploaded from the offline databases to the store database.
    
      - **Bidirectional** – Data is downloaded from the store database and uploaded from the offline databases.

5.  In the **Synchronization frequency** field, enter how often the store database and offline database should be synchronized.

6.  On the **Line details** FastTab, click **Add** to add a database table.
    
    –or–
    
    Select a database table, and then click **Remove**.

7.  Repeat steps 3 through 6 for each offline scope that you want to set up.


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>


  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

