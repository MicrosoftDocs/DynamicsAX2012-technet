---
title: Set up offline profiles
TOCTitle: Set up offline profiles
ms:assetid: 80d2f7ca-acbb-4b53-b9bd-607ffa52cde9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597147(v=AX.60)
ms:contentKeyID: 39519203
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Set up offline profiles [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

An *offline profile* defines which data is synchronized between a store database and the offline databases at the registers. Each offline profile consists of several *offline scopes*. Offline scopes define the order in which data is synchronized, and which database tables are synchronized. Microsoft Dynamics AX includes a default offline profile that is named "Default pr." The offline scopes that are included in the default offline profile reflect the organization of jobs in **Retail scheduler**.


> [!WARNING]
> <P>You can modify the default offline profile that is included with Microsoft Dynamics AX. However, if you modify a store's offline profile after you have created the store's offline databases, you must run the Retail Channel Configuration Utility again on all the registers in the store to re-create the offline databases for those registers. (In AX 2012 R2 and AX 2012 Feature Pack, the Retail Channel Configuration Utility is called the Store Database Utility.)</P>



## Set up an offline profile

1.  Click **Retail** \> **Setup** \> **POS** \> **Profiles** \> **Offline profiles**.

2.  Press CTRL+N to create a new offline profile, or select an existing profile.

3.  In the **Name** field, type a name for the profile. In the **Description** field, type a description.

4.  On the **Line details** FastTab, click **Add** or select an existing offline scope.

5.  In the **Description** field, select an offline scope.
    
    To set up the new or existing offline scope, see the next procedure.

6.  For Retail Modern POS, the following settings in the SQLite device configuration FastTab are also required:
    
      - **Offline timeout (sec)** – specify the time after which Retail Modern POS will switch to the offline database.
    
      - **Reconnect attempt interval (min)** – specify the interval after which Retail Modern POS will try to reconnect to the Retail server or the channel database.

7.  Repeat steps 4, 5, and 6 for each offline scope that is included in the offline profile.

The configuration options in the following table are not currently implemented.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Location</p></th>
<th><p>Options that have not been implemented</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Offline products FastTab</p></td>
<td><p>No options have been implemented</p></td>
</tr>
<tr class="even">
<td><p>Offline customers FastTab</p></td>
<td><p>No options have been implemented</p></td>
</tr>
<tr class="odd">
<td><p>SQLite device configuration FastTab</p></td>
<td><p>Check for new database</p>
<p>Upload transactions</p>
<p>Image folder</p>
<p>Data export folder</p>
<p>Database export schedule</p></td>
</tr>
</tbody>
</table>


## Set up an offline scope

1.  Click **Retail** \> **Setup** \> **POS** \> **Profiles** \> **Offline profiles**.

2.  In the **Name** field, select an offline profile.

3.  On the **Line details** FastTab, click **Add** or select an existing offline scope, and then click **Offline scope**.

4.  In the **Offline scope** form, in the **Synchronization direction** field, specify the direction in which data is moved during synchronization. Select one of the following options:
    
      - **Download** – Data is only downloaded from the store database to the offline databases.
    
      - **Upload** – Data is only uploaded from the offline databases to the store database.
    
      - **Bidirectional** – Data is downloaded from the store database and uploaded from the offline databases.

5.  On the **Line details** FastTab, click **Add** to add a database table.
    
    –or–
    
    Select a database table, and then click **Remove**.

6.  Repeat steps 3 through 6 for each offline scope that you want to set up.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

