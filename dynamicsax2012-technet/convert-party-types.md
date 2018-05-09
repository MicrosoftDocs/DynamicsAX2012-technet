---
title: Convert party types
TOCTitle: Convert party types
ms:assetid: 56041df2-c9a2-40fe-b95c-0effb40718fd
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208963(v=AX.60)
ms:contentKeyID: 36057319
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Convert party types 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

There may be times when you have to update a record to change the party type from person to organization or from organization to person. For example, you may meet someone out in the field and create a party record that has a record type of organization. Later, you realize that the record type should be person. To make sure that the party record information is accurate, you can convert the party record type to person.

To convert a party record from one party type to another, you must first create a new party record of the correct type in the global address book. Then, you associate the record that you want to convert to the new party record. After you have made the new party association, delete the party record that has the incorrect record type.

For example, Nancy is part of the sales team for Fabrikam U.K. At a trade show in London, she meets six new prospects. Nancy creates a prospect party record for each prospect. When Nancy saves the records, each record is also created in the global address book. Fabrikam has set the default party record type in Microsoft Dynamics AX to be organization. However, two of the new prospects should have a record type of person. When Nancy returns from the sales conference, she must convert the party types of the two prospect records by using the following procedure.

This procedure can also be used for customer and vendor records.

## Convert a party type

1.  Click **Home** \> **Common** \> **Global address book**.

2.  On the **Action Pane**, on the **Global address book** tab, in the **New** group, click **Party** to create a new party record.

3.  In the **Party** form, on the **General** FastTab, select **Person** in the **Record type** field and enter the person’s name. This should be the name of the record that you will associate with the new party record.

4.  Close the party record.

5.  Click **Sales and marketing** \> **Common** \> **Prospects** \> **All prospects**. On the **All prospects** list page, select the prospect record for which you want to change the association.

6.  On the **Action Pane**, on the **Prospect** tab, in the **Maintain** group, click **Edit**.

7.  In the **Prospects** form, on the **General** FastTab, click **Change party association**.

8.  In the **Change party association** form, in the **New party record** field, select the new party record that you created in steps 2 and 3, and then click **OK**.

9.  Click **Home** \> **Common** \> **Global address book**. On the **Global address book** list page, select and delete the organization type party record from which you just dissociated the prospect record.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

