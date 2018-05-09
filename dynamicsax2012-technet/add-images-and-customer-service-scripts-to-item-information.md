---
title: Add images and customer service scripts to item information
TOCTitle: Add images and customer service scripts to item information
ms:assetid: 098cad47-1a31-4851-b919-4a540b6d3cad
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497710(v=AX.60)
ms:contentKeyID: 62200032
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailMCRChannelListPage
---

# Add images and customer service scripts to item information 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to add images and scripts for customer service representatives to use when they sell an item through a call center. This information is included in the item record that the customer service representative sees when he or she talks to a customer.

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Related setup task</p></td>
<td><p>Set up up-sell/cross-sell.</p></td>
</tr>
</tbody>
</table>


## Add an image to an item record

Use this procedure to add an image to an item record.

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Select the item to add the image to, and on the **Action Pane**, on the **Product** tab, click **Edit**.

3.  In the **Released product details** form, on the **Action Pane**, on the **Product** tab, in the **Set up** group, click **Product image**.

4.  In the form that opens, click **New**.

5.  In the **Type** field, select the file type and then enter a brief description of the file contents. For example, file type might be .jpg or a URL, and the description might be *Premium bicycle helmet - Adult*.

6.  In the **Media usage** field, select whether the image is to be used internally or externally to the organization.

7.  Select the **Default image** check box to indicate that the image that you added is the default image for the item.

## Add a customer service script or note to an item record

Use this procedure to add one or more scripts or notes to an item record. Scripts can be used by a customer service representative when referencing or selling an item to a customer. Notes are intended to be read by the customer service representative only, whereas scripts are intended to be spoken by the customer service representative to the customer.

1.  Click **Product information management** \> **Common** \> **Released products**..

2.  Select the item to add the script to, and on the **Action Pane**, on the **Product** tab, click **Edit**.

3.  In the **Released product details** form, on the **Action Pane**, on the **Scripts** tab, click **Scripts**.

4.  In the **Scripts** form, click **New**, and in the **Category** field, select the product category of the item.

5.  In the **Priority** field, enter the priority in which the message will show.
    
    For example, if you add three scripts to an item, you might assign a priority of 1 to the first script, 2 to the second, and 3 to the third script. When a customer service representative views the scripts, the script with a priority 1 is first in the list of scripts.

6.  Select the **Active** check box to activate the script, and in the **Type** field, select whether you are adding a note or a script.

7.  In the **Script name** field, select the script. The text of the script will appear in the **Text** field.

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p><strong>Call center</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>Marketing Manager</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

