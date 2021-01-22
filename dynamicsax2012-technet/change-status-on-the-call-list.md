---
title: Change status on the call list
TOCTitle: Change status on the call list
ms:assetid: c8b626db-f312-4e01-ac06-2a05d0294122
ms:mtpsurl: https://technet.microsoft.com/library/Aa550869(v=AX.60)
ms:contentKeyID: 36059322
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Change status on the call list 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the following steps to change the status of a call list or targets of the call list.

## Change the status on a call list

1.  Click **Sales and marketing** \> **Common** \> **Telemarketing** \> **Call distributions**.

2.  Select the call list that you want to work with.

3.  Select the contact person for whom you want to change the status.

4.  Click **Functions**, and then select the new status.
    

    > [!NOTE]
    > <P>If you cancel the call, you are prompted to select a reason for the cancellation.</P>



The following table lists the changes that are possible for each original status.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Status</p></th>
<th><p>Call back</p></th>
<th><p>Closed</p></th>
<th><p>Canceled</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Open</strong></p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p><strong>Call back</strong></p></td>
<td><p>No</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="odd">
<td><p><strong>Closed</strong></p></td>
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>No</p></td>
</tr>
<tr class="even">
<td><p><strong>Canceled</strong></p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>No</p></td>
</tr>
</tbody>
</table>


**Yes** – The status can be changed to the new value.

**No** – The status cannot be changed to the new value.


> [!NOTE]
> <P>Depending on the settings in the <STRONG>Sales and marketing parameters</STRONG> form, you can create activities for the employee who is responsible for a call list when you change the status of a target of the call list.</P>



## Change the status of a target on the call list

1.  Click **Sales and marketing** \> **Common** \> **Telemarketing** \> **Call distributions**.

2.  Select the call list that you want to work with.

3.  On the **Targets** FastTab, select the target for which you want to change the status.

4.  Select the new status.
    
    You can change the status to **Open**, **Call back**, **Closed**, or **Canceled**. To change the status on a call list to **Open**, you must change the status of a target of the call list.

  


