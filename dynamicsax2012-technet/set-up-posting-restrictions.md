---
title: Set up posting restrictions
TOCTitle: Set up posting restrictions
ms:assetid: e81ad5df-2a29-4278-988d-b07dfa24312e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg243236(v=AX.60)
ms:contentKeyID: 36059826
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- posting restrictions
- restrict posting
audience: Application User
ms.search.region: Global
---

# Set up posting restrictions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Posting restrictions determine whether specific users or user groups can post only journals that they create. Posting restrictions are set up for journal names. Use the **Journal names** form to specify posting restrictions for each journal name that you want to use the posting restrictions for.

1.  Click **General ledger** \> **Setup** \> **Journals** \> **Journal names**.

2.  Select the journal name to apply restrictions to.

3.  Click **Posting restrictions**.

4.  To set up posting restrictions by user group, select **By user group**. To set up posting restrictions by user, select **By user**.

5.  To restrict a user or group, select the check box next to the user ID or group name.
    

    > [!NOTE]
    > <P>When you set up posting restrictions, existing user group permissions are considered. If the user (or the user group that the user belongs to) does not have permission to post to the journal type that is assigned to the current journal name, the user or group is hidden, and you cannot define posting restrictions for that user or group.</P>



6.  Click **OK** to apply the restrictions and close the form.

## Results of the setup

When the specified users try to post a journal of a type for which they are restricted, they will be prevented from posting journals that they did not create. Users can select the **Show user-created only** check box in most journal forms to filter the journals to view only the journals that they can post.


> [!NOTE]
> <P>If additional users later are added to a user group, the posting restrictions that are specified for the user group apply to the new users. However, if a new user is added when you have the <STRONG>Posting restrictions</STRONG> form open, a message is displayed. You must close the <STRONG>Posting restrictions</STRONG> form and reopen it to apply the posting restrictions to the new user.</P>



## See also

[Posting restrictions (form)](https://technet.microsoft.com/en-us/library/hh227598\(v=ax.60\))

  


