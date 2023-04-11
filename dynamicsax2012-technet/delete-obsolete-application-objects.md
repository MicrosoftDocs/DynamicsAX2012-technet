---
title: Delete obsolete application objects
TOCTitle: Delete obsolete application objects
ms:assetid: 414f56a5-6d2d-46d8-9d96-a57b54875510
ms:mtpsurl: https://technet.microsoft.com/library/Hh769361(v=AX.60)
ms:contentKeyID: 43876669
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Delete obsolete application objects 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

After you have verified the integrity of your upgraded system and operated it successfully for several months, we recommend that you disable the **Keep update objects 5.0** and **Keep update objects 6.0** configuration keys. When you disable these keys, obsolete application objects that have the prefix DEL\_ will be deleted.


> [!WARNING]
> <P>Do not disable these configuration keys until after your data upgrade is completed and thorough testing verifies the integrity of your system.</P>



## Disable the configuration keys

Follow these steps to delete obsolete application objects by disabling the **Keep update objects 5.0** and **Keep update objects 6.0** configuration keys.


> [!WARNING]
> <P>Do not manually delete application objects. Always use configuration keys to delete objects. For more information, see <A href="keep-update-objects-5-0-sysdeletedobjects41.md">Keep update objects 5.0 (SysDeletedObjects41)</A> and <A href="keep-update-objects-6-0-sysdeletedobjects60.md">Keep update objects 6.0 (SysDeletedObjects60)</A>.</P>



1.  Click **System administration** \> **Setup** \> **Licensing** \> **License configuration** to open the **License configuration** form.

2.  In the left pane, expand **Administration**.

3.  Clear the **Keep update objects 5.0** and **Keep update objects 6.0** check boxes, and then click **OK**.

  


