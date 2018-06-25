---
title: Reassign workers to stores after upgrade (Retail)
TOCTitle: Reassign workers to stores after upgrade (Retail)
ms:assetid: f88a79ef-e69d-4ff7-887e-63ba97344ae5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh803001(v=AX.60)
ms:contentKeyID: 44080983
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Reassign workers to stores after upgrade (Retail) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

After you upgrade to Microsoft Dynamics AX 2012 Feature Pack, you must manually reassign existing workers to stores. This step is necessary, because Microsoft Dynamics AX 2009 for Retail did not enforce a worker-to-store relationship, and the upgrade framework cannot derive these relationships.


> [!WARNING]
> <P>If you do not correctly supply data for worker-to-store relationships, workers may be unable to log on to a point of sale (POS) terminal. Alternatively, a worker may be able to log on to a terminal at the wrong store.</P>



## Assign a worker to a store

Follow these steps to assign an existing worker to a store after an upgrade.


> [!TIP]
> <P>The following example shows how to add one worker to one store. You can also add a worker to multiple stores. To add a worker to multiple store, assign an address book that contains the worker to multiple stores.</P>



1.  Open the Microsoft Dynamics AX client.

2.  Click **Organization administration** \> **Setup** \> **Global address book** \> **Address books** to open the **Address books** form.

3.  Click **New** to create a new address book. Enter a name for the address book, and then press Enter. For this example, name the address book **Store1**.

4.  Click **Retail** \> **Common** \> **Retail channels** \> **Retail stores** to open the **Retail stores** form.

5.  Select **Store1**, and then click **Edit**.

6.  In the **Employee address book** field, select **Store1**.

7.  Click **Retail** \> **Common** \> **Workers** to open the **Workers** form.

8.  Select a worker to assign to Store1, and then click **Edit**.

9.  In the **Address books** field, select **Store1**.

10. Run N jobs or A jobs for Staff and Store to replicate the data.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

