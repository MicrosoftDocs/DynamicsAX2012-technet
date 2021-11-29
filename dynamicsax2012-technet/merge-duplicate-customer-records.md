---
title: Merge duplicate customer records
TOCTitle: Merge duplicate customer records
ms:assetid: d0b4382c-86cc-46dc-88ef-c3a0c175d294
ms:mtpsurl: https://technet.microsoft.com/library/Dn497831(v=AX.60)
ms:contentKeyID: 62279209
author: Khairunj
ms.date: 11/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.MCRCustUnmergeWorkbench
- Forms.MCRMergeConfirmationForm
- MsDynAx060.Forms.MCRMergeConfirmationForm
- MsDynAx060.Forms.MCRCustUnmergeWorkbench
- customer merge
- duplicate customers
- merge customers
audience: Application User
ms.search.region: Global
---

# Merge duplicate customer records 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to resolve the issue of duplicate customer records in Microsoft Dynamics AX. Your database might contain duplicate records for several reasons. For example, a record might have inadvertently been entered twice, a new record might have been created for an existing customer who changed their name, or two customers may have merged their businesses. You can combine information to remove duplicate records in one of the following ways:

  - Export your customer list to a file, review the list for duplicates, and then generate a new customer list without the duplicates. Then import the updated file into Microsoft Dynamics AX and merge the records as appropriate.
    

    > [!NOTE]
    > <P>This list is updated outside of the Microsoft Dynamics AX client, so you can send it to a third-party service to be reviewed and updated if that’s appropriate for your business.</P>



  - Merge customer records manually by using the **Merge** form.

## Import a support file to identify and merge duplicate customer records

Use this procedure to import and process a file that identifies duplicate customers.

1.  Click **Call center** \> **Periodic** \> **Customer** \> **Merged customer upload**.

2.  Click the file folder icon next to the **File name** field, and select the file that you want to import.

3.  On the **Action Pane**, click **Import**. The data in the file is imported, and a list of valid customer accounts and corresponding duplicate accounts appears on the **Overview** tab. You can see more details about each account on the **General** tab.

4.  To merge records, take one of the following actions on the **Overview** tab:
    
      - To merge duplicate records for one customer, select the customer record, and on the **Action Pane**, click **Merge one**.
    
      - To merge duplicate records for all customers, make sure that no records are selected, and on the **Action Pane**, click **Merge all**.

5.  Next, verify which records were merged. Click **Call center** \> **Common** \> **All customers**.

6.  In the **All customers** list, the **Is merged** column indicates which customer records were merged.

7.  Double-click a customer record that was merged.

8.  At the top of the **Customers** form, a message indicates that the current customer record was merged with another customer record.

## Manually merge duplicate customer records

Use this procedure to search for and merge duplicate customer records.

1.  Click **Call center** \> **Journals** \> **Customer service**.

2.  In the **Customer service** form, in the filter, select the type of filter that you want to search on, enter the appropriate text, and then click **Search**. For example, you might select **Keyword** and then enter **Contoso**.
    
    The **Customer search** form opens and list all of the customer records that contain the information that you filtered on.

3.  Select the customer records that you want to merge, and then click **Merge**.
    

    > [!WARNING]
    > <P>(BRA) You can’t merge the customer records with different CNPJ/CPF IDs.</P>



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
<td><p>Retail configuration key</p>
<p>Call center configuration key</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>Sales manager</p></td>
</tr>
</tbody>
</table>


## See also

[Create a customer record](create-a-customer-record.md)

[Maintaining customer information](maintaining-customer-information.md)

  


